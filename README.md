# OSCP Ansible Config

Configurations of my windows host. 


# How to use it

- Download the repo

- Run inside the folder
```ansible
ansible-galaxy install -r requirements.yml
```

-  Add the IP address and credentials of your Windows machine into the inventory file ./inventory/hosts

-  Run ansible-playbook main.yml inside this directory.
  ```ansible
ansible-playbook main.yml
```
