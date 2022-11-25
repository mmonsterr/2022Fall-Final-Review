### ipv6部分
静态配置和ripng配置

# 9 
安全管理包括


网络故障维护流程图

## 综合实验
int e0/0.1      .指的是子接口
 ip add 10.1.2.1 26  
 vlan-tpe dot1q vlan 1 制定子接口的类型为dot1q绑定到vlan1上  

 int s1/0  
 ip add 10.1.0.17 30  
 dis ip ro  
 
 先配置直连路由 看本地通不通  

 version 2  
 undo summary

 R1
 rip  
 network 10.0.0.0  
version 2  
undo summary  
R5  
import-route ospf  
ospf
area 1  
network 10.1.0.4 0.0.0.3  
network 10.1.0.12 0.0.0.3  
