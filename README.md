（支持流量计费、按时间计费、支付宝付款）

除去lnmp的安装时间，仅需3分钟即可完成。
# 联系方式
[TG讨论组](https://t.me/feiyangss)
cd /www/wwwroot/你的文件夹名
git clone -b master https://github.com/Anankke/SSPanel-Uim.git tmp && mv tmp/.git . && rm -rf tmp && git reset --hard
git config core.filemode false
wget https://getcomposer.org/installer -O composer.phar
php composer.phar
php composer.phar install
cd ../
chmod -R 755 你的文件夹名/
chown -R www:www 你的文件夹名/
ln -s /www/wwwroot/你的文件夹名/sql/glzjin_all.sql /www/backup/database/
# 代码部分

##### 要求centos 7 x64

### ss-panel mod魔改版一键脚本
```
yum install screen wget -y &&screen -S ss 
wget -N --no-check-certificate https://raw.githubusercontent.com/itrydo/otoone/master/ss-panel-v3-mod.sh && chmod +x ss-panel-v3-mod.sh && bash ss-panel-v3-mod.sh

```
### ss-panel v3一键脚本
```
yum install screen wget -y &&screen -S ss
wget -N --no-check-certificate https://raw.githubusercontent.com/itrydo/otoone/master/ss-panel_node.sh && chmod +x ss-panel_node.sh && bash ss-panel_node.sh

```


选项都差不多,直接输入1安装即可

默认账号：91vps

默认密码：91vps

节点服务器运行脚本

yum -y install wget
wget -N --no-check-certificate https://raw.githubusercontent.com/itrydo/otoone/master/ss-panel-v3-mod.sh && chmod +x ss-panel-v3-mod.sh && bash ss-panel-v3-mod.sh
输入2，之后需要输入前端站点的domain，token，node_id。

doamin： 域名或者ip都可以，前边要加http或者https。不要弄错，否则可能出现无法推送使用记录的情况。

mukey(token)：默认回车，除非你另行设置过。

node_id：还记得上边那个图里边的ID吗？就是那个了。。。

其他

修改ssh端口

vi /etc/ssh/sshd_config

service sshd restart #重启生效

管理ssr

supervisorctl {start|stop|restart} ssr

修改mysql密码
wget http://soft.vpser.net/lnmp/ext/reset_mysql_root_password.sh

sh reset_mysql_root_password.sh

# 关于
码农一只，欢迎打赏。
本程序主要用于：

- 企业内部局域网搭建，所以信息均处于高度加密下。比VPN更能满足企业安全需要。
- 海外留学生回国线路搭建。
- 自用的游戏加速，信息搜索。

**切勿用于商业用途，可能会触犯法律**

作者接定制功能、页面、脚本、游戏加速器，活儿保证让你满意~
