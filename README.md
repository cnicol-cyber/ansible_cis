Example RHEL8 CIS Ansible repo
=========

This is just an example repo for RHEL8 CIS hardening. 

Requirements
------------

Install collections listed in collections/requirements.yml

ansible-galaxy collection install -r collections/requirements.yml


Running the playbook
------------

Run the playbook as follows.


```bash
ansible-playbook rhel8_cis.yml -i inventory -u ec2-user -b
```
