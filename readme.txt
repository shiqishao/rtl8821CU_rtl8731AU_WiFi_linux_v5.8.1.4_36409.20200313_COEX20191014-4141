Support Linux kernel version
kernel 2.6.18 ~ 5.3

CPU support
x86/x64

Ubuntu 19.04
Install make and gcc
1. update apt
>sudo apt update
2. install make
>sudo apt install make
3. install gcc
>sudo apt install gcc

Install and active module:
1. Unzip and change directory
>tar zxvf rtl8821CU_rtl8731AU_WiFi_linux_v5.8.1.4_36409.20200313_COEX20191014-4141.tar.gz
>cd rtl8821CU_rtl8731AU_WiFi_linux_v5.8.1.4_36409.20200313_COEX20191014-4141
2. Compile module
>make 
3. Install module
>sudo make install
4. Unplug adapter and re-plugin adapter to active module
Please note that DWA-171C support auto install driver function in Windwos OS,
user should exit Flash disk mode(default) to active adapter mode.

Uninstall module:
1. Change directory
>cd rtl8821CU_rtl8731AU_WiFi_linux_v5.8.1.4_36409.20200313_COEX20191014-4141
2. Uninstall module
>sudo make uninstall
3. Clean object code
>make clean