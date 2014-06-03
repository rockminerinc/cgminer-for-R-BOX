#R-BOX挖矿教程

###前期准备

#####**选择比特币钱包
我们建议您首先注册一个在线钱包（如openblock.com、blockchain.info），并使用该钱包的地址作为您挖矿分红的地址，或者您可以使用本地钱包的地址，不建议客户直接使用交易平台上的钱包地址。

####**钱包使用说明
[参考指引](http://www.shroomery.org/forums/showflat.php/Number/19116760)

#####注意：
在线钱包一定要使用双重验证，绑定移动手机和安全邮箱，它们将保护您账户的安全性，帮助您在忘记密码等情况下恢复您的账号。

####**配套硬件
12V/5A的电源适配器（需要客户自行购买，建议购买30元左右价格的，不建议购买10多元的）和Mini USB数据线（R-Box自带）。

###开始设置

如果您的电脑系统为Windows XP系统，则需先下载并安装以下驱动（Win7/Win8系统无需安装）[下载链接](http://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx)

所有Windows系统都需按以下步骤安装:

#####第一步.
[下载软件](https://github.com/rockminerinc/cgminer-for-R-BOX/blob/master/cgminer-win0.3.1.zip)

#####第二步、安装驱动

* 连接电源适配器和USB数据线;
* 
* 解压压缩包cgminer_windows.rar;

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image001.jpg)

* 双击文件”zadig_xp_2.1.0“,单击菜单栏Options，选择”List All Device“。

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image002.jpg)

* 在下拉菜单中选择相应的WinUSB驱动（CP2012 USB to UART Bridge Controller）。

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image003.jpg)

* 点击Install Drive按钮

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image005.jpg)

* 程序安装成功：

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image006.jpg)

* 安装结束。

#####第三步、设置挖矿参数
*设置矿池：打开Cgminer文件夹，选择cg.cmd（或者cg），右键选择“编辑”，更改矿池和钱包地址:

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image008.jpg)

* 官方cg.cmd默认eligius矿池，若您使用eligius矿池，只需更改钱包地址（可以是你E池注册账户中生成的地址，也可以是您的任意钱包地址），任意密码都可以。

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image009.jpg)

###### 注意：如果使用其他矿池，请参考矿池网站提供的网址，端口与用户名。

* 设置芯片工作频率：频率有效范围为270M，当您修改频率参数后请保存。

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image010.jpg)

###开始挖矿

* 双击cg.cmd文件，挖矿开始。

![](http://www.rockminer.com/handbook%20of%20R-BOX.files/image012.jpg)
