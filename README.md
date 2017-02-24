# Devbox
Instant OS X provisioning :)

## How to use
- Install gcc `xcode-select --install`
- Install pip `sudo easy_install pip`
- [Install Ansible](https://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip) (2.0 or later) `sudo pip install ansible`
- Run the relevant playbook `ansible-playbook osx.yaml -i inventory --ask-become-pass`
