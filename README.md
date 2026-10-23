# Mainline arm64 Linux boot on tornado 


Ubuntu LTS 24.04   
codename: tornado   
Devices:-   
Redmi 15C 5g    
Redmi 15R 5g   
Redmi 17C 5g
Poco C85 5g    

Rootfs Download: https://drive.usercontent.google.com/download?id=1hnbZf84SKGPVVEy2OE9yWPqtnUFPPA9p&export=download&authuser=0&confirm=t&uuid=2c7bfa3c-3cf6-4b2e-b68c-c703a7e5527a&at=AMrWOn3mHBrSmKaV0m812s1AJ9At%3A1792739004489

# How to install:- 
![image-name](https://github.com/heppysingh/android_device_xiaomi_tornado_ubuntu/assets/flash.jpg)

```
fastboot create-logical-partition rootfs_a 2147483648
fastboot flash rootfs_a rootfs.img
fastboot flash vendor_boot vendor_boot.img
fastboot reboot recovery 

```
# Screenshot 
![image-name](https://github.com/heppysingh/android_device_xiaomi_tornado_ubuntu/assets/ubuntu.jpg)


