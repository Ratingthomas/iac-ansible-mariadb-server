Role DB
=========

Install mariadb-server

Requirements
------------

- Tested on debian linux.

Role Variables
--------------

```yml
db_name: my_database
```

Dependencies
------------

No dependencies

Example Playbook
----------------

```yml
- hosts: db_servers
  become: true
  vars:
    db_name: project_db
  roles:
    - role_db
```

License
-------

MIT
