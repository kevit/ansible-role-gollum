original idea https://github.com/jonmbake/gollum-easy-install

Usage
```
- import_playbook: ansible-role-gollum/examples/deploy_nginx.yml
- hosts: all
  tasks:
    - name: Run role
      include_role:
        name: ansible-role-gollum
```
