# 简介


> EPEL 是yum的一个软件源,里面包含了许多基本源里没有的软件了，但在我们在使用epel时是需要安装它才可以了，EPEL，即Extra Packages for Enterprise Linux的简称，是为企业级Linux提供的一组高质量的额外软件包，包括但不限于Red Hat Enterprise Linux (RHEL), CentOS and Scientific Linux (SL), Oracle Enterprise Linux (OEL)

## 手动安装
系统：centos7
安装步骤：

1. cd ~ && wget http://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
2. rpm -ivh epel-release-latest-7.noarch.rpm
3. yum repolist
4. yum clean all && yum makecache
