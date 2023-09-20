## The Bitcart
The bitcart is an open source controlboard for Bitmain Antminers. It runs off a RPi CM4 and the design is based around the [Raspberry Pi Compute Module 4 IO Board](https://www.raspberrypi.com/products/compute-module-4-io-board/)

If you are trying run a Bitcoin ASIC miner somewhere besides a datacenter, this is the controlboard for you.

**design is currently in alpha stage and untested!**

### Goals
- Initial support for Antminer S19J and S19XP series miners.
  - eventual support for S19, S17 and S9 legacy miners. 
- Fully open source hardware and firmware
- Runs the open source [esp-miner](http://github.com/skot/esp-miner) ported to linux.
  - miner FW modularized to allow for easy modification. Better utilize stranded energy! 
- IO options for customization
  - Ethernet
  - WiFi
  - Bluetooth
  - USB2
  - PCIe
  - RPi 40-pin header
- Built-in options for hashboard testing and repair
