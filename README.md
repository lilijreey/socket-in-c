### Tcp Udp Socket In C leanning notes

###关于要构造自己的一个应用层协议，需要确定的几个基本问题。
1.  应用层协议的构架，是C/S是P2P
2.  数据包成帧的边界问题：是基于哨兵位的定位。还是基于数据包长度的地定位。
3.  识别一个有效请求的实现问题。
4.  输送信息的编码问题，是字符编码还是二进制编码
