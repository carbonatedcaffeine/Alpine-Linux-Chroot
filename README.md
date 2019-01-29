# Alpine-Linux-Chroot
Chrooting Alpine Linux Is Fun! Also Featured In UserLAnd: [Check It Out!](https://github.com/CypherpunkArmory/UserLAnd-Assets-Alpine)

And Don't Wrorry I Added Alpine To UserLAnd so I Have Some Rights

### Other Importent Stuff
: [Wiki](https://github.com/EnderNightLord-ChromeBook/Alpine-Linux-Chroot/wiki)

### Prebuilts
to use prebuilts you must clone the repo

to put the prebuit tar.gz's back together:

`cd Alpine-Linux-Chroot/(arch)`

`sudo cat rootfs.tar.gz.part00 rootfs.tar.gz.part01 rootfs.tar.gz.part02 >rootfs.tar.gz`

extract the archive

and then you can chroot into it

`sudo chroot $CHROOT /bin/sh -l`

### How To Build Source For Yourself
alpine-chroot is like the buildArch script. but for any pc.

first you will need to download Alpine-Chroot.sh

`wget https://github.com/EnderNightLord-ChromeBook/Alpine-Linux-Chroot/blob/master/Alpine-Chroot.sh`

`sudo sh Alpine-Chroot.sh (arch: x86_64 x86 aarch64 or armhf)`

`sudo chroot $CHROOT /bin/sh -l`
