# hinemos-ansible

## Usage

```
yum -y install epel-release # CentOS 7
yum -y install ansible git

git clone https://github.com/froop/hinemos-ansible.git
cd hinemos-ansible
ansible-playbook -i hosts site.yml
#ansible-playbook -i hosts hinemosmanager.yml
#ansible-playbook -i hosts hinemosagents.yml
#ansible-playbook -i hosts hinemosweb.yml
```

## 参考

AnsibleでHinemosをインストールしてみた。 - てんこ  
https://tenko.hatenablog.jp/entry/2020/07/18/151757
