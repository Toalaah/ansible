# Ansible

Ansible configuration for my macOS and Arch Linux configurations.

---

## Requirements

- ansible

## Running the Playbook

**Optional:** if running on an Arch Linux machine, install the
[ansible-aur](https://github.com/kewlfft/ansible-aur) helper with
`ansible-galaxy collection install -r requirements.yml` in order to download /
update packages.

To run the playbook, run `ansible-playbook --ask-become-pass playbook.yml` from
the project root directory.

> **Note:** This playbook is designed to run on local machines, although it is
> probably also possible to run this on a remove one with some configuration
> tweaks.

## TODOS

- Install yay (aur helper) automatically
- Install fonts automatically

