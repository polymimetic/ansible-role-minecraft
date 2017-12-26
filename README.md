# Ansible Role: Minecraft

[![Build Status](https://img.shields.io/travis/polymimetic/ansible-role-minecraft.svg?style=flat-square)](https://travis-ci.org/polymimetic/ansible-role-minecraft)
[![Release](https://img.shields.io/github/tag/polymimetic/ansible-role-minecraft.svg?style=flat-square)](https://github.com/polymimetic/ansible-role-minecraft/releases)
[![License: MIT](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-polymimetic.minecraft-blue.svg?style=flat-square)](https://galaxy.ansible.com/polymimetic/minecraft/)

Installs Minecraft for Linux.

## Requirements

No requirements.

## Dependencies

No dependencies.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    sample_variable: []

This is an example of a sample variable default.

## Example Playbook

To run the role, include it as follows:

    - hosts: all
      roles:
         - { role: polymimetic.minecraft, x: 42 }

## Credits

This role takes inspiration from the following Ansible roles:

- [geerlingguy.git](https://github.com/geerlingguy/ansible-role-git)

## License

This software package is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](./LICENSE) file for details.

## Author Information

This role was created in 2017 by [Polymimetic](https://github.com/polymimetic).

* ansible-role-minecraft generated using [ansible-role-skeleton](https://github.com/polymimetic/ansible-role-skeleton)