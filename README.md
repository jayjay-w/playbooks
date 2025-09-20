### Setup

 - Install ansible

```
sudo apt-install ansible
```

 - Deploy the playbooks


```
cd archie
ansible-playbook -i inventory.ini dotfiles.yml -K
ansible-playbook -i inventory.ini playbook.yml -K
```