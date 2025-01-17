# IPScaner
局域网IP扫描工具 IPScaner.exe是一个局域网内快速搜索IP是否在线的绿色小工具，并集成了多个网络调试工具，包括IP段扫描、端口扫描、windows命令、IP地址计算器、系统端口占用查看工具等。

## 主要功能说明：
1. 主菜单的IP段扫描，支持多网卡切换，快速扫描整个网的网络通讯状态，包括IP、计算机名称、Mac地址，以及常用的网络调试命令（具体请见IP小色块的右键菜单）。
2. 修改本地IP，支持修改单网卡多IP、多网卡IP，保留历史IP修改记录，方便下次快速切换。
3. IP批量扫描，扫描指定IP网段地址的通讯状态
4. IP地址计算器，根据IP地址和子网掩码位，快速计算IP的可用数量、首个可用IP、末个可用IP、网络地址、广播地址、掩码地址
5. 目标端口扫描，支持IP网段地址扫描若干个端口、支持单IP扫描全部端口
6. 本机端口占用查看，快速查看系统中被占用的TCP、UDP端口，快速定位指定端口的进程目录
7. WiFi密码查看，查看曾经连接过的所有WiFi名称和密码，快速复制密码，并支持导出到Excel
8. Windows命令，快速打开windows常用程序，例如网络连接、卸载程序、服务等18个命令，同时支持用户自定义命令，可添加自己常用的程序、文档、命令等。
9. 关于，显示软件版本，更新说明等信息

## 更新说明
### 版本1.23更新说明
1. IP批量扫描，点击列头进行排序

### 版本1.22更新说明
1. IP批量扫描增加列：主机名、MAC

### 版本1.21更新说明
1. 修改本地IP，支持DHCP和静态两种方式。并增加了设置DNS的功能。
2. 备注管理中增加从剪贴板导入功能

### 版本1.20更新说明
1. 修复windows 11(24H2版本)不可查看WIFI密码的问题
2. 修复获取本地IP的MAC地址不显示的问题
3. Ping失败时，尝试侦测特定端口判断设备是否在线
4. 优化TCP端口扫描效率
5. 增加备注信息管理界面，批量扫描IP会显示备注。

### 版本1.19更新说明
1. 小色块右键增加访问共享目录
2. 根据掩码位数，批量扫描IP
3. 根据两个IP地址之间的范围，跨网段批量扫描
4. 界面优化，输入框增加提示信息

### 版本1.18更新说明
1. 系统端口占用查看，双击PID列时，可快速杀死相应的进程。
2. 小色块右键菜单增加浏览http网页
3. 小色块颜色支持自定义设置，有备注的色块文字颜色自定义设置
4. 小色块双击事件支持自定义，便于快速执行某一右键事件
5. 增加划过菜单自动弹出的配置项
6. 主界面增加列表视图展示
   
### 版本1.17更新说明
1. 增加WiFi密码查看器，快速复制密码，并支持导出到Excel
2. 右击IP小色块，增加用户备注功能，用于填写计算机名或使用人等信息
3. 系统端口查看，增加反向筛选条件，过滤不想看的进程名或端口号
4. 优化自定义批量IP扫描的显示结果，并增加导出到excel
5. 状态栏显示【启用主机名查询】的状态
6. 允许用户修改IP小色块字号大小

### 版本1.16更新说明
1. 增加系统端口工具查看器，查看哪些端口被占用了。
2. 优化主程序的菜单栏

### 版本1.15更新说明
1. 增加IP地址计算器功能。
2. 端口扫描增加按IP段扫描多个端口号。

### 版本1.14更新说明
1. IP小色块右键菜单增加快速端口扫描
2. 批量IP扫描界面，增加指定IP段快速生成功能
3. 优化提升批量IP扫描的效率

### 版本1.13更新说明
1. IP小色块右键菜单增加常用命令: 如Ping,Tracert,Telnet,netstat,ARP
2. 优化IP小色块的单双击事件，单击检测网络通讯状态，双击调用命令行窗口ping命令
3. 双击间隔默认为200毫秒，可以在参数配置页面修改值。
4. 调用ping命令，默认请求4次，可以在参数配置页面修改值。

### 版本1.12更新说明
1. 顶部IP扫描段下拉框支持显示单网卡配置的多个IP
2. IP小色块右键菜单优化，增加调用ping命令
3. Windows工具中【我的命令】增加功能说明。
4. 增加【关于】对话框，显示版本更新说明
5. 修复数字键盘不能输入小数点的bug

### 版本1.11更新说明
1. IP段扫描修改为多网卡显示
2. 增加参数配置：是否启用获取主机名（默认不启用）、Ping超时毫秒（默认100毫秒）

### 版本1.10更新内容
1. 点击图标【正常】按钮，可批量复制导出ip、计算机名、Mac地址。
2. 优化254个小色块按钮，使得全部展示在用户面前。

### 版本1.9更新内容
1. 增加windows工具箱，显示系统中常用的工具。
2. windows工具中支持调用自定义的我的命令。

### 版本1.8更新内容
1. 一键修改本地IP界面增加无线网卡。
2. 一键修改本地IP界面增加打开网络连接快捷方式。
3. 增加外部工具箱，快速启动控制面板中常用工具。

### 版本1.7更新内容
1. 修复多网卡显示本地IP错误的问题。

### 版本1.6更新内容：
1. 记录历史修改的IP，点击可快速切换IP。
2. 鼠标悬停在IP小色块上，可显示计算名称。
3. 鼠标悬停在IP小色块上，可显示本网段内的MAC地址值。
4. 鼠标右击IP小色块，在弹出的菜单中可复制各段信息。

### 版本1.5更新内容：
1. 支持修改本地连接的网卡IP地址
2. 增加指定IP的端口扫描工具
3. 增加自定义IP地址批量扫描
4. 过滤ping时长>2秒的IP

### v1.1
1. 调整检测后的颜色值，用绿色表示通讯正常，红色表示通讯失败。
2. IP地址通讯正常时，同时查询主机名称，该查询方法效率较低
3. 鼠标悬停在IP小块上，显示对应的IP地址与主机名称
