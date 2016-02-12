# Simple test Docker + LVM

### Requirements:
* CentOS host
* Ansible 1.8+
* Set device variable in play.yml

### Usage:
```
ansible-playbook -u $USER -i $HOST, play.yml --private-key=$SSH_KEY
```
