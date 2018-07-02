# VerosK.postgresql-addon-users

Make sure PostgreSQL users exists after installation.

Role Variables
--------------

Check `defaults/main.yml`

Dependencies
------------

This should be applied after `geerlingguy.posgresql` role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: postgres
      roles:
         - role: geerlingguy.postgresql
         - role: VerosK.postgresql-addon-users

License
-------

BSD

