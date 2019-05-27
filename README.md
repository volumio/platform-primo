# platform-primo  

**Volumio platform files for Volumio Primo Boards**

Kernel Sources  
http://github.com/TinkerBoard/debian_kernel
(branch "develop", currently maintained by Asus, we only support)

Tinkerboard: https://volumio.github.io/docs/, chapter "Porting_Guide"/ "Get_The_Kernel_Source"  

This repo contains all files, used by the Volumio Builder to create a **Volumio Primo** image  

- kernel files (kernel, modules, firmware)  
- u-boot  
- other files. e.g. kernel configuration etc.  

**Changelog**


2019.05.21 Separated Primo from Tinkerboard, using Asus kernel 4.4.132 with a fix for the es90x8q2m frequency issue  

2019.05.27 Change configuration: usb audio as a module

