# Ansible OpenVPN Setup

## Requirements
- Ansible 2.9+
- Ubuntu 20.04 server
- Root or sudo access

## Description
This repository contains a collection of Ansible playbooks to automate the setup and cleanup of an OpenVPN server on Ubuntu 20.04. The playbooks are designed to simplify the installation, configuration, and maintenance of OpenVPN, making it easy to deploy and manage your VPN infrastructure.

## Playbooks
- **openvpn_setup.yml**: Installs, configures, and finalizes the OpenVPN server setup.
- **cleanup_openvpn.yml**: Cleans up the OpenVPN server installation, removing all related packages, configurations, and rules.

## Usage

### Setup OpenVPN Server
1. Clone this repository.
2. Modify the `openvpn_setup.yml` playbook to suit your environment.
3. Run the playbook:
   ```bash
   ansible-playbook -i your_inventory_file openvpn_setup.yml
