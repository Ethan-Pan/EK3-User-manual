## EK3用户手册
这里是EK3用户操作手册，包含EK3使用方法，应用程序使用方法，以及使用过程中的注意事项。

### 欢迎使用EK3
EK3是一个桌面级多媒体控制器项目，在具有科技感外观的同时，可以满足桌面级多媒体控制需求，拥有指纹解锁，音量控制，音乐控制，自定义宏按键等多种控制功能。EK3配备了1.28寸240*240分辨率的触摸显示屏，可以显示时间，日期，天气等信息，同时也具备了定时器，番茄时钟等高频使用工具。

### 初次使用
初次使用需要下载**EK Home**进行配置，**EK Home**是专门为EK3设计开发的桌面应用程序，可以对EK3进行高度自定义配置，目前已支持windows系统和macOS，Linux适配正在开发中，对应版本的下载地址：
EKHome-application-windows
EKHome-application-macOS

### EK Home使用方法
- 连接设备
 
配置EK3时，需要将设备与电脑通过Type-c进行连接，然后点击EK Home中的“连接”按钮。连接成功之后，“连接”按钮会变为“已连接”且不可选中。首次配置EK3时需要点击“连接”按钮，后续使用EK Home将会自动连接。
【此处加上对应EK Home的截图】
- 用户名设置

请输入您的用户名，用户名会显示在EK3的目录页面与蓝牙名称中，目前仅支持英文与数字输入。
【此处加上对应EK Home的截图】
- 地区设置

请选择您所在的地区，EK3所显示的天气信息会根据您选择的地区来进行推送与同步。目前仅支持广东省的几个主流城市，后续更多的城市将陆续上线。
【此处加上对应EK Home的截图】
- 电量显示
  
EK3表盘中的绿色能量条为电量条，低于20%会变为红色。选中电量显示会将目前电池电量的百分比显示在表盘中。
【此处加上对应EK Home的截图】
- LED颜色设置
  
EK3侧边配备了LED灯条，可以显示多种模式效果。您可以在EK3上来进行选择，此处的设置用来选择LED的底色，只对常量模式与呼吸模式有效。
【此处加上对应EK Home的截图】
- 睡眠区间设置
  
为了节省电量与保护屏幕，EK3在睡眠区间会停止工作。请您选择合适的睡眠区间，如果没有选择，默认的睡眠区间为23:00-09:30。如果您想在睡眠区间唤醒EK3，请短按EK3的开机键。
【此处加上对应EK Home的截图】
- 深度省电模式
  
开启深度省电模式会关闭EK3的常量显示，屏幕亮屏10s后会自动熄屏，熄屏状态下不影响指纹、旋钮等功能的使用，触摸屏幕会再次点亮。
【此处加上对应EK Home的截图】
- 指纹密码
  
请您输入指纹认证成功后所要输入的密码，该功能为电脑解锁设计。因EK3无法获得windows与Mac OS底层权限，无法接入windows hello与Mac指纹识别，所以EK3通过模拟外置键盘向电脑发送开机密码来完成电脑解锁。使用指纹解锁时，需要将电脑调整为输入密码的页面即可。
【此处加上对应EK Home的截图】
【此处加电脑解锁界面的截图】
- 添加指纹
  
点击‘+’号即可开始录制指纹信息，请您在EK3指纹模组开启蓝光时，按压手指4-6次，直到蓝光熄灭，EK Home提示录制成功之后，命名您的指纹信息，完成指纹录制。
【此处加上对应EK Home的截图】
- 自动更新检测
  
开启自动更新检测以后，EK3会自动检测固件更新并推送。即使没有开启该选项，在EK3中也可以在‘系统更新’中手动检测固件更新。
【此处加上对应EK Home的截图】
- X-key模式
  
当您开启X-key模式时，指纹模组失效，成为X键。您按压指纹模组时，不会验证您的指纹信息，会直接输出自定义组合按键。此模式为高频自定义宏按键设计，比如您可以将X-Key设置为代码编辑器的编译快捷键，或者设置为电脑锁屏键WIN+L，或者网易云音乐的heart快捷键CTRL+H等。
【此处加上对应EK Home的截图】
- 数据同步方式选择
  
目前，EK3同步天气信息与时间信息有两种方式，一种是有线通信方式，一种是蓝牙通信方式。在有线模式下，EK3通过type-c同步网络信息，无论电脑是否出于锁屏状态都可以正常使用。在蓝牙模式下，EK3通过蓝牙同步网络信息，不需要有线连接，但是在电脑锁屏状态下多媒体控制功能与指纹识别失效。这两种模式都需要保持EK Home在桌面后台运行。
【此处加上对应EK Home的截图】
- 一键同步配置
  
配置好以上功能后，点击一键同步配置即可。第一次同步时时间比较久，时间大约30s，后续同步进行差分配置，时间会缩短到3s左右。
注意：如果您选择了有线连接模式，请在配置同步成功后，在电脑的蓝牙搜索中，选择usename's EK3设备，进行主动连接（只在第一次连接，后续会自动连接）。
【此处加上对应EK Home的截图】
- 设置界面
  
在设置界面您可以配置EK Home的外观，主题，属性，自动更新检测等。

### 常见问题
1.初次连接时，EK Home显示连接失败。
   在保持连接的情况下，请您核实电脑是否安装CH340驱动【此处有下载链接】以及设备是否被PC正确识别。window下的判断方法是：在计算属性中--设备管理--端口--是否有CH340设备。Mac下的判断方法是：待补充
   另外，请确保您使用的type-c线是可以进行数据传输的线，而不是仅用来充电的线。识别方法是在type-c口里面，数据线会有多个触点，而仅充电的线只有少数几个触点。
【此处加上对应两种接口的截图】

