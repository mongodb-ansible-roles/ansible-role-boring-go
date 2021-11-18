Ansible role for ansible-role-boring-go
==================================

Installs boring go

[![GitHub Actions](https://github.com/cbiphuk/ansible-role-ansible-role-boring-go/workflows/Molecule%20Test/badge.svg)](https://github.com/cbiphuk/ansible-role-ansible-role-boring-go/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/cbiphuk/ansible-role-ansible-role-boring-go/workflows/Release/badge.svg)](https://github.com/cbiphuk/ansible-role-ansible-role-boring-go/actions?query=workflow%3A%22Release%22)

Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| name | desc | type | default | required |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-boring-go
      vars:
        install_dir: /opt/boring
        src_url: https://storage.googleapis.com/go-boringcrypto/go1.15.8b5.linux-amd64.tar.gz
        version: 1.15
        create_symlink: true
```

License
-------

[Apache License](LICENSE)
