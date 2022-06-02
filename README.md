# Ansible FLARE VM Role

[![CI](https://github.com/gr4unch3r/ansible-role-flare-vm/actions/workflows/ci.yml/badge.svg)](https://github.com/gr4unch3r/ansible-role-flare-vm/actions/workflows/ci.yml)

Ansible role to install [FLARE VM](https://github.com/mandiant/flare-vm) Windows malware analysis distribution.

## Requirements

- Windows 10 Version 1809 VM configured for remoting with Ansible (e.g. [gr4unch3r/windows-10](https://app.vagrantup.com/gr4unch3r/boxes/windows-10/versions/10.0.17763))
- [ansible.windows](https://galaxy.ansible.com/ansible/windows)

## Role Variables

- `flare_passwd` - User password (Default: 'vagrant')

## Example Playbook

```
- hosts: all
  gather_facts: true
  roles:
    - gr4unch3r.flare_vm
```

## License

MIT

## Author Information

gr4unch3r [at] protonmail [dot] com
