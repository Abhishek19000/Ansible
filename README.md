# Ansible

# Configuring Hadoop and starting cluster services using Ansible Playbook

# Before following the below steps one should have ansible and sshpass software installed on the controller node.

1. Keep the required software and files in the given folder.

2. Copy the hdfs-site.xml and core-site.xml in /namenode directory of controller node from namenode file of this repository.

3. Copy the hdfs-site.xml and core-site.xml in /datanode directory of controller node from datanode file of this repository.

4. Run the namenode.yml and datanode.yml playbook to configure the Hadoop cluster. 
  
               For ex: ansible-playbook namenode.yml 
