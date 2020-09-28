# AutoBuild-Actions
Actions for Building OpenWRT

Supported Devices: `d-team_newifi-d2`

## Fork说明

因为 [Hyy2001](https://github.com/Hyy2001X) 老哥改动了一些编译选项  
（去掉了多拨和负载均衡 更新openclash等  
而自己又非常需要多拨和负载均衡的支持  
同时为了节省空间 有效利用新三32MB的存储  
我fork了本项目 开始自己的折腾固件之路

## 固件说明

下面是我保留的软件：  
python3-requests及其所有依赖（校园网模拟登陆用）  
mwan3 负载均衡 多拨使用  
ssr mwan3分流助手 搭梯子用  
samba 自动挂载 文件共享备用  
ttyd 网页终端管理  
AdguardHome 广告过滤与隐私保护  
kms 本地激活服务  
zerotier 大内网计划  
socat 网络工具  

如果你的需求跟我一样，也可以直接下载我的release刷  
如果想自己定制固件 欢迎继续fork 一起折腾

## 使用方法

使用方法参考 CurssedCoffin老哥 的 [AutoBuild-Actions](https://github.com/CurssedCoffin/AutoBuild-Actions)
