
# REDIS CLUSTER

Ansible Playbook to deploy and maintain several Redis Clusters (1-Master/n-Slaves) on top of a Corosyn/Pacekamer cluster. Features:
  - Multiple Redis Cluster
  - Master/Slave with multiple slaves
  - Serialized roll-out (one-by-one) to update redis configuration without service interruption
  - Compatible with Centos 6.5 "Center of Internet Security" hardening best practices


Notes:
- Remove hostname from localhost resolution (/etc/hosts)
- Grant hostname resoulutions between all cluster nodes
