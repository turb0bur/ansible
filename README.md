# [Ansible](https://docs.ansible.com/)

Ansible learning project

### [Installation on Ubuntu](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)

```bash
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo add-apt-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible
```

### Running playbooks

```bash
$ ansible-playbook -i <PATH_TO_INVENTORY_FILE> <PATH_TO_PLAYBOOK_FILE>
```

1. LAMP (Linux, Apache, MySQL, PHP) stack with firewall rules
2. Adding users (2 groups: admins and developers) with 