## 联想小新锐7000


### 配置信息 

>>>>>>> 1701ae844a20b0d70c5ca152f66d496fc5a89f0f

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
>>>>>>> 1701ae844a20b0d70c5ca152f66d496fc5a89f0f

1. Fn亮度快捷键

2. 无法调节亮度请将CLOVER/kexts/Other/AppleBacklightFixup.kext放入L/E或S/L/E可修复亮度

3. HDMI可用，但是不能插着启动。。。。

### 适用系统

macOS High Sierra 10.13 

macOS Mojave 10.14

### 安装方法

1. 在制作完启动盘或者安装完系统之后打开终端执行以下命令
 ```bash 
    git clone https://github.com/Erf172/Lenovo_XiaoXin_Rui7000_Hackintosh.git
    sudo diskutil mount disk0s1   #disk0s1为你电脑本地磁盘或优盘的EFI分区
```

2. 删除相应的EFI分区的CLOVER文件夹并复制替换即可   


    
### 系统截图
![SysScreen](https://img.vim-cn.com/6a/9ffd8b467320a6a6d5be385263b456cafd1888.png)
![SysScreen](https://img.vim-cn.com/49/5369b1e3bfd366b259dcd7aaa3d1ebdc77ade5.png)
![SysScreen](https://img.vim-cn.com/ca/f827ce420e148d75a905f8fd8c293272f9688f.png)
![SysScreen](https://img.vim-cn.com/0e/5ad521869b78531f3f094a10c3d8f747d4b703.png)
![SysScreen](https://img.vim-cn.com/2d/52e5b23fd51d3d54d48c641c18d31aae6bb9c7.png)


### 更新日志


1. 睡眠修复

2. HDMI可以使用了

3. 应该不会再次开机卡住了~~学艺不精闹出的笑话~~~

4. 更新了clover至4871

5. 更新了一些驱动文件
<<<<<<< HEAD


### 其他

如果想要自己手动安装的话，可以[点击这里](https://www.erf172.tk/2019/02/13/Hackintosh-Installation-on-Lenovo-Xiaoxin-Rui7000-1/)作为参考进行安装
~~大部分笔记本都可以按照这个思路进行安装~~

