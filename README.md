# 此仓库用于保存Orange Pi开发板的Raspberry Pi OS镜像

## 下载Raspberry Pi OS镜像

开发板 | 镜像类型 | 下载 |
|:--|:--|:--|
| opizero3 1gb和2gb|桌面版 |[下载链接](https://github.com/leeboby/raspberry-pi-os-images/releases/download/opizero3/opizero3-raspios-bullseye-arm64-2023-07-16.tar.gz) |
|opi3b|服务器版|[下载链接](https://github.com/leeboby/raspberry-pi-os-images/releases/download/opi3b/Orangepi3b_1.0.0_raspios_bullseye_server_linux5.10.160.7z)|
|opi3b|桌面版|[下载链接](https://github.com/leeboby/raspberry-pi-os-images/releases/download/opi3b/Orangepi3b_1.0.0_raspios_bullseye_desktop_lxde_linux5.10.160.7z)|

## OPi Zero3 1.5gb和4g内存版本的开发板使用说明

- 1.5gb内存的开发板需要更新下u-boot才能正常使用
- 4gb内存的开发板需要更新下u-boot和内核的dtb文件才能正常使用

更新方法请参考：[更新opizero3 u-boot和dtb的方法](https://github.com/leeboby/opizero3-uboot-dtb) 

## opi3b使用说明
- opi3b镜像第一次启动需要接HDMI显示器，然后通过用户向导来设置账号和密码
- opi3b镜像默认没有打开ssh登录，可以在raspi-config中打开
- opi3b镜像默认不会自动扩容rootfs，可以在raspi-config中运行扩容功能

## opizero3登录账号和密码
opizero3镜像默认登录账号和密码都是：opi

---
![Raspberry Pi OS桌面壁纸](https://github.com/leeboby/raspberry-pi-os-images/blob/main/pictures/desktop.png)
