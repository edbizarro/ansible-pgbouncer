PgBouncer
=========

Install and configure pgbouncer.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: yes

    roles:
    - role: edbizarro.pgbouncer
      pgbouncer_databases:
        - dbname: testing
          options:
            host: localhost
            port: 5432
            user: testing
            password: 123456
      pgbouncer_users:
        - username: testing
          password: 123456


License
-------

Apache 2.0
