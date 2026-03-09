# UFW Firewall Setup

Install UFW:
- Sudo pacman -S ufw (For Arch/AUR based distro)

Enable Firewall:
- sudo systemctl enable ufw
- sudo systemctl start ufw

Allow SSH:
- sudo ufw allow ssh

Check status:
- sudo ufw staus
