# Docker_pxc_Ansible


Setup Pecrona Xtradb cluseter on Docker container with Ansible.

# Requirements:

 * Ansible version 2.9
 
# Responsibilities of this setup.

 * Install docker and python-docker packeges
 * Create Percona Xtradb Cluster on docker container
 
# How to use?

  1. To fill the information on nodes in the "hosts" file. 
     
     Exp. 
        swarm_manager ansible_host=192.168.5.50 ansible_user=user ansible_ssh_pass=1234 ansible_sudo_pass=1234
  
  2. To fill the needed environment variable in the "all" file from the "group_vars" directory.
  
  3. Run playbook "docker_pxc.yml". 
