
# LQEmulator

LQEmulator is easy to use linux rootfs/initrd pack tool with this tool you will be able to pack for example initrd.img (cpio) initrd.gz (cpio in gzip)

With LQEmulator you also can run this pack on x86_64 or arm depend of you files.

# Example

- pack + run (emulator -rp /home/user/target -i initrd/)
- packing without run it (emulator -rp /home/user/target -i initrd/ -co)
- run it without packing (emulator -rp /home/user/target -i initrd/ -noc )
- to clear old data (emulator -rp /home/user/target -c )
- run help (emulator -h)
## Depends
All Depends are auto instaling if some one is missing.
 - [QEMU](https://www.qemu.org)
 - [GUNZIP](#)
 - [CPIO](#)

