## This folder containes the Roles for Configuring the entire Kubernetes Cluster on AWS Cloud using Ansible. 
- KubeMaster : For configuring the Master Node on AWS.
- KubeSlave : For configuring the Slave Node on AWS.
- KubeCluster.yml : Final Ansible Playbook including all roles.
- ec2.yml : Playbook for infrastructure setup(one ec2 instance for master node & 2 instance for slave)
- secure.yml : This contains the authentication credentials for AWS. 


## Steps : 
1. Create Ansible Vault File i.e secure.yml
2. Run the playbook for setting up nodes i.e ec2.yml
3. Then finally go for cluster setup i.e KubeCluster.yml
