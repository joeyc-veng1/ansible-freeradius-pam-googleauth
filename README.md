# freeradius-pam-googleauth
Ansible Playbook to build FreeRADIUS servers with PAM and Google Authenticator (OTP) support

Works with pam_unix and pam_sss methods

Tested on Ubuntu 22.04, joined to a Samba 4.15 domain.

Example Playbook

```
---
# Playbook to configure the Google Authenticator OTP servers

- hosts:
    - {{ list them here... add however many lines you want }}

  roles:
    - pamonly-radius-servers
    - google-authenticator
```
