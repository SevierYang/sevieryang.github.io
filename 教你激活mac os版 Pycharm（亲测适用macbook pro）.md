
获取注册码地址： http://idea.lanyus.com

 

输入注册码之后可能会报 this license XXXXXXXX has been cancelled 的错误，解决方法如下：

 

终端： sudo vi /etc/hosts

 

在最后一行加入： 

0.0.0.0 account.jetbrains.com
 

保存，退出。重新申请注册码，搞定！
