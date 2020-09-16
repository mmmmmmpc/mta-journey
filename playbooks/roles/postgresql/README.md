PostgreSQL Role
=========

A role to deploy, initialize and configure a PostgreSQL database in RHEL8

Requirements
------------

The system to run this role has to be subscribed (if RHEL), and configured with the default repo

It can be done in RHEL with the following command (once subscribed)
```
subscription-manager repos --disable='*' --enable='rhel-8-for-x86_64-baseos-rpms' --enable='rhel-8-for-x86_64-appstream-rpms'
```

Role Variables
--------------

TODO

Example Playbook
----------------

Example playbook is quite simple:

    ---
    - hosts: db.example.com
      roles:
        - postgresql

License
-------

Apache 2.0

Author Information
------------------

Miguel Pérez Colino 

Based on work by Sergio Ocón Cardenas:
https://github.com/chargio/postgresql-vagrant
