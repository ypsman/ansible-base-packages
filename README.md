base Packages
=============
[![Build Status](https://travis-ci.org/ypsman/ansible-base-packages.svg?branch=master)](https://travis-ci.org/ypsman/ansible-base-packages)
Installs your base Packages on Debian and Ubuntu Systems

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.base-packages
          packages:
            - vim
            - htop
