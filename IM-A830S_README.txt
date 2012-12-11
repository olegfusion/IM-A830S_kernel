1. How to build Kernel source of IM-A830S
	a.	Firstly Get Toolchain from android git server and etc ¡¦
        GCC correct version is arm-eabi-4.4.0
		
	b.	modify Makefile
		edit "CROSS_COMPILE" to toolchain path ( You downloaded )
		ex) CROSS_COMPILE=$(You Download directory)/android/prebuilt/linux-x86/toolchain/arm-eabi-4.4.0/bin/arm-eabi-
	c.	make CONFIG_DEBUG_SECTION_MISMATCH=y ARCH=arm arm msm8960_ef47s_tp30_defconfig
	
	d.	make CONFIG_DEBUG_SECTION_MISMATCH=y ARCH=arm
	
2.	Kernel Image Location is arch/arm/boot/zImage
	Module Image Location is drivers/*/*.ko
	
3.	How to Clean Kernel object files
	a.	make ARCH=arm clean

