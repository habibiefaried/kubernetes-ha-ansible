# kubernetes-ha-ansible
* Modify the hosts file
* Initroot is basically a master who inits the cluster, meanwhile master is the master node that joining to the initroot
* Slave will be joining to init root
* Loadbalancer is using haproxy
* If everything just good, then run command: 'ansible-playbook -i hosts all.yaml'
* Seems that it's wrong to have 2 masters (1 initroot and 1 master)

# Tested on
* AWS Ubuntu 18.04

# CAUTION
This is only for fresh install! The script to add either master/worker nodes is under development

