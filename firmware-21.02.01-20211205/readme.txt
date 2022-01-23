MLO:
U-Boot SPL 2018.11 (Dec 05 2021 - 18:01:57 +0800)

u-boot.img:
U-Boot 2018.11 (Dec 05 2021 - 18:01:57 +0800)
=> mtdparts

device nand0 <omap2-nand.0>, # parts = 8
 #: name                size            offset          mask_flags
 0: nand.spl            0x00020000      0x00000000      0
 1: nand.spl_backup1    0x00020000      0x00020000      0
 2: nand.u-boot         0x00100000      0x00040000      0
 3: nand.u-boot-env     0x00020000      0x00140000      0
 4: nand.u-boot-env.backup10x00020000   0x00160000      0
 5: nand.dtb            0x00020000      0x00180000      0
 6: nand.kernel         0x00c00000      0x001a0000      0
 7: nand.rootfs         0x0f260000      0x00da0000      0

active partition: nand0,0 - (nand.spl) 0x00020000 @ 0x00000000



am335x-antminer.dtb:

zImage:
openwrt-imagebuilder-21.02.1-omap.Linux-x86_64//build_dir/target-arm_cortex-a8+vfpv3_musl_eabi/linux-omap/zImage
openwrt-21.02.1-omap-rootfs.img:
openwrt-21.02.1-omap-rootfs.tar.gz -> mkfs.ubifs -F -q -r rootfs -m 2048 -e 126KiB -c 2047 -o openwrt-21.02.1-omap-rootfs.img

