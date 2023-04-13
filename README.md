# go-ping
go实现简单ping


思路总结
小例子涉及到的知识点
ICMP报文格式以及ICMP和IP的关联
ICMP校验和算法-有点不知道其所以然
flag包基础用法
探测的主力依旧是net.DialTimeout--跟之前的TCP扫描工具相同
涉及到bytes.Buffer的用法
https://cloud.tencent.com/developer/article/1456243
buffer这里主要涉及：声明一个buffer 从buffer中读数据 往buffer中写数据 及其他操作 详见上文链接
我猜应该是为了提高文件读写效率而创建的buffer包 具体例子以后留心

