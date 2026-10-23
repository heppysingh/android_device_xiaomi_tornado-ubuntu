# Mainline ARM64 Linux Boot on Tornado

* **OS:** Ubuntu 24.04 LTS
* **Codename:** `tornado`

---

## 📱 Supported Devices
* Redmi 15C 5G
* Redmi 15R 5G
* Redmi 17C 5G
* Poco C85 5G

---

## 📥 Downloads
* **Rootfs Image:** [Download Rootfs](https://drive.usercontent.google.com/download?id=1hnbZf84SKGPVVEy2OE9yWPqtnUFPPA9p&export=download&authuser=0&confirm=t&uuid=2c7bfa3c-3cf6-4b2e-b68c-c703a7c5527a&at=AMRvOn3HMHbRsNkAYOM812s1AJ9At3A1792739004489)

---

## 🛠️ How to Install

1. **Flashing Procedure:**
   ```bash
   fastboot create-logical-partition rootfs_a 2147483648
   fastboot flash rootfs_a rootfs.img
   fastboot flash vendor_boot vendor_boot.img
   fastboot reboot recovery

# Flashing Process
​<img src="https://raw.githubusercontent.com/heppysingh/android_device_xiaomi_tornado-ubuntu/main/assets/flash.jpg" width="600" alt="Flash Process">
# ​Ubuntu Running
​<img src="https://raw.githubusercontent.com/heppysingh/android_device_xiaomi_tornado-ubuntu/main/assets/ubuntu.jpg" width="600" alt="Ubuntu Running">
