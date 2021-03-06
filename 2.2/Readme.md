The LCD pins were the wrong way around in v2.1. The files here simply reverse the orientation of the LCD.

![](https://raw.githubusercontent.com/rosmo-robot/Open-Core-M5stack/main/2.2/lcd.png)


![top](https://raw.githubusercontent.com/rosmo-robot/Open-Core-M5stack/main/v2.1/Octocore.jpg)

![bottom2 1](https://user-images.githubusercontent.com/400875/155421879-066880c6-0f89-4e74-8423-ee3c0ec1a567.png)
![bottom](https://raw.githubusercontent.com/rosmo-robot/Open-Core-M5stack/main/v2.1/octocore-top.jpg)


<img width="496" alt="2 1side" src="https://user-images.githubusercontent.com/400875/153314797-62cbf153-89ad-41ff-8106-a68829210b8c.png">


- [Gerber view on Altium](https://365.altium.com/files/649C7BFA-BEAC-4A11-B612-F499FA4A752B)
- [Schematic & PCB on EasyEDA](https://easyeda.com/editor#id=b0c915455cd342b9a03f863e1992dc43|42f8b3c53ee042b4857c136aa38183c5)

**Open Core ESP32 Dev board**

CERN-P licenced ESP32 board  in 5cm x 5cm [M5stack dimensions](https://shop.m5stack.com/collections/stack-series).

Summary: Design a small, self-contained ESP32 dev board capable of interfacing with other boards or components over I2C using the M5Mbus, Stemma or Breakout garden pins.

Dimensions: 50mm x 50mm

Power supply: 5v 

Current max: 2A

Main BOM components: ESP32 S3 module?, AZ1117C-3.3, TPS62177DQCR, USBC socket, TXS0108E Or similar 5V signal voltage translation/a level shifter for the servos signal

Form factor: Square with cut-out bolt holes

Power connectors: JST-PH 2pin

Programming will be via USB.

Control will be via Wifi

Board: 4 layers generic, according to JLCPCB.



**Use cases**

- 8x servo for a walking [OttoDIY/Ninja](https://www.ottodiy.com/) - [Servo library](https://github.com/madhephaestus/ESP32Servo)
- Optional Rosmo ESC for [Rosmo.io](https://rosmo.io)
- Optional [ 8pin display 1.54" or 2"](https://www.aliexpress.com/item/32859772356.html) [Library](https://github.com/Bodmer/TFT_eSPI) [data](http://www.lcdwiki.com/1.54inch_IPS_Module)
- Optional [HCS404](https://github.com/rosmo-robot/Rosmo_3D/issues/6) with staggered pins
- Optional [M5 Mbus](https://forum.m5stack.com/topic/360/m5stack-fire-pinout-leaflet)
- Optional 5pin [Breakout garden header](https://shop.pimoroni.com/collections/breakout-garden) For [3Dof](https://shop.pimoroni.com/products/msa301-3dof-motion-sensor-breakout), [6dOf](https://shop.pimoroni.com/products/lsm303d-6dof-motion-sensor-breakout), [9DoF](https://shop.pimoroni.com/products/icm20948),  [toF](https://shop.pimoroni.com/products/vl53l1x-breakout), [GPS](https://shop.pimoroni.com/products/pa1010d-gps-breakout) [More](https://shop.pimoroni.com/?q=breakout+garden)
- Optional [M5 x4 motor](https://docs.m5stack.com/en/module/lego_plus) **GPIO 16, 21, 36, 26, 17, 22, 13** With no confict with servo's
- Optional [Open DC motor](https://github.com/tomorrow56/M5Stack_Motor_Driver/blob/master/M5_Moter_v02_schematics.pdf) GPIO 16, 2, 12, 15, 13, 0
- Optional [M5 LAN base](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/schematic/Bases/lan_base.pdf) GPIO 34, 23, 19, 18, 26
- Optional [M5 868, 433 LoRa](https://docs.m5stack.com/en/module/lora868) GPIO 23,19,18, 36, 26, 05
- Optional [M5 commu](https://docs.m5stack.com/en/module/commu) GPIO 23, 19, 18, 03, 16, 21, 12, 15, 01, 17, 22
- Optional [M5 GPS](https://docs.m5stack.com/en/module/gps) GPIO 03, 16, 35, 36, 01, 17, 05, 13, 34

Iteration of this concept: https://github.com/rosmo-robot/Open-Core-M5stack/blob/main/v2/readme.md
