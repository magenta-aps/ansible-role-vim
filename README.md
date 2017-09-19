Vim
===

Installs the excellent Vim text editor

Usage
-----

To utilize this role, add it as a submodule to the roles folder of ansible:

    cd ansible/roles/
    git submodule add git@github.com:magenta-aps/ansible-role-vim.git vim

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
