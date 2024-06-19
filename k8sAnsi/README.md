# Ansible Roles
- Roles allow you to define default variables that can be overridden when the role is used in an Ansible Playbook. This makes it easier to tailor a role's behavior to different environments or use cases without modifying the role itself -Red Hat

example: We want to install and configure k8s in x number of machines. there is no way we could do this by going through every single machine. therefore we can configure Ansible roles

# Commands
- ansible-galary role init kubernetes

