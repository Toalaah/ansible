# Ansible

This repository contains the Ansible configuration used to keep my macOS and
Arch Linux configurations in sync across multiple machines.

---

## Prerequisites

If running on an Arch Linux machine, you must install the
[ansible-aur](https://github.com/kewlfft/ansible-aur) helper using

```shell
ansible-galaxy collection install -r requirements.yml
```
In order for the playbook to function properly.

## Configuration

There are a number of configuration variables which can be set to customize the
installation. These variables are controlled by a configuration file which can
be found [here](./config.yml).

## Running the Playbook

To run the playbook, run the following command from the project root directory

```shell
ansible-playbook --ask-become-pass playbook.yml
```

> **Note:** This playbook is designed to run on local machines, although it is
> probably also possible to run this on a remote server with some minor
> configuration tweaks.

## TODOs

- Install Yay (AUR helper) automatically
- Install fonts automatically

