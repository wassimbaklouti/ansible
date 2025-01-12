execute the play book : 
ansible-playbook -i inventory.ini prepare_k8s_cluster.yml

verify connection with inventory machines : 
ansible all -m ping -i inventory.ini
