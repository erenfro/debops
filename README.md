## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) contrib-foodsoft

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.contrib--foodsoft-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/5939)

For more details checkout the [README from the Foodsoft project][foodsoft.readme].

The role will setup Foodsoft ready for production.

Used Technologies:

* [nginx](http://nginx.org/)
* [Phusion Passenger](https://www.phusionpassenger.com/)
* [MariaDB](https://mariadb.org/)/[MySQL](https://www.mysql.de/)

This role is based on the following documentation:

* [Deployment (Debian)](https://github.com/foodcoop-adam/foodsoft/wiki/Deployment-%28Debian%29)
* [SETUP_DEVELOPMENT.md](https://github.com/foodcoops/foodsoft/blob/master/doc/SETUP_DEVELOPMENT.md#manual-configuration)
* [Dockerfile](https://github.com/foodcoops/foodsoft/blob/master/Dockerfile)

And other bits and pieces.

The default of Foodsoft is to redirect to HTTPS so be sure to setup a certificate for example via [debops.pki].

[debops.pki]: https://galaxy.ansible.com/detail#/role/1588
[foodsoft.readme]: https://github.com/foodcoops/foodsoft

### Installation

This role requires at least Ansible `v1.8.4`. To install it, run:

```Shell
ansible-galaxy install debops.contrib-foodsoft
```

### Documentation

More information about `debops.contrib-foodsoft` can be found in the
[official debops.contrib-foodsoft documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-contrib-foodsoft/docs/).


### Role dependencies

- `debops.secret`
- `debops.ruby`
- `debops.nginx`
- `debops.mariadb`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`contrib-foodsoft` role was written by:

- [Robin Schneider](http://ypid.de/) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-(gpl-3))

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
