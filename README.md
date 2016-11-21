# 用于开发的虚拟机

基于 Vagrant 和 Ansible

## 常用命令

- `vagrant up`
- `vagrant provision`
- `vagrant provision ansible`, 这里的 ansible 是一个主机名
- `vagrant reload`
- `vagrant destroy`

## 调试

参考 https://www.vagrantup.com/docs/other/debugging.html


`VAGRANT_LOG=error vagrant provision ansible` 得到的这个不是错误

~~~
ERROR loader: Unknown config sources https://github.com/mitchellh/vagrant/issues/4585
~~~
