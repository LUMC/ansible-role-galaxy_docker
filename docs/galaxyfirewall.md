# Galaxyfirewall role

## Function
Sets ufw firewall to accept galaxy firewall ports by copying a ufwprofile into ufw directory.

Ansible removed the ssh rules on one instance so the firewall is opened for SSH by default as well.

## Variables
 variable | usage 
---|---
galaxy_web_port | A port number
galaxy_ftp_port | A port number
galaxy_sftp_port | A port number
ufw_profile | Default name is "galaxy". The name of the profile in your /etc/ufw/applications.d directory

