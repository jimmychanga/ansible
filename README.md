
# Joe's Ansible Repo #

This repo is used for Ansible learning. It's currently being leveraged to support provisioning of a Cisco Modeling Lab instance and a virtual machine lab hosted on two VMware servers.

File Structure:

```text
ansible
   |
   |--network
   |  |--inventory/
   |  |   |--
   |  |
   |  |--playbooks/
   |  |   |--templates/
   |  |   |--
   |  |
   |  |--ansible.cfg
   |
   |--servers/
   |  |
   |  |--inventory/
   |  |  |
   |  |  |--development/
   |  |  |   |--hosts.ini
   |  |  |   |--group_vars/
   |  |  |   |--host_vars/  
   |  |  |
   |  |  |--testing/
   |  |  |   |--hosts.ini
   |  |  |   |--group_vars/
   |  |  |   |--host_vars/
   |  |  |
   |  |  |--production/
   |  |      |--hosts.ini
   |  |      |--group_vars/
   |  |      |--host_vars/
   |  |
   |  |--playbooks
   |  |   |--templates/
   |  |   |--sshd-config-playback.yml
   |  |   |--system-updates-playbook.yml
   |  |
   |  |--ansible.cfg
   |
   |--playbooks
```
