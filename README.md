ansible-role-gnome-shell
========================

Role that install gnome-shell with Ansible

# Notes :
- Install Gnome 3.12 on Ubuntu with the ppa of the gnome team if gnome_with_ppa_staging: true
- Only tested with Ubuntu Trusty


# Usage example :
```
---
- hosts: localhost
  remote_user: root
  roles:
    - role: gnome-shell
      gnome_with_ppa_staging: true
```