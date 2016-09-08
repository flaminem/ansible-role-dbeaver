ansible-role-vagrant
====================

Install DBeaver with Ansible


# Local installation : (ansible need to be installed)
```
git clone https://github.com/flaminem/ansible-role-dbeaver.git
ansible-playbook -i "localhost," --ask-sudo-pass --connection=local installation.yml
```

# Simple Usage :
```
---
 - hosts: all
   roles:
    - dbeaver
```

# Usage with version specification
```
---
 - hosts: all
   roles:
    - role: dbeaver
      vagrant_version: "3.7.3"
```
