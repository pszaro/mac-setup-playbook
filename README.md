                   
Introduction
-----------------
Currently testing Ansible to setup my mac environments quickly and effecently. If anything, I hope to gain a better understanding on Ansible on all platforms.
                   
GIT Repo Location
-----------------
https://github.com/pszaro/mac-setup-playbook.git
                   
Things to do
-----------------

This repository is forks of [Jeff Geerlings](https://github.com/geerlingguy/mac-dev-playbook) and [ricbra](https://github.com/ricbra/mac-dev-playbook) excellent repositories:

It is a very stripped version suited to my needs while I test ansible.

For installation:

    $ git clone http://github.com/pszaro/mac-setup-playbook.git
    $ cd mac-dev-playbook
    $ ansible-galaxy install -r requirements.yml

    For Ansible < 2.0
    $ ansible-playbook -i inventory --ask-sudo-password main.yml
    For Ansible >= 2.0 use
    $ ansible-playbook -i inventory --ask-become-pass main.yml


