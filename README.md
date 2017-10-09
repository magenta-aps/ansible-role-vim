Vim
===

Installs the excellent Vim text editor

Usage
-----

To utilize this role, add it to the `requirements.yml` file inside the ansible folder:

    - src: git+https://github.com/magenta-aps/ansible-role-vim.git
      version: master
      name: vim

Requirements
------------

Must be run against a `apt` capable system.

Example Playbook
----------------

    - hosts: all
      roles:
         - vim

License
-------

MPLv2

Author Information
------------------

skeen - Emil Madsen
