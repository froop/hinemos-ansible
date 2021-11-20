```
yum -y install epel-release # CentOS 7
yum -y install ansible git

git clone https://github.com/froop/hinemos-ansible.git
cd hinemos-ansible
ansible-playbook -i hinemosmanager hinemosmanager.yml
ansible-playbook -i hinemosagents hinemosagents.yml
```
