# OpenCore Bootloader for Hackintosh on Clevo NH5x/NH70 series
+ 支持 Clevo NH5xRD_RC_RA_RH(Q)/NH70RD_RC_RA_RH(Q) 系列的所有机器。
+ **启动之后一定要更换三码！**
+ **安装之前需要先刷入蓝天原厂 BIOS，并手动禁用 SGX、Fastboot、VT-d、Platform Trust、CFG Lock。**
    - SGX Fast Boot VT-d: Advanced -> Advanced Chipset Control
    - Platform Trust: Advanced -> Chipset Configuration
    - CFG Lock: Advanced -> Power & Performance -> CPU - Power Management Control -> CPU Lock Configuration
+ Big Sur 上可以用此命令开启 hidpi `bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/dev/hidpi.sh)"`。
-----------------------------------------
感谢：[@Dortania](https://github.com/dortania) [@daliansky](https://github.com/daliansky) [@takoyakiwhite](https://github.com/takoyakiwhite)
