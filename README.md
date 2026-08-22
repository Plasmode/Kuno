# Kuno
Kuno is a P90CE201 SBC for Arduino Mega Enclosure. The name “Kuno” is concatenation of “K” of 68000 or 68K and “uno” of Arduino. Kuno is P90MB repackaged for Arduino Mega Enclosure.

![kuno](kuno_p90ce201_rev0_topview_arduino.jpg)

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
- [Schematic](kuno_rev0_scm.pdf)
- [Gerber photoplots](kuno_r0_gerber.zip)
- CPLD design file

### Software
- [P90MB monitor](x688_software_loader_r1_5.zip)
- CP/M68K [BIOS](p90mb_software_cpm68k_bios.zip)
- [CP/M68K distribution](software_cpm68k_distro_updated.zip) files, plus gkermit, microEmac, and BASIC compiler. Unzip and use gkermit to upload to P90MB. The console baud rate needs to change to 9600 baud for gkermit to work.
- Lee Davison's [EhBasic](p90mb_software_ehbasic.zip) ported to P90CE201
- [EPROM programming file](x688_software_EPROM_binary_loader1_5_ehbasic_cpm.zip) with monitor, CP/M, and EhBasic
- [Conway's Game of Life](OLED_software_game_life_with_2_array_51sec.zip) running on Kuno. This requires a 128×64 OLED display plugged into the I2C connector. The scenerio running is “Gosper Gun”.

### Documentation
[P90CE201](https://github.com/Plasmode/P90CE201SBC/blob/main/p90ce201_datasheet.pdf) Datasheet


