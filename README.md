# freeradius-pam-googleauth
Ansible Playbook to build FreeRADIUS servers with PAM and Google Authenticator (OTP) support

Example Playbook

---
# Playbook to configure the Google Authenticator OTP servers

- hosts:
    - {{ list them here... add however many lines you want }}

  roles:
    - pamonly-radius-servers
    - google-authenticator
