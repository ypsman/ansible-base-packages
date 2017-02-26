base Packages
=============

Installs your base Packages on Debian and Ubuntu Systems

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.base-packages
          packages:
            - vim
            - htop
