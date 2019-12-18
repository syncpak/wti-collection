WTI Ansible Collection
=========

This [Ansible](https://www.ansible.com/) collection provides a set of platform dependent configuration
 management modules specifically designed for  [WTI OOB and PDU devices](https://wti.com/) .

Requirements
------------

* Python 2.7 or 3.5+
* Ansible 2.9.0 or later
* Supported WTI firmware (DSM/CPM v6.58+, VMR 2.15+)
* Configuration command needs a user with Administrator privileges



Installation
-------

Ansible Collections were added as a technology preview in Ansible 2.8,
and are a new method of distributing namespaced Ansible components
that are not integrated into the core source tree.

They can be installed into a playbook-adjacent `collections`
directory, `~/.ansible/collections`, or the system-wide
`/usr/share/ansible/collections`, or you can modify Ansible's
configuration to specify custom locations.


Contribution
-------
At WTI we're dedicated to ensuring the quality of our products, if you find any
issues at all please open an issue on our [Github](https://github.com/syncpak/wti-collection) and we'll be sure to respond promptly!
Or you can always email us directly at support@wti.com


License
-------

Apache-2.0

Author Information
------------------
 - Ken Partridge (@syncpak)
