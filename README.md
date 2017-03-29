Ansible Role: NLTK
=================

[![Build Status](https://travis-ci.org/ScorpionResponse/ansible-nltk.svg?branch=master)](https://travis-ci.org/ScorpionResponse/ansible-nltk)

Simplest possible role to install NLTK and all data.

Requirements
------------

None.

Role Variables
--------------

* NLTK_DATA_DIR: '/usr/share/nltk_data'

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
