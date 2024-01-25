# About
It's a group of **useful ansible playbooks** for DevOps engineers, System administrators and developers.

# How
Each playbook has a different purpose and scripts are not related to each other.
Find a useful playbook from this readme file then use it.

# List
+ check docker installation
+ docker compose up using ansible

### check-docker-installation.yaml
Check docker (or even other programs) is installed or not on nodes and save the result in a file.

### docker-compose-up-using-ansible.yaml
Provision docker compose services using ansible.

Consider "community.docker.docker_compose" module limitations which are explained in official documentation. For example, the docker-compose version should be less than version 2.

# Contribution
Feel free and don't hesitate contributing to this repository.
