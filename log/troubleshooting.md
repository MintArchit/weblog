# issues #F44 #FF4 #4F4

001
error in booting period prolongs it from normaly 5s to ~60s :/
"usb 1-10 device descriptor read/64 error -110"

+ benign notices
+ those are for kernel developers to address
+ systemd-analyze blame

systemd-analyze gives nothing back, which explains 60s

+ add: brand, make, model of the machine and the bios version in use
asus 20?? G751JT?

+ Update BIOS
+ Install a newer kernel (newer Ubuntu release)
+ You should see them in dmesg

articles read
https://askubuntu.com/questions/1422730/lots-of-time-taken-to-boot-my-linux-machine
https://askubuntu.com/questions/1420232/ubuntu-20-04-firmware-bug
https://askubuntu.com/questions/1367947/acpi-error-messages-during-boot
