# Ansible Role 

## Status

[![Travis CI](https://travis-ci.org/lordoftheflies/ansible-role-python.svg?branch=master)](https://travis-ci.org/lordoftheflies/ansible-role-python)

### Supported platforms

[![Platform](http://img.shields.io/badge/platform-Ubuntu_19.10-purple.svg?style=flat)](#)
[![Platform](http://img.shields.io/badge/platform-Ubuntu_19.04-purple.svg?style=flat)](#)

## Description

Role for setup Python runtime environment.

## Roadmap

* [ROADMAP.md](ROADMAP.md)

## References

* [docs.ansible.com](https://docs.ansible.com/)

## Requirements

### Production

* Ansible

### For Local Testing

* [Vagrant](https://www.vagrantup.com/) - (Tested using version 2.1.1)
* Vagrant plugins:
  * [vagrant-disksize (0.1.2)](https://github.com/sprotheroe/vagrant-disksize)
  * vagrant-vbguest (0.15.2) - Recommended [vagrant-vbguest](https://github.com/lordoftheflies/vagrant-vbguest)
  * vai (0.9.3) - For testing with multiple vms [vagrant-plugin-vai](https://github.com/lordoftheflies/vagrant-plugin-vai) 
* [Virtual Box](https://www.virtualbox.org/)
  * Tested using Version 5.2.14 r123301 (Qt5.6.1) 

## Variables

### defaults/main.yml

* [defaults/main.yml](defaults/main.yml) contains all of the required variables.

### project_name/site.yml example

* [example_ansible-role-python.yml](files/example_site.yml) may contain an example entry.

## Testing

To test with all VM's defined in Vagrantfile run the following:

```shell
cd ansible-role-ansible-role-python
vagrant up
```

To run on a specific VM's
```shell
vagrant up xenial
```

### VM's tested with Vagrant and Virtualbox

pass, fail, untested

| Distribution | Results  |
| ------------ | -------- |
| precise      | untested |
| trusty       | untested |
| xenial       | untested |
| bionic       | untested |
| CentOS 6     | untested |
| CentOS 7     | untested |

## Authors and License

* [László Hegedűs](mailto:laszlo.hegedus@cherubits.hu)

License: [Apache-2.0](Apache-2.0)

> **NOTE**: This skeleton generated using [galaxy-role-skeleton](https://github.com/cjsteel/galaxy-role-skeleton)
