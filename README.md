# IP-address-checker
A quick and easy way to check if any IP address is in use within the network.
It takes an IP address as an input from the user and checks it against all network devices defined in the inventory file.
It then generates a report on which interfaces the IP address is configured and then emails the interface details to the project owner.

Software dependencies:
clay584.parse_genie role
sshpass python library
Jinja templates
SMTP
Ansible Vault to encrypt and secure the login credetials
