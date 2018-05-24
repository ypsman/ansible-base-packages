base Packages
=============
[![Build Status](https://travis-ci.org/ypsman/ansible-base-packages.svg?branch=master)](https://travis-ci.org/ypsman/ansible-base-packages)
Installs and removes Packages.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.base-packages
          basepackages:
            - vim
            - htop
          basepackages_remove:
            - exim4
