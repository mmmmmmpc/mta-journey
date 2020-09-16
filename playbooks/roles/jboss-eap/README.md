JBoss EAP Domain Role
=========

A role to deploy, and configure two JBoss servers as master adn slave in RHEL7 / CentOS7

Requirements
------------

The system to run this role has to be subscribed (if RHEL), and configured with the base, optional and extras repos, as well as the JBoss EAP repo.

It can be done in RHEL with the following command (once subscribed)
```
subscription-manager repos --disable='*' --enable='rhel-7-server-rpms' --enable='rhel-7-server-extras-rpms' --enable='rhel-7-server-optional-rpms'      
```

Role Variables
--------------

TODO

Example Playbook
----------------

Example playbook is quite simple:

    ---
    - hosts: jboss[0:1].example.com
      roles:
        - jboss

License
-------

Apache 2.0

Author Information
------------------

Miguel Pérez Colino 
