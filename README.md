ASBRL-LINUX-NODE-EXPORTER
=========

Deploy an official Node Exporter (Linux) as a Docker container.

Requirements
------------

- Need to be Docker engine installed.

Role Variables
--------------

- BUILD: 'v1.0.1'
- CONTAINER_NAME: "node-exporter"
- DOCKER_CPU_PERIOD: 0
- DOCKER_CPU_QUOTA: 0
- DOCKER_MEMORY: 0
- CONTAINER_STATE: 'started'

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
