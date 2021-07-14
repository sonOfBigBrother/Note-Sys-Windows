## 查询命令概述
- systeminfo：显示关于计算机及OS的详细配置信息
- ipconfig：显示IP地址信息
	- /all：显示本机TCP/IP配置的详细信息
- netstat：打印网络连接、路由表、连接的数据统计、伪装连接以及广播域成员
	- a：显示所有连接的socket
	- n：直接使用IP地址，不通过域名服务器
	- o：显示计时器
- sysdm.cpl：打开系统属性窗口，个人一般喜欢通过该命令在“高级”选项下设置环境变量。
- netsh wlan show profiles：查看所有WLAN连接的配置文件名列表
  - netsh wlan show profile "Wifi名称" key=clear：查看WiFi密码
- control：打开控制面板

