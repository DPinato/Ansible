# Raspberry Pi Ansible

A personal Ansible repository used to manage and maintain my Raspberry Pi devices.

I use this repository to automate common administration tasks, configure services and keep my Raspberry Pi environment consistent.

## Repository structure

- `hostfiles/` – Ansible inventory files containing my Raspberry Pi hosts and groups.
- `files/` – Supporting files and templates used by the playbooks.
- `*.yaml` – Ansible playbooks for configuring and managing the Raspberry Pis.

## Requirements

- SSH key-based access to the Raspberry Pis.
- Sudo privileges on the target machines.
- A correctly configured inventory file.

## Usage

There are sample commands in sample_commands.txt

## Notes

This is a personal repository. Playbooks and configurations are tailored to my Raspberry Pi environment and may need adjusting before being used on other systems.
