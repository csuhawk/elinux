# 介绍
多数嵌入式设备使用[flash memory](http://en.wikipedia.org/wiki/Flash_memory)作为存储媒介，而系统大小和启动速度对很多消费电子产品是非常重要的。因此，特别定制的flash文件系统通常拥有很多不同的特性，比如高压缩比，或者直接片上执行代码的能力(XIP)。

# MTD
Note that flash memory may be managed by the Memory Technology Devices (MTD) system of Linux. See the [http://www.linux-mtd.infradead.org/faq/general.html MTD/Flash FAQ] for more information.  Most of the 
filesystems mentioned here are built on top of the MTD system.