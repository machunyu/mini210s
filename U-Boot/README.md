u-boot-2012.10
==============
1. [root@u-boot-2012.10]#make mini210_config
2. [root@u-boot-2012.10]#make
3. [root@u-boot-2012.10]#cat /proc/partitions
4. [root@u-boot-2012.10]#dd iflag=dsync oflag=dsync if=spl/mini210-spl.bin of=/dev/sdb seek=1
5. [root@u-boot-2012.10]#dd iflag=dsync oflag=dsync if=u-boot.bin of=/dev/sdb seek=49
