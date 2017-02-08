This Page is dedicated to LineageOS on the Gigaset QV1030 aka. Quanta FG6Q. 
There wont't be daily buils. 

```c
#include <std_disclaimer.h>

/*
 * Your warranty is now void.
 *
 * We are not responsible for bricked devices, dead SD cards,
 * thermonuclear war, or you getting fired because the alarm app failed. Please
 * do some research if you have any concerns about features included in this ROM
 * before flashing it! YOU are choosing to make these modifications, and if
 * you point the finger at us for messing up your device, we will laugh at you.
 *
 */
```

### What is working?
* Graphics (OpenGL)
* Sensors
* GPS
* Wlan
* Access to internal and external SD (sdcard0&sdcard1)
* USB (MTP,ADB,HOST,Input Devcies)
* Audio
* Vibrator/Vibrations

### What is PARTIAL working?
* Bluetooth, some features work (file transfer for exp.), some don´t (audio is faulty for exp.)

### Bugs
* CM 13.1: Occasionally reboots due to old sensorblobs

[Device tree](https://github.com/fg6q/android_device_quanta_fg6q) // 
[Kernel](https://github.com/fg6q/android_kernel_quanta_fg6q) // 
[Vendor binaries](https://github.com/fg6q/android_vendor_quanta_fg6q)