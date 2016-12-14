Ansible Role: VIMRC v1.0
===

[![Build Status](https://travis-ci.org/mm0/ansible-role-vimrc.svg?branch=master)](https://travis-ci.org/mm0/ansible-role-vimrc)

An Ansible role that sets up system-wide vim defaults (/etc/vimrc.conf).  Uploads plugins to target host(s)


Requirements
--

Vim-enhanced

Role Variables
--

Available variables are listed below, along with default values:

```yml
vim_config:
- syntax on
...
```

#####Please view vars/main.yml for full list of configurations


#####Includes yaml plugin, javascript plugin, php-dock plugin, recover plugins.
#####Includes custom color map (ir_black)

Dependencies
--

None 

Example Playbook
--
```yml
- hosts: webservers
  roles:
  - ansible-role-vimrc
```

License
---------------

BSD-2

Author Information
------------------

[Matt Margolin](mailto:matt.margolin@gmail.com)

[mm0](https://github.com/mm0) on github
