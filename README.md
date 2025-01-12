# r2s-openwrt安装教程
## 下载固件
IMMORTALWRT(https://firmware-selector.immortalwrt.org/)

## 配置OPENWRT
### 1.登陆默认192.168.1.1 用户名root 密码无
### 2.关闭IPV6
#### 接口-删除WAN6接口
#### 接口-LAN口-DHCP服务器-IPV6设置-关闭所有IPV6服务
#### 接口-LAN口-高级设置-IPV6分配长度禁用
#### DHCP高级设置 勾选过滤IPV6 AAAA记录
