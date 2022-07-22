# Setting up the Plain Linux serever:

I have used Ubuntu Server for this 

sudo add-apt-repository ppa:deadsnakes/ppa
 sudo apt-get update
 sudo apt-get install python3.7

sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible



# ansible-todo-deploy
Deploy a todo app with mysql with dockercompose using ansible.

# Installing Docker and Dockercompose in the remote host
ansible-palybook docker-install-playbook.yaml

# Deploying todo-application and sql app using Docker Compose
ansible-playbook deploy-todo-playbook.yaml
