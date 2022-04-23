# Software configuration management

## Ansible

### Setup
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

#### Homebrew
https://formulae.brew.sh/formula/ansible

### Running
```
ansible-playbook -i hosts ./roles/main.yaml
```

### Creating roles

> "A role is a complete unit of automation that can be reused and shared"

https://galaxy.ansible.com/docs/finding/content_types.html#ansible-roles

```
ansible-galaxy init docker
```