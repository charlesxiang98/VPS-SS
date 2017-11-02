# VPS-SS
deploy VPS and Shadowsocks 

Hello guys, I just want to tell you how to deploy your own SS on VPS. 
Ok,I will give an example with Bandwagon.Of course, Vultr is also good. Here are 9 points.
1.You need to get an account on bandwagon or vultr, both of them are great. 
2.choose an item and pay your money.
3.click client area, input your email address and password, click services----my services, "kiwiVM Control Panel” under Management.
4.cick main controls, click stop
5.install new OS, choose " debian-7-x86_64”，and reload.
6.in bandwagon, they will send you an IP address,password and SSH port through email.
7. open terminal on Macbook, ssh root@ip  # this ip is that vps gives you
8.input the following codes that involve 3 lines
1)wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks.sh
2)chmod +x shadowsocks.sh
3)./shadowsocks.sh 2>&1 | tee shadowsocks.log

9.dowload Shadowsocks.link:https://sourceforge.net/projects/shadowsocksgui/files/dist/             #choose the suitable version

That's it, very simple.
