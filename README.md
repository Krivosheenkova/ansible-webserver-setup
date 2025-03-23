This playbook created and tested for Debian 11 Bullseye.
## Requirements
* **Ansible** >= 2.18 (tested with 2.18.3)

## Usage
Update the `inventory.ini` file with your target host address.

Ensure SSH access is configured:
1. SSH login should work without password
2. Use the same user that is specified as ansible_use

Then you can simply run the playbook:
```bash
ansible-playbook playbook.yml 
```

