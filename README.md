NLCR.mariadb
=========

Empty role will install only MariaDB
defining:
```
mariadb_name: db_name will install your_db with access for vagrant:vagrat
mariadb_import: sql_file will import file into mariadb_name 
mariadb_state: MariaDB will be latest/present/absent (default is present)
mariadb_user/maridb_pass: will set user:pass
mariadb_priv: set priviliges (default is db_name.*:SELECT")
```

Example Playbook
----------------

```
- name: Maria simplest
  hosts: db
  roles: NLCR.mariadb
```
License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
