<img width="370" alt="opencoreesp32" src="https://user-images.githubusercontent.com/400875/151476227-865af0c9-5c3e-4b6e-902d-47326b499fff.png">
<img width="351" alt="opencore" src="https://user-images.githubusercontent.com/400875/151476250-7e076ac4-c0a4-49d5-80a2-1c5199740953.png">

Open Core ESP32 Dev board

CERN licenced [ESP32 board](https://easyeda.com/editor#id=0c94645e6c4e443cb9d172e18162d7fa|cf28dd6a985d4901b4a220c4195efb63) in 5cm x 5cm [M5stack dimensions](https://shop.m5stack.com/collections/stack-series).

Summary: Design a small, self-contained ESP32 dev board capable of interfacing with other boards or components over I2C using the M5Mbus, Stemma or Breakout garden pins.

Dimensions: 50mm x 50mm

Power supply: 5v 

Current max: 2A

Main BOM components: ESP32 module, 5V> 3v step down, USBC socket, reset button?

Form factor: Square with 1/4 cut-out bolt holes

Power connectors: JST-PH 2pin

The pin mappings will be as follows:


Programming will be via USB.

Control will be via Wifi

Board: 2 layers generic, according to JLCPCB.

Provisional [BOM](https://cloud.transition-space.org/s/oWLfcNf2Ctzc3SG)


Conceptual schematics:




'''Features'''
- 8x servo for a walking otto as [Robo8080 documents](https://togetter.com/li/1374900) 
- 5v input via JST
- 4x pin Tx/Rx interface for programming the ESP32
- Optional [HCS404](https://github.com/rosmo-robot/Rosmo_3D/issues/6) with staggered pins
- Optional [M5 Mbus](https://forum.m5stack.com/topic/360/m5stack-fire-pinout-leaflet)
- Optional [ staggered 7pin display 1.54"](http://www.lcdwiki.com/1.54inch_IPS_Module)
- Optional 5pin [Breakout garden header](https://shop.pimoroni.com/collections/breakout-garden)
- Optional [3v Stemma](https://www.tomshardware.com/features/stemma-vs-qwiic-vs-grove-connectors) Supports [Qwiic](https://www.reddit.com/r/electronics/comments/8lhxwg/sparkfuns_qwiic_standard_for_modular_i2c_devices/), [Grove (I2C)](https://thepihut.com/products/qwiic-cable-grove-adapter-100mm) ,[Gravity](https://learn.adafruit.com/introducing-adafruit-stemma-qt/dfrobot-gravity)



<img width="489" alt="side" src="https://user-images.githubusercontent.com/400875/151074421-d22a6a05-58cb-4bdc-bd93-8d7e2470e1fe.png">


<img width="184" alt="otto5" src="https://user-images.githubusercontent.com/400875/150679018-b0bb5ad0-db5d-4c06-ad89-1fea6cc3b11b.png">

