# 其他说明：
#
- 支持ipv6：1、Global build settings ---> Enable IPv6 support in packages (NEW)（选上）
-             2、Extra packages ---> ipv6helper（选上）
-             3、安装好固件后在-网络-DHCP/DNS里的高级设置-把“禁止解析 IPv6 DNS 记录”的“√”去掉
#
- 不要ipv6：Global build settings ---> Enable IPv6 support in packages (NEW)（不选），就好了
#
- 网络共享luci-app-samba默认是去不掉的，在：Extra packages ---> autosamba（不选），就可以不选luci-app-samba
#
- 编译成功跟失败都邮件通知--右上角头像-->Settings-->Notifications的差不多最下面找到《Send notifications for failed workflows only》把前面的勾去掉就好了
