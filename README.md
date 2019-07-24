# ansible-quickipa
Ansible roles to quickly install IPA for testing

This project is in NOT meant for production use.

This project is meant to quickly and easily setup a FreeIPA or
Red Hat Identity Management Test Environment.  It's meant as an
alternative to [ansible-freeipa](https://github.com/freeipa/ansible-freeipa)
when you need to use the official ipa-\*-install commands.

Setting up an inventory file to run the playbooks should look
very similar to an inventory file for ansible-freeipa.  It does
not support the same level of flexibility however.  Flexibility 
is limited to keep complexity down.

An example of how to setup the inventory is included here under
inventory/hosts.
