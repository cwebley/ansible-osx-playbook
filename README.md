# ansible-osx-playbook
Automated Setup for a new Mac

## Testing this playbook
Create an OSX VM using Virtualbox + Vagrant by following [geeringguy's repo](https://github.com/geerlingguy/macos-virtualbox-vm)
Take a snapshot after install to ensure it can be re-tested. And after xcode install.

## Settuping up a new Mac
1: `xcode-select --install`

2: Install Ansible:
    - Run the following command to add Python 3 to your $PATH: export PATH="$HOME/Library/Python/3.8/bin:/opt/homebrew/bin:$PATH"
    - Upgrade Pip: sudo pip3 install --upgrade pip
    - Install Ansible: pip3 install ansible
