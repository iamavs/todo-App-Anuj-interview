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

<img width="762" alt="Screenshot 2022-09-21 at 11 45 12 AM" src="https://user-images.githubusercontent.com/95232494/191428070-0f522a89-09a7-47e5-812f-17bb29a36930.png">
