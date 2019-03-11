# Elasticsearch_Diagnostics_Ansible
Quickly get the Elasticsearch Cluster Diagnostics with Ansible


* Add the role to a master host in your inventory file
* Add your username and password under host_vars/hostname
* Run `ansible-playbook -i INVENTORY cluster-diagnostics.yml`