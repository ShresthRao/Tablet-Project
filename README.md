# Tablet Project
## Description
This project is a custom tablet. It contains a custom PCB and case. The PCB connects to a CM4 Lite Wireless module for processing and wireless connections. The PCB is connected to a Viekk VK1200 V2 device that is used as the digitiser, stylus and the display.

## Bill of Materials (BOM)

Note: All prices are in USD. Production and assembly files contain additional specs where applicable.
Note: Bom for Item 4: JLCPCB Custom Manufactured PCB is in /Production/assembly/Custom Tablet_bom_raw.csv , /Production/assembly/Custom Tablet_jlcpcb_bom.csv

### Purchased Components

| Item | Qty | Component | Price (USD) | Link | Description |
| :---: | :---: | :--- | :---: | :--- | :--- |
| 1 | 2 | NOVA 9060100 8000mAh 3.7V Micro LiPo Battery Pack with PCB & 100mm Cable (Wired in Parallel) | $18.65 | [Robu.in](https://robu.in/product/nova-9060100-8000mah-3-7v-lipo-battery-pack/) | Lined in Parallel |
| 2 | 4 | Harwin R25-1001102 Hex Standoffs (F-F Brass M2.5 11mm for CM4) | $1.71 | [Element14](https://in.element14.com/harwin/r25-1001102/standoff-hex-f-f-brass-m2-5-11mm/dp/3754478) | Standoffs for CM4 module |
| 3 | 1 | Raspberry Pi Compute Module 4 (CM4104000 - Lite, 4GB RAM) | $93.11 | [Element14](https://in.element14.com/raspberry-pi/cm4104000/rpi-compute-module-4-lite-4gb/dp/3563487) |  |
| 4 | 1 | JLCPCB Custom Manufactured PCB | $279.95 | [JLCPCB](https://cart.jlcpcb.com/quote?spm=jlcpcb.Public.2006&jlc_vid=TlcPUgdeEgRZAlRTTlRaVAFVFlRZV1IFRFgLAQdVRFIxVlNeQVBYVlxURlZbVDsOAxUeFF5JWAsCBBQFFU8NCAlJ) | |
| 5 | 1 | VEIKK VK1200 V2 Drawing Tablet | $157.25 | [Amazon](https://www.amazon.in/gp/product/B08G8CKSWK/) | |
| 6 | 1 | Heat Shrink Tubing Kit (328 pcs) | $1.65 | [Robu.in](https://robu.in/product/328pcs-heat-shrink-tube-heat-shrink-tube-kit/) | |
| 7 | 1 | High-Temperature Kapton Polyimide Tape (10mm × 33m) | $1.03 | [Robu.in](https://robu.in/product/10mm-33m-100ft-high-temperature-heat-resistant-polyimide-kapton-tape-hot/) | |
| 8 | 1 | Digital Multimeter (Small LCD, AC/DC) | $1.80 | [Robu.in](https://robu.in/product/digital-multimeter-small-yellow-color-lcd-ac-dc-measuring-voltage-current/) | |
| 9 | 1 | Multimeter Test Probes | $1.25 | [Robu.in](https://robu.in/product/1-month-warranty-1260/) | |
| Total | | | $565 (accounted for future price changes) | | |

### On-Hand Hardware & Tools

* Storage: Micro-SD card (64GB+)
* Cables: 3x USB-C cables, 1x Short HDMI cable
* Wiring: Red and Black battery wire
* Tools & Consumables: Soldering iron, flux, solder, tweezers, superglue
* Peripherals: USB keyboard and mouse

## Specifications
### Screen:
11.6 inch
Laminated anti-glare
8,192 levels of pressure sensitivity
Resolution is 1920 × 1080 pixels (Full HD)
Color Gamut: 72% NTSC

### PCB
1 HDMI port for connection of VIEKK VK1200 V2 device.
1 SD card slot
2 USB-C ports
2 Connectors for CM4 Lite Wireless module
1 Solder pads for connection of batteries

### Stylus
2 battery-less styluses
8,192 levels of pressure
60 degrees of tilt
290 RPS of report rate
5080 LPI of resolution

### Case (total size of custom tablet)
202 mm width
378 mm length
24 mm tall

### Software
Raspberry Pi OS (64-bit) with VIEKK drivers

## Screenshots of the design:
### Schematic
#### Full Screenshot
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/Full%20Schematic.png" alt="Full Schematic Overview">

#### Part-Wise screenshots
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/1.png" alt="Schematic Page 1">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/2.png" alt="Schematic Page 2">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/3.png" alt="Schematic Page 3">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/4.png" alt="Schematic Page 4">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/5.png" alt="Schematic Page 5">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/6.png" alt="Schematic Page 6">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/7.png" alt="Schematic Page 7">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/8.png" alt="Schematic Page 8">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Schematic/9.png" alt="Schematic Page 9">

### PCB
#### Zoned
<img src="Assets/PCB%20%26%20Schematic%20Assets/Zones/All_Zones.png" alt="All Layers With Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Zones/B.Cu_Zones.png" alt="Bottom Copper With Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Zones/F.Cu_Zones.png" alt="Front Copper With Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Zones/Ground_Zones.png" alt="Ground Copper With Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/Zones/Power_Zones.png" alt="Power Copper With Zones">


#### Un-Zoned
<img src="Assets/PCB%20%26%20Schematic%20Assets/No-zones/All_NoZones.png" alt="All Layers No Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/No-zones/Blue_NoZones.png" alt="Blue Layer No Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/No-zones/F.Cu_NoZones.png" alt="Front Copper No Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/No-zones/Ground_NoZones.png" alt="Ground Layer No Zones">
<img src="Assets/PCB%20%26%20Schematic%20Assets/No-zones/Power_NoZones.png" alt="Power Layer No Zones">

### CAD
#### Assembly
<img src="Assets/3D%20model%20Assets/Front/Assembly_Front.png" alt="Assembly Front View">

<img src="Assets/3D%20model%20Assets/Side/Assembly_Side.png" alt="Assembly Side View">

#### Bottom Case
<img src="Assets/3D%20model%20Assets/Front/Bottom_Front.png" alt="Bottom Front View">

<img src="Assets/3D%20model%20Assets/Side/Bottom_Side.png" alt="Bottom Side View">

#### Top Case
<img src="Assets/3D%20model%20Assets/Front/Top_Front.png" alt="Top Front View">

<img src="Assets/3D%20model%20Assets/Side/Top_Side.png" alt="Top Side View">

****
