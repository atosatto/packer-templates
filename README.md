packer-templates
================

Collection of templates to build VMs images with Packer.

Requirements
------------

- [Packer](https://www.packer.io/)    >= 0.10
- [Ansible](https://www.ansible.com/) >= 2.0
- [ovftool](https://www.vmware.com/support/developer/ovf/)

Usage
-----

Build VMWare ovf with

    packer build \
      -var 'esxi_host=10.99.1.201' \
      -var 'esxi_password=<password>' \
      templates/standard-centos.json
