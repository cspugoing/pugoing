![](http://www.cspugoing.com/pcimg/help/module.png)

# 通用模块

通用模块是一款实现灯光无线远程控制的设备，安装时无需改造原有线路，无需替换传统开关，只需要安装在普通开关的86底盒内，即可实现灯光的智能化控制

#### 模块接线方式：

模块铜柱部分接火线和灯线，零线选接（有零线接零线）

排线部分接传统开关，如下图，左起第一根接开关公共线（通常是开关的火线）

左起第二、三、四根线分别对应通知的L3、L2、L1

<img src="http://open.cspugoing.com/img/help/module-1.png" style="zoom:50%;" /><img src="http://open.cspugoing.com/img/help/module-2.png" alt="" style="zoom:50%;" />

#### 接入系统步骤：

（1）如果模块只接了火线，没有接零线，普通开关为翘板式开关

	a、语音命令“小乔管家，发现单火自锁模块”，如果有接零线，则命令为：“小乔管家，发现零火自锁模块”
	b、按一下墙面开关按钮
	c、主机回应“发现新设备，通用模块”
	d、在小程序里面可以查看到新增加的通用模块
（2）如果模块只接了火线，没有接零线，普通开关为自复位式开关

	a、语音命令“小乔管家，发现单火自锁模块”，如果有接零线，则命令为：“小乔管家，发现零火自锁模块”
	b、按一下墙面开关按钮
	c、主机回应“发现新设备，通用模块”
	d、在小程序里面可以查看到新增加的通用模块
（3）模块配置

模块有普通模式和定制模式两种，在普通模式下，每一路开关都只是控制各自的灯光。在定制模式下，可以设置不同的组合来控制其他路的灯光，并且同一个模块可以混接翘板式和自复位式两种开关。如下图，具体可以根据实际需要来进行设置

​	普通模式：

​	面板控制灯光一样，如2.1开关面板

​	<img src="http://open.cspugoing.com/img/help/module-3.png" style="zoom:50%;" />

```
点击右上角设置按键：
选择房间：就是模块连接的面板分配房间
普通模式：点击可以切换成定制模式
信号中继：开关与系统之间通过中继器互联；开关中控位置离远，需要中继传输信号时使用
区域标识：可以区分面板，防止多个面板混淆
分配灯光：修改每一路灯光的图标和名称
替换设备：当设置出现问题，而场景或其他操作中又用到此设备时，直接提替换不需修改场景或其他操作
删除设备：直接删除解绑
```

定制模式：

![](http://open.cspugoing.com/img/help/module-4.png)

如上图

```
输入配置： 复位开关表示模块连接的开关为自复位开关
		 自锁开关表示模块连接的开关为翘板式开关
		 根据实际连接开关选择
```

```
输出配置： 开关模式表示就是和正常开关一样，按一下开，再按一下关
		 只关模式表示每次按开关都是关
		 与一路互斥表示和第一路相反，例如当第三路开时，第一路就是关，反之一样
		 与二路互斥表示和第二路相反，例如当第三路开时，第二路就是关，反之一样
```

<img src="http://open.cspugoing.com/img/help/module-5.png" alt="" style="zoom:80%;" />	<img src="http://open.cspugoing.com/img/help/module-6.png" alt="" style="zoom:80%;" />     

如上图，当选择三路，输出配置选择二路输出和三路输出时，表示第三路开关可以控制二路和三路两路的灯光；模式选择如上面介绍一样

当选择三路，输出配置选择一路输出、二路输出和三路输出时，表示第三路开关可以控制一路、二路和三路所有的灯光，模式选择如上面介绍一样

选择一路或二路，设置上面和第三路一样；当第三路控制所有路的灯光时，一路和二路也可以自由选择控制灯的路数及模式，与第三路是没有关系的；灵活自由设置

#### 解绑方式：

长按模块对接开关面板上的按键，按键对应灯光状态发生变化松开（如果是对应灯光是开的，直到灯光灭了松开，反之一样）；再长按此按键，直到对应灯光状态发生变化松开（如果是对应灯光是灭的，直到灯光打开松开，反之一样），管家会提示“已删除此设备”，解绑成功