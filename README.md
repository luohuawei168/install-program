# n1-install-program
Install to emmc script for phicomm n1, which will help you to copy openwrt system to emmc.  
Execute `n1-install` in terminal to run this program!
 **注意：  
   一键安装到 emmc 脚本( phicomm n1 )已迁移至 openwrt package。使用方法如下，悉知！！**

   **用法**：  
   1、`git clone https://github.com/luohuawei168/install-program`  
   2、执行 `make menuconfig` ，选中 Utilities 下的 install-program
      ``` 
      Utilities  --->  
         <*> install-program
      ```
   3、编译完成之后使用本源码制作镜像写入U盘启动，之后执行 `n1-install` 即可安装到 emmc  
   4、将固件上传到 `/tmp/upgrade`( xxx.img )，之后执行 `n1-update` 即可从该固件升级
