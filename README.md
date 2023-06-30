
# LQEmulator

LQEmulator is easy to use linux rootfs/initrd pack tool with this tool you will be able to pack for example initrd.img (cpio) initrd.gz (cpio in gzip)

With LQEmulator you also can run this pack on x86_64 or arm depend of you files.

# Example

- pack + run (emulator -p /home/user/target -i initrd/)
- packing without run it (emulator -p /home/user/target -rp initrd/ -co)
- run it without packing (emulator -p /home/user/target -rp initrd/ -noc )
- to clear old data (emulator -p /home/user/target -c )
- run help (emulator -h)

  to dissmis use evertime -p <path> you can ony cd <path> also by default this folder from geting files is rootfs/ to change it i use -rp <folder> or --root <folder> 
## Depends
All Depends are auto instaling if some one is missing.
 - [QEMU](https://www.qemu.org)
 - [GUNZIP](#)
 - [CPIO](#)

