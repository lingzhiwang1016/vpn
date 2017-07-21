# vpn
vpn配置指引


描述
客户端
配置

Installer (32-bit), Windows XP and later；
openvpn-install-2.3.4-I003-i686.exe；
windows-openvpn-client.zip；

nstaller (64-bit), Windows XP and later；
openvpn-install-2.3.4-I003-x86_64.exe；
windows-openvpn-client.zip；

Installer (32-bit), Windows Vista and later；
openvpn-install-2.3.4-I603-i686.exe；
windows-openvpn-client.zip；

Installer (64-bit), Windows Vista and later；
openvpn-install-2.3.4-I603-x86_64.exe；
windows-openvpn-client.zip；

Centos；
sudo yum install openvpn；
linux-openvpn-client.tar.gz；

Debian/Ubuntu；
sudo apt-get install openvpn；
linux-openvpn-client.tar.gz；

###### 1. 客户端下载安装
###### 2. 下载配置，并修改配置：
    将第五行的EIP替换为内网IP
    
###### 3. 将2中文件夹里所有的内容复制到openVPN 中的config文件夹里即可

备注：注意只能以管理员身份运行

