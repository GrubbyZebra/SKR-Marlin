# Marlin Firmware for SKR Bear / SKR 1.4 / TMC2209

![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

<<<<<<< HEAD
## Specs
=======
Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!
>>>>>>> 2.0.x

This firmware is configured for a Full Bear MK3 fitted with a BigTreeTech SKR 1.4 and TMC2209s:

### Motherboard
* [BigTreeTech SKR 1.4](https://www.biqu.equipment/collections/skr-series/products/btt-skr-v1-4-skr-v1-4-pro)

### Printed Parts
* [Printed control box by RC-CNC](https://www.prusaprinters.org/prints/20416-skr-bear-case)
* [Universal Printed control box by Juan Pochol](https://www.thingiverse.com/thing:4178177)
* [Bear TFT35 LCD Screen Case by Jerlo](https://www.prusaprinters.org/prints/25002-jerlo-bear-lcd-cover-bigtreetech-tft35)

### Drivers
* [BTT TMC2209 V1.2](https://www.biqu.equipment/collections/stepper-motor-board/products/bigtreetech-tmc2209-stepper-motor-driver-for-3d-printer-board-vs-tmc2208) on X/Y/Z/E/E0

### Steppers
* **X-axis:** LDO 1.8° motor
* **Y-axis:** LDO 1.8° motor
* **Z-axis:** LDO 1.8° motor
* **Extruder:** LDO 1.8° motor
* **Microstepping:** 1/32

### Hotend
 * Direct drive [E3D V6 all-metal hotend](https://e3d-online.com/v6-all-metal-hotend)
 * [E3D 40W 24V Heater Cartridge](https://e3d-online.com/standard-heater-cartridge)
 * [Mechatronics B5015E24B-BSR 24v 5015 fan](https://www.digikey.com/product-detail/en/mechatronics-fan-group/B5015E24B-BSR/1570-1034-ND/5209731) (parts cooling)
 * [PINDA V2](https://www.prusa3d.com)


### LCD Controller
* RERAP Discount Smart Controller

### Wiring Guide
* [SKR V1.4 Wiring Guide](https://github.com/codiac2600/SKR-MK3s-V1.4-Beta/blob/master/SKR%20MK3s%20Wire%20Guide.pdf)

<<<<<<< HEAD
### BOM
* [Bill of Materials](https://github.com/codiac2600/SKR-MK3s-V1.4-Beta/blob/master/SKR%20Conversion%20BOM.csv)

### Other
=======
- Submit **Bug Fixes** as Pull Requests to the ([bugfix-2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)) branch.
- Follow the [Coding Standards](http://marlinfw.org/docs/development/coding_standards.html) to gain points with the maintainers.
- Please submit your questions and concerns to the [Issue Queue](https://github.com/MarlinFirmware/Marlin/issues).

## Marlin Support

For best results getting help with configuration and troubleshooting, please use the following resources:

- [Marlin Documentation](http://marlinfw.org) - Official Marlin documentation
- [Marlin Discord](https://discord.gg/n5NJ59y) - Discuss issues with Marlin users and developers
- Facebook Group ["Marlin Firmware"](https://www.facebook.com/groups/1049718498464482/)
- RepRap.org [Marlin Forum](http://forums.reprap.org/list.php?415)
- [Tom's 3D Forums](https://forum.toms3d.org/)
- Facebook Group ["Marlin Firmware for 3D Printers"](https://www.facebook.com/groups/3Dtechtalk/)
- [Marlin Configuration](https://www.youtube.com/results?search_query=marlin+configuration) on YouTube

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - USA &nbsp; [Donate](http://www.thinkyhead.com/donate-to-marlin)
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - USA
 - Chris Pepper [[@p3p](https://github.com/p3p)] - UK
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - USA
 - Erik van der Zalm [[@ErikZalm](https://github.com/ErikZalm)] - Netherlands &nbsp; [![Flattr Erik](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
>>>>>>> 2.0.x
