## <span style="color:#008c8c">Linux常用指令</span>

- ls : 展示当前目录下所有文件夹
- su root : 切换 root 用户
- ifconfig : 查看interface config
- service network restart : 重启网络服务
- hostname : 查看主机名
- hostnamectl : 查看主机配置信息
- hostnamectl set-hostname  更改的名字：修改主机名
- ssh root@IP : 可以通过ssh协议登录远程主机（首先要能ping到远程主机，IP可以被域名代替）
- grep : 筛选 
  - ls /usr/sbin/	|  grep  service 	// 从前面执行的结果中筛选含有service的项