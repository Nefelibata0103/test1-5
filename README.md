+ 安装过程与一些问题
  + 安装软件

  + 安装SDK

  + 安装device

    + 出现的问题：

      1. 安装镜像的时候会报无法安装

         解决方案：卸载原来的intel x86，然后再进行安装，但是还会报错，接着打开Windows虚拟平台，成功解决

         <img src="./img/image-20230413212546314.png" alt="image-20230413212546314" style="zoom:33%;" />



      2. 解决 Could not resolve com.android.tools.build:gradle:7.4.2

         原因：jdk版本为8可能太低了。

         <img src="./img/image-20230413211937634.png" alt="image-20230413211937634" style="zoom:33%;" />

      <img src="./img/image-20230413212026188.png" alt="image-20230413212026188" style="zoom:33%;" />

      将jdk版本改到11

      <img src="./img/image-20230413212154685.png" alt="image-20230413212154685" style="zoom:33%;" />






+ 安装后运行截图

<img src="./img/image-20230409205621510.png" alt="image-20230409205621510" style="zoom:33%;" />
