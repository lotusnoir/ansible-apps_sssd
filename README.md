# ansible-apps_sssd

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_sssd-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_sssd)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_sssd.svg)](https://github.com/lotusnoir/ansible-apps_sssd/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_sssd?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_sssd)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_sssd)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_sssd)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install sssd in order to check ldap server for ssh login.

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_sssd
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_sssd


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

