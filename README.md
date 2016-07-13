packer-templates
================

Collection of templates to build VMs images with Packer.

Requirements
------------

- [Packer](https://www.packer.io/)    >= 0.10
- [ovftool](https://www.vmware.com/support/developer/ovf/)

Usage
-----

Build VMWare ovf with

    packer build  \
      -var 'esxi_host=10.99.1.201' \
      -var 'esxi_password=<packer_esxi_password> \
      templates/centos-7-esxi.json

License
-------

MIT

Author Information
------------------

Andrea Tosatto ([@\_hilbert\_](https://twitter.com/_hilbert_))
