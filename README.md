# Linux Desktop setup

Ansible-based setup process for new Linux desktop (Ubuntu) according
to my preferences.

## Core setup process

- install OS & log in
- create pubkey `ssh-keygen -t ed25519 -C "comment"`
- add ssh public key to GitHub account
- `sudo apt install git ansible`
- sudo ansible-pull -i localhost -U https://github.com/ijdickinson/linux-desktop-setup.git
