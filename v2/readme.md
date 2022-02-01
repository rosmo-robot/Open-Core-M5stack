<img width="447" alt="v2" src="https://user-images.githubusercontent.com/400875/151975925-141f34f4-bfb3-49a4-a934-d17ff00b97d6.png">
<img width="373" alt="V2b" src="https://user-images.githubusercontent.com/400875/151975964-5604d894-c7a4-4253-8fb4-9250efad506d.png">

[Schematic in 2nd tab](https://easyeda.com/editor#id=|cf28dd6a985d4901b4a220c4195efb63|8899d40f4e734017b47c859c78fa6371) BOM can be exported from here

**Open Core ESP32 Dev board**

CERN-P licenced ESP32 board  in 5cm x 5cm [M5stack dimensions](https://shop.m5stack.com/collections/stack-series).

Summary: Design a small, self-contained ESP32 dev board capable of interfacing with other boards or components over I2C using the M5Mbus, Stemma or Breakout garden pins.

Dimensions: 50mm x 50mm

Power supply: 5v 

Current max: 2A

Main BOM components: ESP32 module, AZ1117C-3.3, TPS62177DQCR, USBC socket, TXS0108E Or similar 5V signal voltage translation/a level shifter for the servos signal

Form factor: Square with 1/4 cut-out bolt holes

Power connectors: JST-PH 2pin

The [pin mappings are here](https://docs.google.com/spreadsheets/d/18HBvosVtXnOy4TjSlgeaK6NfCzJlY6rAayFWI3vbToo/htmlview)

Programming will be via USB.

Control will be via Wifi

Board: 2 layers generic, according to JLCPCB.

In progress [schematic](https://easyeda.com/editor#id=|cf28dd6a985d4901b4a220c4195efb63|8899d40f4e734017b47c859c78fa6371)
![Schematic_OttoESP32_2022-02-01 (5)](https://user-images.githubusercontent.com/400875/152006990-6e690cb6-8825-4a09-a319-a157a48f4662.png)


**Use cases**
- 8x servo for a walking OttoDIY/Ninja [Robo8080 documents](https://togetter.com/li/1374900) 
- Optional Rosmo ESC for [Rosmo.io](https://rosmo.io)
- Optional [staggered 8pin display 1.54" or 2"](http://www.lcdwiki.com/1.54inch_IPS_Module)
- Optional [HCS404](https://github.com/rosmo-robot/Rosmo_3D/issues/6) with staggered pins
- Optional [M5 Mbus](https://forum.m5stack.com/topic/360/m5stack-fire-pinout-leaflet)
- Optional 5pin [Breakout garden header](https://shop.pimoroni.com/collections/breakout-garden) For [3Dof](https://shop.pimoroni.com/products/msa301-3dof-motion-sensor-breakout), [6dOf](https://shop.pimoroni.com/products/lsm303d-6dof-motion-sensor-breakout), [9DoF](https://shop.pimoroni.com/products/icm20948),  [toF](https://shop.pimoroni.com/products/vl53l1x-breakout), [More](https://shop.pimoroni.com/?q=breakout+garden)
- Optional [3v Stemma](https://www.tomshardware.com/features/stemma-vs-qwiic-vs-grove-connectors) Supports [Qwiic](https://www.reddit.com/r/electronics/comments/8lhxwg/sparkfuns_qwiic_standard_for_modular_i2c_devices/), [Grove (I2C)](https://thepihut.com/products/qwiic-cable-grove-adapter-100mm) ,[Gravity](https://learn.adafruit.com/introducing-adafruit-stemma-qt/dfrobot-gravity)
- Optional [M5 x4 motor](https://docs.m5stack.com/en/module/lego_plus) GPIO 16, 21, 36, 26, 17, 22, 13 With no confict with servo's
- Optional [Open DC motor](https://github.com/tomorrow56/M5Stack_Motor_Driver/blob/master/M5_Moter_v02_schematics.pdf) GPIO 16, 2, 12, 15, 13, 0
- Optional [M5 LAN base](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Bases/lan_base.pdf) GPIO 34,23,19,18,26
- Optional [M5 868, 433 LoRa](https://docs.m5stack.com/en/module/lora868) GPIO 23,19,18, 36, 26, 05
- Optional [M5 commu](https://docs.m5stack.com/en/module/commu) GPIO 23,19,18, 03, 16, 21, 12, 15, 01, 17, 22
- Optional [M5 GPS](https://docs.m5stack.com/en/module/gps) GPIO 03, 16, 35, 36, 01, 17, 05, 13, 34


Older pictures

<img width="489" alt="side" src="https://user-images.githubusercontent.com/400875/151074421-d22a6a05-58cb-4bdc-bd93-8d7e2470e1fe.png">


<img width="184" alt="otto5" src="https://user-images.githubusercontent.com/400875/150679018-b0bb5ad0-db5d-4c06-ad89-1fea6cc3b11b.png">

