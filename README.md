# gx2sploit - a Wii U kernel exploit
A Wii U kernel exploit created by libwiiu.  
Currently this repo only works on FW 5.5, adjust the defines in the headers to supports other FWs

# Usage
Call `run_kexploit` with a valid `coreinit_handle`, aftwards you can use the kernel_read,kernel_write and KernelCopyData functions defined in `kexploit.h`  

**Make sure to have GX2 running before using the exploits, the exploit also needs to be called from the main GX2 core.**

# Credits
 - [original sources](https://github.com/wiiudev/libwiiu/tree/master/kernel/gx2sploit)
 - Marionumber1
 - TheKit
 - Hykem
 - comex
 - Chadderz
 - Relys
 - NWPlayer123
 - Mathew_Wi
 - Kinnay: for the KernelCopyData function

