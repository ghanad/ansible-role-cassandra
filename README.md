Role Name
=========

install cassandra cluster.

Requirements
------------

put apache-cassandra*.tar.gz in `/opt/` on local machine

java

Role Variables
--------------

All variables are in default/main.yml



Example Playbook
----------------

    - hosts: servers
      serial: 1
      roles:
         - cassandra

    hosts file:
      [servers]
      192.168.1.1 rack=rack1
      192.168.1.2 rack=rack2
      192.168.1.3 rack=rack3
      
**Note:** run this role in serial 

peygir issue: 10
