# Ubuntu Setup

An Ansible-based setup for Ubuntu Server

## How to Use
1. SSH/open a console to the machine
2. Clone repo and move to the directory
3. Create config file by copying `config.dist` to `config`
    - To get the interface value, run `ip a`
    - Known default values are:
        - Proxmox + Ubuntu: `ens18`
        - VirtualBox + Ubuntu: `enp0s3`
4. Start setup with `bash setup.sh`
    > Hint: 46 Wong DVD's for you
5. Reboot machine
