Role Name
=========

Installs PHP Composer on the server.

Requirements
------------

None.

Role Variables
--------------

Default variables are set in `defaults/main.yml`.

Dependencies
------------

No dependency on other Ansible Galaxy roles.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hspaans.composer, become: true }

License
-------

MIT

Author Information
------------------

This role was created in 2020 by [Hans Spaans](https://github.com/hspaans).
