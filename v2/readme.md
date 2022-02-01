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
![Schematic_OttoESP32_2022-02-01 (3)](https://user-images.githubusercontent.com/400875/151976830-792d0c72-bdc5-4b23-a20d-7435e164ed29.png)



**Use cases**
- 8x servo for a walking OttoDIY/Ninja [Robo8080 documents](https://togetter.com/li/1374900) 
- Optional Rosmo ESC for [Rosmo.io](https://rosmo.io)
- Optional [HCS404](https://github.com/rosmo-robot/Rosmo_3D/issues/6) with staggered pins
- Optional [M5 Mbus](https://forum.m5stack.com/topic/360/m5stack-fire-pinout-leaflet)
- Optional [ staggered 7pin display 1.54"](http://www.lcdwiki.com/1.54inch_IPS_Module)
- Optional 5pin [Breakout garden header](https://shop.pimoroni.com/collections/breakout-garden)
- Optional [3v Stemma](https://www.tomshardware.com/features/stemma-vs-qwiic-vs-grove-connectors) Supports [Qwiic](https://www.reddit.com/r/electronics/comments/8lhxwg/sparkfuns_qwiic_standard_for_modular_i2c_devices/), [Grove (I2C)](https://thepihut.com/products/qwiic-cable-grove-adapter-100mm) ,[Gravity](https://learn.adafruit.com/introducing-adafruit-stemma-qt/dfrobot-gravity)
- Optional [M5 LAN base](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Bases/lan_base.pdf) GPIO 34,23,19,18,26

Older pictures

<img width="489" alt="side" src="https://user-images.githubusercontent.com/400875/151074421-d22a6a05-58cb-4bdc-bd93-8d7e2470e1fe.png">


<img width="184" alt="otto5" src="https://user-images.githubusercontent.com/400875/150679018-b0bb5ad0-db5d-4c06-ad89-1fea6cc3b11b.png">

