# ansible-playbook-node-monitoring
Hosts are provisioned with vagrant (virtualbox)
For learning purpose

### Prerequisite
- Ansible
- Vagrant

##### Generate SSH Key
```
ssh-keygen -t rsa -b 4096 -C "vagrant-key" -f $PWD/key/vagrant-key
```

#### Vagrant setup
```
vagrant up
```

## Provision with Ansible
```
ansible-playbook -i inventory playbooks/*.yaml
```
