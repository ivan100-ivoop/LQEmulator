
# LQEmulator

LQEmulator is easy to use linux rootfs/initrd pack tool with this tool you will be able to pack for example initrd.img (cpio) initrd.gz (cpio in gzip)

With LQEmulator you also can run this pack on x86_64 or arm depend of you files.

# Example
- pack + run (emulator -p /home/user/target -i initrd/)
- packing without run it (emulator -p /home/user/target -rp initrd/ -co)
- run it without packing (emulator -p /home/user/target -rp initrd/ -noc )
- to clear old data (emulator -p /home/user/target -c )
- run help (emulator -h)
- To dissmis using ever time -p <path> you can ony cd <path> also by default this folder from geting files is rootfs/ to change it i use -rp <folder> or --root <folder> 
## Depends
All Depends are auto instaling if some one is missing.
 - [QEMU](https://www.qemu.org)
 - [GUNZIP](#)
 - [CPIO](#)

## Installing
` wget -qO- https://raw.githubusercontent.com/ivan100-ivoop/LQEmulator/main/installer | bash`

## Help commands
`Usage: emulator [option] [arguments]`

- `--ram, -r  <size> Ram Size for Emulation.`
- `--machine, -m <machine> Qumu Type of machine to use Emulator.`
- `--size, -s <size> Emulation HDD Image Size (is a dinamic).`
- `--kernel, -ke <kernel name> Kernel Name/path default is on <PWD> with name bzImage.`
- `--initrd, -i <initrd name> name of rootfs/initrd filename to use Emulator default is core.gz.`
- `--path, -p <target> Target Directory path defult is getting from <PWD>.`
- `--root, -rp <path> Path to this rootfs/initrd file system folder.`
- `--version, -v Emulator Current Version and some info.`
- `--kill, -k Killing Emulator.`
- `--autokill, -ak <time> Set time to auto kill Emulator (NOT READY).`
- `--nocompile,-nc Bypass Compilation proccess and Emulate old build.`
- `--compile, -co Bypassing Emulator and only compiling rootfs/initrd file.`
- `--clear, -c Cleaning old build(s) or HDD Images.`
- `--reset, -rs Restaring console only active on end Emulator not valid for only compile or clear!.`
- `--set, -se <qemu-arm-static> With this you can change Startup Arch for default is qemu-system-x86_64.(NOT READY)`
- `--install-packages, -inp Checking for missing packages like. wget,cpio,qemu,gzip and etc!.`
- `--mupdate, -mu Manual Updating downloading and installing direct.`
- `--help, -h Emulator Help Commands.`
