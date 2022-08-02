# dainslef-cloud-environment-config
Debian package for setting up my VPS enviroment in a short time.

Build package:

```html
<!-- Generate deb package in current directory. -->
$ dpkg-deb --build .
<!-- Generate deb package in custom path. -->
$ dpkg-deb --build . xxx_path/dainslef-cloud-environment-config.deb
```

Usage:

```html
<!-- Use Ansible to run the playbook. -->
$ ansible-playbook playbook.yaml
```
