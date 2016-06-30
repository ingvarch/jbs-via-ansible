# Using

- Clone repository
```
git clone git@github.com:ingvarch/jbs-via-ansible.git
```
- Change dir to jbs
```
cd jbs-via-ansible/ansible/playbooks/jbs/
```
- Create ansible config from example and modify it
```
cp ansible.cfg.example ansible.cfg
```
- If you use bastion you can create local ssh config and modify it
```
cp ssh.cfg.example ssh.cfg
```
- Update "group_vars" and "inventory" files
- For installation docker and run containers - teamcity, youtrack, upsource on Host server
```
ansible-playbook -i inventory/dev host.yml 
```
- For installation docker and run containers with teamcity agents
```
ansible-playbook -i inventory/dev tc-agent.yml 
```

# Requirements

1. Ansible 2.*
2. Vagrant + VirtualBox (for local)

# Also

1. Ansible uses Ubuntu 14.04


### JBS - JetBrain Services :)
