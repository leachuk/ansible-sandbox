# Ansible Commands

- Check hosts can connect
```bash
ansible all -i inventory/hosts.inventory -m ping
```

- Run playbook with specified host inventory file using `-i`  option
```bash
ansible-playbook -i inventory/hosts.inventory site.yml
```