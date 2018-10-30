vscode-ansible
=========

Ansible role to manage a VSCode installation on Mac or Linux (Debian-based)

Requirements
------------
Ansible (tested with 2.7.0)

What does it do?
--------------
* If you don't have VSCode, it will download and install the latest
* If you do have VSCode, it will download and install the extensions in defaults/
* If you add something to the list it will only install the new one

Quick start
--------------
Check defaults/ for the list of extensions you would like to install then

`ansible-playbook tests/test.yml --ask-become-pass`

License
-------
MIT