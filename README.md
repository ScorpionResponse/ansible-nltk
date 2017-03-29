Ansible Role: NLTK
=================

[![Build Status](https://travis-ci.org/ScorpionResponse/ansible-nltk.svg?branch=master)](https://travis-ci.org/ScorpionResponse/ansible-nltk)

Simplest possible role to install NLTK and data as needed.

Requirements
------------

None.

Role Variables
--------------

* NLTK_DATA_DIR: Set the installation directory for the shared data.
  Default: '/usr/share/nltk_data'
* NLTK_DATA_PACKAGE_IDS: The data packages to download.  Use 'all' to get
  everything.
  Default: ['punkt', 'stopwords']

Dependencies
------------

Depends on ScorpionResponse.pip

Example Playbook
----------------

Example usage:

    - hosts: all
      roles:
         - { role: ScorpionResponse.nltk }

License
-------

BSD

Author Information
------------------

Github: https://github.com/ScorpionResponse
