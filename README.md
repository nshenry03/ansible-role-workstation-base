Ansible Role: workstation-base
==============================

[![Build Status](https://travis-ci.org/nshenry03/ansible-role-workstation-base.svg?branch=master)](https://travis-ci.org/nshenry03/ansible-role-workstation-base)

Base role to be installed on all Nick Henry workstations

Requirements
------------

- [Ansible 2.5 or later](https://github.com/nshenry03/ansible-role-vim/#requirements)
- Git must be installed to download dependencies


Role Variables
--------------

-   [geerlingguy.ntp](https://github.com/geerlingguy/ansible-role-ntp#role-variables)
-   [nshenry03.bash](https://github.com/nshenry03/ansible-role-bash/#role-variables)
-   [nshenry03.vim](https://github.com/nshenry03/ansible-role-vim/#role-variables)

Dependencies
------------

-   [geerlingguy.ntp](https://github.com/geerlingguy/ansible-role-ntp)
-   [nshenry03.bash](https://github.com/nshenry03/ansible-role-bash)
-   [nshenry03.vim](https://github.com/nshenry03/ansible-role-vim)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - src: https://github.com/nshenry03/ansible-role-workstation-base

License
-------

MIT

Author Information
------------------

This role was created in 2018 by [Nick Henry](http://TechNickal.net).
