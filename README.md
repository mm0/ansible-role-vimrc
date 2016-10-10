# README.md

# Ansible Role: VIMRC v1.0

An Ansible role that sets up system-wide vim defaults (/etc/vimrc.conf).  Uploads plugins to target host(s)

![travis-ci](https://travis-ci.org/mm0/ansible-role-vimrc.svg?branch=master)

## Requirements

Vim-enhanced

## Role Variables

Available variables are listed below, along with default values:

  vim_config:
  - syntax on
  ...

  please view vars/main.yml for full list of configurations


  Includes yaml plugin, javascript plugin, php-dock plugin, recover plugins.
  Includes custom color map (ir_black)

## Dependencies

None 

## Example Playbook

    - hosts: webservers
      roles:
      - ansible-role-vimrc

## License

MIT

Author Information
------------------

[Matt Margolin](mailto:matt.margolin@gmail.com)

mm0 on github
