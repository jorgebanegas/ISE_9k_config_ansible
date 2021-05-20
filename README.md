
**Cisco Catylst 9k ISE configuration with Ansible**

cisco-9k.yml - an example of a playbook that sends configs to a cat 9k

Contacts:

* Jorge Banegas ( jbanegas@cisco.com )


**Source Installation**


Run playbook file "cisco-9k.yml"

```bash
ansible-playbook -i inventory.yml cisco-9k.yml
ansible-playbook -i inventory.yml cisco-9k.yml --tags=show_test
```


