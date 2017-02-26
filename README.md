base Packages
=============
[![Galaxy](https://img.shields.io/badge/galaxy-ypsman.basepackages-blue.svg)](https://galaxy.ansible.com/ypsman/base-packages)


Installs your base Packages on Debian and Ubuntu Systems

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.base-packages
          packages:
            - vim
            - htop
