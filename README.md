# Dell_ipmi_fans_controller
一个具有手动调速和线性调速功能的戴尔服务器风扇控制程序(win)
软件参考了：https://github.com/cw1997/dell_fans_controller 
软件调用ipmitool，需要先开启服务器的IPMI。
使用Qt5.14.2编程，调速策略参考了主板风扇的调速方案，并可以调整每个温度控制点。
本软件已在DELL R720服务器中测试，其他服务器型号没有测试，请有戴尔其他型号服务器的使用者请自行测试，如有问题请提交issue。
本软件仅供学习交流免费使用，若您遇到商家使用本软件并进行收费，产生的任何问题及后果与本软件无关。
本软件icon来自iconfinder.com，分享协议为BY-SA 3.0。
