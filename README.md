## 安装宝塔

CentOS安装脚本

```
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh
```

Ubuntu/Deepin安装脚本

```
wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && sudo bash install.sh
```

Debian安装脚本

```
wget -O install.sh http://download.bt.cn/install/install-ubuntu_6.0.sh && bash install.sh
```

Fedora安装脚本

```
wget -O install.sh http://download.bt.cn/install/install_6.0.sh && bash install.sh
```



## 管理宝塔

卸载

```
/etc/init.d/bt stop && chkconfig --del bt && rm -f /etc/init.d/bt && rm -rf /www/server/panel
```

堡塔命令行工具箱 （仅限6.x以上版本的面板，5.x以下版本请点击右侧目录 - 旧版本管理宝塔）

```
bt
```

重启面板

```
bt 1
```

停止面板

```
bt 2
```

启动面板

```
bt 3
```
