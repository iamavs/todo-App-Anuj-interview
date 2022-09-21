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


<img width="733" alt="Screenshot 2022-09-21 at 11 44 03 AM" src="https://user-images.githubusercontent.com/95232494/191427893-e5744f6a-1127-40ef-9b6d-41d445dea295.png">
