Mod_Cluster Role
=========

A role to deploy, and configure a Mod_Cluster + Apache HTTPD webserver as load balancer in RHEL8

Requirements
------------

The system to run this role has to be subscribed, and configured with the default repos.


It can be done in RHEL8 with the following commands (once subscribed):
```
subscription-manager repos --enable='jb-coreservices-1-for-rhel-8-x86_64-rpms'
```

Role Variables
--------------

TODO (Currently hardcoded IP for App Servers)

Example Playbook
----------------

Example playbook is quite simple:

    ---
    - hosts: lb.example.com
      roles:
        - mod_cluster

License
-------

Apache 2.0

Author Information
------------------

Miguel Pérez Colino 
