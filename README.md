# ansible-todo-deploy
Deploy a todo app with mysql with dockercompose using ansible.

# Installing Docker and Dockercompose in the remote host
ansible-palybook docker-install-playbook.yaml

# Deploying todo-application and sql app using Docker Compose
ansible-playbook deploy-todo-playbook.yaml