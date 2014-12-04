ansible-sample
==============

* ansible のインストール方法(CentOS6)

```shell
 # sudo yum install epel-release
 # sudo yum install ansible
```

* ansible の実行方法


```shell
 # cp hostlit-sample hostlist
 # vi hostlist
 # cd ansible-sample
 # export ANSIBLE_HOSTS=hostlist
 # ansible-playbook --private-key=~/.ssh/id_rsa allset.yaml
```

