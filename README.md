# Kuno
Kuno is a P90CE201 SBC for Arduino Mega Enclosure

![kuno](kuno_p90ce201_rev0_topview_arduino.jpg)
### Introduction
The name “Kuno” is concatenation of “K” of 68000 or 68K and “uno” of Arduino. Kuno is P90MB repackaged for Arduino Mega Enclosure.
### Features
- P90CE201 at 22MHz
- 512K PROM
- 512K RAM
- EPM7032S CPLD
- 44-pin Disk-on-Module interface
- I2C connectors
- RC2014 I/O expansion bus
- CP/M68K ready
![kuno-annotated](kuno_p90ce201_rev0_topview_annotated.jpg)

### Design Files
- Schematic
- Gerber photoplots
- CPLD design file

### Software
- P90MB monitor
- CP/M68K BIOS
- CP/M68K distribution files, plus gkermit, microEmac, and BASIC compiler. Unzip and use gkermit to upload to P90MB. The console baud rate needs to change to 9600 baud for gkermit to work.
- Lee Davison's EhBasic for P90CE201
- EPROM programming file with monitor, CP/M, and EhBasic
- Conway's Game of Life running on P90MB. This requires a 128×64 OLED display plugged into the I2C connector. The scenerio running is “Gosper Gun”.

### Documentation
P90CE201 Datasheet


