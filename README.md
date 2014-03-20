Check_MK Agent Installer
========

Installs the Check_MK Monitoring Agent

Requirements
------------

Tested with Ansible 1.4 on CentOS, RHEL and FEDORA

Role Variables
--------------

Check_MK agent rpm version could be change, so it would good to refer to 'http://mathias-kettner.com/download/'

    vars:
	check_mk_version: '1.2.4-1'


Usages
------

    ansible-galaxy install ravibhure.check_mk-agent

Also check the [Ansible Galaxy](https://galaxy.ansibleworks.com/intro) about page.

License
-------

GPL

Author Information
------------------
Ravi Bhure <ravibhure@gmail.com>

[GitHub project page](https://github.com/ravibhure/ansible-check_mk-agent)
