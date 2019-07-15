[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Vagrant-blue.svg)](https://galaxy.ansible.com/wluisaraujo/vagrant) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-vagrant.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-vagrant)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Vagrant](https://www.vagrantup.com/)
------------

Description
------------

 * Ansible role for Vagrant
 
Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - vagrant
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
