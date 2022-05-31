# WireShark抓包





学习Wireshark的基本操作，抓取和分析有线局域网的数据包；掌握以太网 MAC 帧的基本结构，掌握ARP协议的特点及工作过程。

有线局域网？

局域网 局域网络 字面意思就是比较小的网络

有线局域网 需要网线 

无线局域网 不需要网线 直接用wifi即可

哈哈哈哈哈 图书馆二楼连上网线了 我真是个大聪明

开始做啦

用最广泛的有线局域网

![image-20220529203630706](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529203630706.png)

for /L %i IN (1,1,254) DO ping -w 2 -n 1 172.16.48.%i

获取局域网内所有主机

记录一个本网段的ip

![image-20220529203934852](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529203934852.png)

清空ARP表

arp-d



ping本地网址

![image-20220529204155108](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529204155108.png)



![image-20220529204332174](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529204332174.png)



![image-20220529204351268](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529204351268.png)



![image-20220529204556701](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529204556701.png)





![image-20220529204812541](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220529204812541.png)