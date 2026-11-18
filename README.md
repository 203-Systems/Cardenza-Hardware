# Cardenza Hardware

The hardware of the 203 Systems Cardenza (ESP32-S3, 240 × 135 display, 56 keys with a light each, speaker, microphone, SD card, USB).
203 Systems Cardenza 的硬件资料（ESP32-S3、240 × 135 屏幕、56 个带灯按键、扬声器、麦克风、SD 卡、USB）。

- [Cardenza_V1.0_SCH.pdf](Cardenza_V1.0_SCH.pdf): V1.0 schematic / V1.0 原理图
- [Cardenza-PCB-3D.step](Cardenza-PCB-3D.step): the PCB's 3D model / PCB 3D 模型

## I2C port / I2C 接口

![Cardenza I2C port (CN2), seen from the front, left to right: GND, VIN, SDA, SCL](docs/i2c-port.png)

Seen from the front, left to right: **GND · VIN · SDA · SCL** (pins 4, 3, 2, 1). A 4-pin, 1.0 mm pitch connector (JST SH size, as
Qwiic / STEMMA QT). VIN is USB 5 V after a diode (about 4.5–4.8 V), not 3.3 V. SDA is GPIO2, SCL GPIO1: 3.3 V logic with 5.1 kΩ
pull-ups on the board.

从正面看，从左到右：**GND · VIN · SDA · SCL**（4、3、2、1 脚）。4 针、1.0 mm 间距（JST SH 尺寸，和 Qwiic / STEMMA QT 一样）。VIN 是 USB 5 V
经过二极管后的电压（约 4.5–4.8 V），不是 3.3 V。SDA 是 GPIO2，SCL 是 GPIO1：3.3 V 电平，板上有 5.1 kΩ 上拉。

## Links / 链接

| | |
|---|---|
| Website / 官网 | https://203.io/products/cardenza-mini-synthsiser |
| Learn / 教程 | https://cardenza.203.io ([中文](https://cardenza.203.io/zh-Hans/)) |
| Firmware community / 固件社区 | https://cardenza.203.io/community |
| Firmware / 固件（鸣片） | [CardenzaSynth](https://github.com/203-Systems/CardenzaSynth) |
| Hardware layer for your own firmware / 做自己的固件 | [CardenzaHAL](https://github.com/203-Systems/CardenzaHAL) |
