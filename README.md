base Packages
=============

Installs your base Packages

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.base-packages
          packages:
            - vim
            - htop
