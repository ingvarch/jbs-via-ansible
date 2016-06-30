# Using

1. git clone
2. cd jbs-via-ansible/ansible/playbooks/jbs/
3. cp ansible.cfg.example ansible.cfg # and modify
4. cp ssh.cfg.example ssh.cfg # and modify
5. Update group_vars and inventory files
6. ansible-playbook -i inventory/dev host.yml # For installation docker and run containers - teamcity, youtrack, upsource
7. ansible-playbook -i inventory/dev tc-agent.yml # For installation docker and run containers with teamcity agents

# Requirements

1. Ansible 2.*
2. Vagrant + VirtualBox (for local)

# Also

1. Ansible uses Ubuntu 14.04


### JBS - JetBrain Services :)
