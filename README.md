ASBRL-LINUX-NODE-EXPORTER
=========

Deploy an official Node Exporter (Linux) as a Docker container.

Requirements
------------

- Need to be Docker engine installed.

Role Variables
--------------

- BUILD: 'v1.0.1'

Dependencies
------------

None

Example Playbook
----------------

    - name: Deploy Node Exporter
      include_role:
        name: asbrl-linux-node-exporter
      tags:
        - node-exporter 

License
-------

BSD

Author Information
------------------

Moegui.com
