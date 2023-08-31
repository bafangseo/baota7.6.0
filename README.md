# 宝塔--7.5.16

1.宝塔LinuxPanel-7.5.16

2、将升级包上传到服务器中的/root目录

3、解压文件：unzip LinuxPanel-7.5.16.zip

4、切换到升级包目录：cd panel

5、执行升级脚本：bash update.sh

6、删除升级包：cd .. && rm -f LinuxPanel-7.5.16.zip && rm -rf panel


 # 宝塔--7.6.0
 进入目录
 cd /root/
 
 下载
 wget https://raw.githubusercontent.com/bafangseo/baota7.6.0/master/LinuxPanel-7.6.0.zip
 
解压
 unzip LinuxPanel-7.6.0.zip

进入目录
 cd /root/panel
 
运行降级脚本
bash update.sh


 
另外
宝塔升级指定版本
wget -O update.sh http://download.bt.cn/install/update.sh && sh update.sh 7.44


