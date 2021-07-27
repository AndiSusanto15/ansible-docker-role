# Batutah docker roles
Ansible playbook to install docker on Ubuntu

Support for:
- Ubuntu Hirsute 21.04
- Ubuntu Groovy 20.10
- Ubuntu Focal 20.04 (LTS)
- Ubuntu Bionic 18.04 (LTS)

## Vars

```yml
docker_user: batutah
```

## Sample playbook

```yml
---
- hosts: localhost
  become: yes
  vars:
    docker_user: batutah

  roles:
    - { role: batutah.docker }

```

## Docker Documentation

https://docs.docker.com/engine/install/ubuntu/

&copy; 2021 [Andi Susanto](https://jurnal.batutah.id)