Keeping this directory to prevent some packer nasty such as

```bash
# [ ... ]
Build 'vmware-iso' errored: lstat output-vmware-iso: no such file or directory

==> Some builds didn't complete successfully and had errors:
--> vmware-iso: lstat output-vmware-iso: no such file or directory

==> Builds finished but no artifacts were created.
```
