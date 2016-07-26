ansible-docker-swarm
====================

Role to set up a Docker Swarm Cluster on CentOS.

This role can create both Docker Swarm manager and worker nodes.
This is done using variables.

Example Playbook
-------------------------

    - hosts: managers
      roles:
        - { role: docker-swarm, docker_role: 'manager' }

    - hosts: workers
      roles:
        - { role: docker-swarm, docker_role: 'worker' }

License
-------

GPLv2

Author Information
------------------

oddgeir.gitlestad@gmail.com
