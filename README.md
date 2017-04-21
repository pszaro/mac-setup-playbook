# Mac Development Ansible Playbook

This repository is a fork of Jeff Geerlings and ricbra excellent repositories:

https://github.com/geerlingguy/mac-dev-playbook
https://github.com/ricbra/mac-dev-playbook

It is a stripped version suited to my needs while I test ansible.

For installation:

    $ git clone http://github.com/pszaro/mac-setup-playbook
    $ cd mac-dev-playbook
    $ ansible-galaxy install -r requirements.yml

    For Ansible < 2.0
    $ ansible-playbook -i inventory --ask-sudo-password main.yml
    For Ansible >= 2.0 use
    $ ansible-playbook -i inventory --ask-become-pass main.yml
    
