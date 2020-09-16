PostgreSQL Role
=========

A role to deploy, initialize and configure a PostgreSQL database in RHEL8

Requirements
------------

The system to run this role has to be subscribed (if RHEL), and configured with the default repo

It can be done in RHEL with the following command (once subscribed)
```
subscription-manager repos --enable='jb-eap-7.3-for-rhel-8-x86_64-rpms'
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
