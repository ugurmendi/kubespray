# kubespray
For the execution of the cluster we need to clone kubespray git repo first
after that we need to declere the ip addresses for nodes 
Finally for creating the cluster we need to execute the following command 
ansible-playbook -i inventory/mycluster/hosts.yaml --become --user=ubuntu cluster.yml --ask-become-pass
