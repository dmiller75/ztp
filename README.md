# Zero Touch Provisioning (ZTP) using Ansible for FlashBlade

Within this repository is a set of ansible playbooks for use with Pure Storage FlashBlade ZTP process. They are provided as is and are currently a work in progress. 

## Pre-Requisites

ZTP requires DHCP and the FlashBlade to be in setup mode and bootstrapped.

  `fbsetup --ztp`

### Ansible Pre-Requisites
These playbooks in part, take advantage of the [Pure Storage Ansible FlashBlade Collection](https://github.com/Pure-Storage-Ansible/FlashBlade-Collection).
