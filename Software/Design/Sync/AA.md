

Software

	1. Linux system with 64bit
	2. Yocto setup
		a. Host setup
		b. Build setup
			i. Yocto vanilla
			ii. Build dependency
			iii. Documentation
		c. Build image
			i. Uboot
			ii. Linux
			iii. FS
		d. Test image
			i. NFS boot 
			ii. SD card boot


Hardware:

Consideration factors

	1. ARM Cortex 64 bit
	2. Storage (Emmc or Nand, Size 4G or more)
	3. Memory (DDR3 , size 1GB +)
	4. UART (minimum 6)
	5. More GPIO
	6. Year of support 5 to 10 years
	7. Kernel, Uboot available with Spec
	8. Power supply (Module type device no need to consider it)

Repo:

	1. Repo place = github
	2. Repo name = Lyvt
	3. Release plan
		a. Yearly release 
		b. Intermediate release
	4. Repo structure
		a. Hardware
			i. Datasheets
			ii. Schematics
			iii. Rework
			iv. errata
		b. Software
			i. Yocto
			ii. Design
			iii. Release
				1) Software
				2) Binary
