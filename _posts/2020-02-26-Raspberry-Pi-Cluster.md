---
layout: post
title: Raspberry Pi Cluster
---
Documenting my adventures in playing with raspberry pi cluster.

## References
USB boot from hard drive (fix slowness)
https://www.raspberrypi.org/forums/viewtopic.php?f=28&t=245931
```
sudo nano /boot/cmdline.txt

# Add to very beginning of commands
usb-storage.quirks=152d:0578:u
```


Setting up a RPi Zero to be a USB gadget and share internet with host (windows part doesn't work for me...)
https://www.circuitbasics.com/raspberry-pi-zero-ethernet-gadget/

Setting up a bridge network
https://wiki.debian.org/BridgeNetworkConnections
