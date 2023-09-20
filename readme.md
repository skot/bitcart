## The Bitcart
The bitcart is an open source control board for Bitmain Antminers. It runs off a RPi CM4 and the design is based around the [Raspberry Pi Compute Module 4 IO Board](https://www.raspberrypi.com/products/compute-module-4-io-board/)

**design is currently in alpha stage and untested!**

### Goals
- Initial compatibility with Antminer S19J and S19XP series miners.
- Fully open source hardware and firmware
- Runs the open source [esp-miner](http://github.com/skot/esp-miner) ported to linux.
- IO options for customization
  - Ethernet
  - WiFi
  - Bluetooth
  - USB2
  - PCIe
  - RPi 40-pin header
- Built-in options for hashboard testing and repair
