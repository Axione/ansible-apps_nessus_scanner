# ansible-apps_nessus_scanner

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_nessus_scanner-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_nessus_scanner)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_nessus_scanner.svg)](https://github.com/lotusnoir/ansible-apps_nessus_scanner/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_nessus_scanner?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_nessus_scanner)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_nessus_scanner)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_nessus_scanner)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Install and Tenable Nessus Scanner serveur

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_nessus_scanner
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_nessus_scanner


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.
