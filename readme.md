# 英安特网络报警主机开发技术文档
## Global nt1/3&NTS&AW-BM1600Plus wikit
<br>
<br>
Globalntsrv程序基于Linux平台gcc编译，具有完全的自主知识产权。当需要在其他架构平台的基础上使用，需要采用对应平台的编译器进行编译，可与软件供应商联系。<br>
Globalntsrv程序是INANTER系列网络报警主机的通讯服务程序，做为基础应用服务使用，为第三方平台兼容INANTER系列网络报警主机服务，可以从该服务程序获取到连接到此服务的所有的报警主机的实时事件、状态，并能通过该服务程序对已连接的网络报警主机进行反向控制、从报警主机读取编程项、修改编程项、查询主机状态、校时等等操作。<br>
windows版本采用了原SDK集成了http服务，采用Visual Studio2010开发，使用者只需要将SDK初始化即可采用http协议开发。<br>

详情参见 https://github.com/Antone-wydon/globalntsrv/wiki
