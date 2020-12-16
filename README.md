# Boinc Ansible Playbook
Ansible playbook to deploy BOINC client.

## Usage

### Configure
Update 'hosts' inventory and create 'credentials.yml' (Copy credentials.yml.example).

### Run
        ansible-playbook -i hosts site.yml

### Tested on
Debian 10
CentOS 8
Ubuntu 18.04 and 20.04
Alpine linux edge
