linux-3.14.12
=============

1 make mini210_defconfig
2 make zImage
3 ./mkimage -A arm -O linux -T kernel -C none -a 20008000 -e 20008040 -n linux-3.14.12 -d arch/arm/boot/zImage uImage