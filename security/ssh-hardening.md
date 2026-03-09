# SSH Hardening Basics

## Check SSH service

Command:
systemctl status ssh

---

## Disable root login

Edit SSH config file:

sudo nano /etc/ssh/sshd_config

Find:

PermitRootLogin yes

Change to:

PermitRootLogin no

---

## Restart SSH

sudo systemctl restart ssh
