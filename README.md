packer-datacenter
================

Build Docker Datacenter hosts images with Packer.

Requirements
------------

- [Packer](https://www.packer.io/)    >= 0.10
- [Ansible](https://www.ansible.com/) >= 2.0
- [ovftool](https://www.vmware.com/support/developer/ovf/)

Usage
-----

    packer build \
      -var 'esxi_host=10.99.1.201' \
      -var 'esxi_password=<password>' \
      templates/datacenter-centos.json
