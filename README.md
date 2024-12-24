![image](https://github.com/user-attachments/assets/d9913a87-95a7-4cde-aed0-7687b4230d0f)


## EK3用户手册 ⭐
这里是EK3用户操作手册，包含EK3使用方法，应用程序使用方法，以及使用过程中的注意事项。

### 🌈 欢迎使用EK3
[EK3](https://jmlstudio.cn/)是一个桌面级多媒体控制器项目，在具有科技感外观的同时，可以满足桌面级多媒体控制需求，拥有指纹解锁，音量控制，音乐控制，自定义宏按键等多种控制功能。EK3配备了1.28寸240*240分辨率的触摸显示屏，可以显示时间，日期，天气等信息，同时也具备了定时器，番茄时钟等高频使用工具。

### 初次使用 🚀🚀🚀
初次使用需要下载**EK Home**进行配置，**EK Home**是专门为EK3设计开发的桌面应用程序，可以对EK3进行高度自定义配置，目前已支持windows系统和macOS，Linux适配正在开发中，对应版本的下载地址：

[EK-Home-application-windows](https://github.com/Ethan-Pan/EK3-User-manual/releases/tag/EK-Home-V1.3)

EKHome-application-macOS(暂未上线)

### EK Home使用方法
- 连接设备 
 
配置EK3时，需要将设备与电脑通过Type-c进行连接，然后点击EK Home中的“连接”按钮。连接成功之后，“连接”按钮会变为“已连接”且不可选中。首次配置EK3时需要点击“连接”按钮，后续使用EK Home将会自动连接。

![image](https://github.com/user-attachments/assets/b032ecfa-4905-4ca0-a3b9-ce71804442b3)

- 用户名设置

请输入您的用户名，用户名会显示在EK3的目录页面与蓝牙名称中，目前仅支持英文与数字输入。

![image](https://github.com/user-attachments/assets/30d2a400-8032-45e7-ab2d-d92ce0f146f1)

- 地区设置

请选择您所在的地区，EK3所显示的天气信息会根据您选择的地区来进行推送与同步。目前仅支持广东省的几个主流城市，后续更多的城市将陆续上线。

![image](https://github.com/user-attachments/assets/529168a4-f50c-401b-8e6f-2c11c05875c0)

- 电量显示
  
EK3表盘中的绿色能量条为电量条，低于20%会变为红色。选中电量显示会将目前电池电量的百分比显示在表盘中。

![image](https://github.com/user-attachments/assets/326a49b7-cc4d-4c3d-bc98-ab31e29550a5)

- LED颜色设置
  
EK3侧边配备了LED灯条，可以显示多种模式效果。您可以在EK3上来进行选择，此处的设置用来选择LED的底色，只对常量模式与呼吸模式有效。

![image](https://github.com/user-attachments/assets/27160844-80c9-4dd4-9ac2-4836eaed9608)

- 睡眠区间设置
  
为了节省电量与保护屏幕，EK3在睡眠区间会停止工作。请您选择合适的睡眠区间，如果没有选择，默认的睡眠区间为23:00-09:30。如果您想在睡眠区间唤醒EK3，请短按EK3的开机键。

- 深度省电模式
  
开启深度省电模式会关闭EK3的常量显示，屏幕亮屏10s后会自动熄屏，熄屏状态下不影响指纹、旋钮等功能的使用，触摸屏幕会再次点亮。

![image](https://github.com/user-attachments/assets/4e553d70-8583-4a05-8943-8ba24193a699)

- 指纹密码
  
请您输入指纹认证成功后所要输入的密码，该功能为电脑解锁设计。因EK3无法获得windows与Mac OS底层权限，无法接入windows hello与Mac指纹识别，所以EK3通过模拟外置键盘向电脑发送开机密码来完成电脑解锁。使用指纹解锁时，需要将电脑调整为输入密码的页面即可。

![image](https://github.com/user-attachments/assets/353aedb8-976f-405d-8c95-f2b59b6a2b92)

- 添加指纹
  
点击‘+’号即可开始录制指纹信息，请您在EK3指纹模组开启蓝光时，请在15s内，按压抬起手指4-6次，直到蓝光熄灭，闪烁绿光，EK Home提示录制成功之后，命名您的指纹信息，完成指纹录制。**注意：有部分情况，指纹模组只闪烁绿色，但是EK Home没有提示录制成功，请不要担心，您已经录取成功，只是EK Home会偶发一些bug（再解了再解了）**。

![image](https://github.com/user-attachments/assets/2f83b112-23d0-4296-9086-f834a962c97d)

- 自动更新检测
  
开启自动更新检测以后，EK3会自动检测固件更新并推送。即使没有开启该选项，在EK3中也可以在‘系统更新’中手动检测固件更新。

![image](https://github.com/user-attachments/assets/c2565d5f-b555-4c48-91e9-51dcff08d471)

- X-key模式
  
当您开启X-key模式时，指纹模组失效，成为X键。您按压指纹模组时，不会验证您的指纹信息，会直接输出自定义组合按键。此模式为高频自定义宏按键设计，比如您可以将X-Key设置为代码编辑器的编译快捷键，或者设置为电脑锁屏键WIN+L，或者网易云音乐的heart快捷键CTRL+H等。

![image](https://github.com/user-attachments/assets/5dc260ab-b767-4862-aa69-1502b46c8ef7)

- 数据同步方式选择
  
目前，EK3同步天气信息与时间信息有两种方式，一种是有线通信方式，一种是蓝牙通信方式。在有线模式下，EK3通过type-c同步网络信息，无论电脑是否出于锁屏状态都可以正常使用。在蓝牙模式下，EK3通过蓝牙同步网络信息，不需要有线连接，但是在电脑锁屏状态下多媒体控制功能与指纹识别失效。这两种模式都需要保持EK Home在桌面后台运行。

![image](https://github.com/user-attachments/assets/7a64f069-958f-4345-88d0-a930080f264b)

- 一键同步配置
  
配置好以上功能后，点击一键同步配置即可。第一次同步时时间比较久，时间大约30s，后续同步进行差分配置，时间会缩短到3s左右。
注意：如果您选择了有线连接模式，**请在配置同步成功后，在电脑的蓝牙搜索中，选择usename's EK3设备，进行主动连接（只在第一次连接，后续会自动连接）。**

![image](https://github.com/user-attachments/assets/95c6082b-11f4-406b-8143-1fa532350f97)

- 设置界面
  
在设置界面您可以配置EK Home的外观，主题，属性，自动更新检测等。


### 常见问题
**1.初次连接时，EK Home显示连接失败**

   在保持连接的情况下，请您核实电脑是否安装CH340驱动【此处有下载链接】以及设备是否被PC正确识别。window下的判断方法是：在计算属性中--设备管理--端口--是否有CH340设备。Mac下的判断方法是：待补充
   另外，请确保您使用的type-c线是可以进行数据传输的线，而不是仅用来充电的线。识别方法是在type-c口里面，数据线会有多个触点，而仅充电的线只有少数几个触点。

**2. 使用过程中，EK HOME总是连接不上**

   请重启EK Home, 注意点击窗口‘x’并不能退出EK Home，正确退出EK Home的做法是在角标栏目中右击退出即可。

**3. 如何更新EK3固件**

   3.1 请保持EK3与EK Home在连接状态
   
   3.2 请在EK3的目录中，选择“系统更新”

   ![image](https://github.com/user-attachments/assets/be5d337b-a151-4849-92af-d2787d7eb95f)

   3.3 如果有更新，EK3会显示如下界面

   ![image](https://github.com/user-attachments/assets/98fd7f33-d722-4ea6-9071-5421c18bcfd1)


   3.4 点击更新等待固件下载完毕，直到显示界面如下：

   ![image](https://github.com/user-attachments/assets/2f4a2e76-370c-46f3-a9c5-4a99422a4546)


   3.5  等待屏幕熄灭之后，长安开关键5s之后即可放开，等待固件更新完成。**注意，长按5s之后，屏幕仍然是熄灭的，此时EK3已处于固件更新状态中，等待即可。**

