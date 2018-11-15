# The playbook for OpenVPN Client installation on Ubuntu 16.04 LTS (Xenial Xerus)

### Install and configure OpenVPN Client on Ubuntu 16.04 LTS according to presets.

#### Very-very short description:
1. You can add your keys & certs in the template roles/openvpn-client/templates/client.conf.j2
2. You can change a destination group of hosts in inventories/stage/hosts (this path is default at moment in ansible.cfg)
3. You can change anything you wish because it is just an example.
