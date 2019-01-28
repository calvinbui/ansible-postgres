[![Build Status](https://travis-ci.com/calvinbui/ansible-postgres.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-postgres)

# Ansible Postgres

Installs Postgres, creates a database and a default user

##  Requirements

N/A

## Role Variables

`postgres_version`: Version of postgres to install

`postgres_db_name`: Database to create

`postgres_db_user`: DB user name

`postgres_db_password`: DB user password


## Dependencies

N/A

## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
    - role: calvinbui.ansible_postgres
```

## License

GPLv3

## Author Information

http://calvin.me
