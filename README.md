# General purpose ansible roles

OS: Ubuntu

## customization

- Remote user definition (name, password)
- root password
- System hostname

## default-firewall

Basic iptables firewall to block incoming and forwarded trafic to the host

## docker

Install docker and create a specific user to manage containers. Also supports installing docker inside LXC containers.

## hardening

General hardening roles

### automatic_security_updates

Enable apt unattended upgraded for security updates on Ubuntu

### general

Basic system tuning with option to disable ipv6

### kernel hardening

Basic kernel hardening parameters

## ssh-config

Configuration and basic hardening of sshd