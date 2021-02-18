
## 联想小新锐7000


### 配置信息 

| 部件  | 信息 |
| ---- | --- |
| CPU  | Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz |
| 内存 | 8g DDR4 2400Mhz x2 |
| 存储 | TOSHIBA Xg3 256G Nvme <br> TOSHIBA 1TB 5400RPM HDD |
| 显卡 | Intel HD Graphics 630 <br> NVIDIA GeForce GTX 1050 |
| 声卡 | Realtek ALC235 |
| 有线网卡 | Realtek RTL8111 PCI-E Gigabit Ethernet Adapter |
| 无线网卡 | Broadcom BCM94352z 802.11ac Wireless Network Adapter |



### 已知问题 

1. HDMI可用，但是不能插着启动。。。。

2. OpenCore linux暂时无法引导

### 适用系统

macOS High Sierra 10.13 

macOS Mojave 10.14

macOS Catalina 10.15 (感谢@xoomp)

macOS BigSur 11

### 安装方法

1. 在制作完启动盘或者安装完系统之后打开终端执行以下命令
 ```bash 
    git clone https://github.com/Erf172/Lenovo_XiaoXin_Rui7000_Hackintosh.git
    sudo diskutil mount disk0s1   #disk0s1为你电脑本地磁盘或优盘的EFI分区
```

2. 将你想要使用的引导方式的文件夹内的内容复制到EFI分区内的EFI文件夹即可





    
### 系统截图
![SysScreen](https://img.vim-cn.com/c2/d17e9b8c636a14195bf46146ed2e7820f0203b.png)
![SysScreen](https://img.vim-cn.com/75/50295d7e606b3b6212c0a79165f0781a2317d8.png)
![SysScreen](https://img.vim-cn.com/7c/cd70229df6e34d1b6a91f6776f89fa27e62adf.png)
![SysScreen](https://img.vim-cn.com/c1/814ae09fcab74d11f9e6f2afbe1ebf4546ac76.png)
![SysScreen](https://img.vim-cn.com/88/2171017186249783873b120b18083d7e4155af.png)


### 更新日志

#### 2020.1.28

    1. 更新了clover至5103

    2. 更新了一些驱动文件

#### 2020.3.4

    修复了睡眠会不定时唤醒的问题


#### 2020.3.25

    1. 更新CLOVER至5107

    2. 更新OpenCore至0.5.6

    3. 可以使用系统内置的读卡器

    4. 更新一部分内核驱动文件

#### 2020.7.13

    1. 更新CLOVER至5119

    2. 更新OpenCore至0.5.9

    3. 更新一部分内核驱动文件


#### 2021.2.16

    1. 更新OpenCore至0.6.5

    2. 支持Big Sur

    3. 更新一部分内核驱动文件

### 其他


1. OpenCore 引导切换为启动的时候按住键盘上的`ESC`键 ，如果想要体验白苹果的切换体验，可以在Windows下安装Bootcamp支持软件(安装完可能需要手动更新一次才能识别APFS分区。)   
    **注意：安装完Bootcamp可能D盘会被隐藏，可以手动去磁盘管理挂载，或者格式化一次(注意备份数据)**
2. OpenCore中的 systemuuid需要修改为win10 系统中查询到的UUID，否则可能激活失效

3. 如果想要自己手动安装的话，可以[点击这里](https://www.erf172.tk/2019/02/13/Hackintosh-Installation-on-Lenovo-Xiaoxin-Rui7000-1/)作为参考进行安装   
~~大部分笔记本都可以按照这个思路进行安装~~



### 感谢

[黑果小兵的部落阁：精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)

[xjn's blog: 使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543)

[宪武大大oc部件](https://github.com/daliansky/OC-little)