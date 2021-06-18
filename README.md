#Kali Nethunter

###Installation:

######1) install magisk module
    https://github.com/zaharchenko-test/kali-nethunter/releases/download/2021/magisk-nethunter.zip
    and restart your phone
######2) install rootfs
    mkdir -p /data/local/nhsystem
    busybox tar -xf /sdcard/nethunter-arm64-2021.tar.xz -C /data/local/nhsystem
######3) boot and test
    /system/xbin/kali
    neofetch && uname -a
