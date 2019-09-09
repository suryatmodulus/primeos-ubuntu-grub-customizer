# Primeos-Ubuntu-Grub-Customizer

# steps:

1] Create a new entry in grub customizer with type ==> linux and choose your PrimeOS partition
2] Change Intial ramdisk to ==> /android/initrd.img
3] Change Linux Image to ==> /android/kernel
4] Add the following text to Kernel params ==> quiet androidboot.selinux=permissive buildvariant=userdebug SRC=/android
5] Click OK and Save the configuration

