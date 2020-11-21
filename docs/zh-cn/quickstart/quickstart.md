## LogicLab编程工具下载与安装

登录翌控科技官网https://www.nxtrol.com/download.html 下载LogicLab Automation Suite最新标准版本,目前分为无INtime和有INtime版,根据需求选择下载。如果您使用的控制器经过了深度定制化，请联系该控制器厂商提供专门经过优化了的LogicLab编程工具：

![](_images/1.png)

下载完成后，建议关闭360或者其他安全软件后使用管理员权限进行安装，根据提示一步一步完成安装，如使用x86+Windows平台，请参考INtime章节进行软件安装工作：

![](_images/2.png)


## Logiclab初体验
LogicLab初始界面如下图所示：

![](_images/4.png)

### 扫描网络内的目标设备
 点击扫描网络，LogicLab自动识别连接的目标设备(需要该设备支持自动扫描功能)。

![](_images/5.png)
 
新建工程，输入工程名称。

![](_images/6.png)


 点击工具栏连接目标设备，右下角显示CONNECTED表示已经连接。

![](_images/7.png)

### 添加PLC程序
 右击工程栏的工程名字，选择添加的程序语言。 输入程序的名称把程序分配给指定的任务（程序必须放在任务里才能运行）。

![](_images/8.png)

![](_images/9.png)

添加PLC指令，拖拽ADD运算块到梯形图中。 添加变量，选择变量类型。

![](_images/10.png)

![](_images/11.png)

### 设备上运行PLC程序
点击“编译”与“下载”按钮，将PLC程序下载到设备上运行。

 ![](_images/12.png)

### 调试PLC程序
通过点击“调试”按钮，进入调试模式

![](_images/13.png)