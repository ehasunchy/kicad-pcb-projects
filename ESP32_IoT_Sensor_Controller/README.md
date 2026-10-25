# ESP32 IoT Sensor Controller

## Project Overview

The ESP32 IoT Sensor Controller is a custom-designed,
two-layer PCB developed using KiCad 10. The project
integrates an ESP32-WROOM-32E microcontroller module,
an SHT31 temperature and humidity sensor, a CP2102N
USB-to-UART interface, and a regulated 3.3V power supply.

The project demonstrates schematic design, PCB layout,
component placement, routing, design-rule verification,
and manufacturing documentation preparation.

**Project Type:** Personal PCB Design Portfolio Project

**Design Software:** KiCad 10

**Current Status:** Design completed and manufacturing
files generated. The PCB has not yet been fabricated
or physically tested.

## Hardware Specifications

| Component | Model / Specification | Function |
|---|---|---|
| Microcontroller | ESP32-WROOM-32E | Wi-Fi and Bluetooth connectivity |
| Temperature & Humidity Sensor | SHT31 | Environmental sensing |
| USB-to-UART Converter | CP2102N | USB serial communication and programming interface |
| Voltage Regulator | AP7361C-33FGE-7 | Regulated 3.3V power supply |
| USB Connector | USB Type-C | USB power and data connection |
| PCB | 2-layer FR-4 | Custom PCB design |

## PCB Specifications

| Parameter | Specification |
|---|---|
| PCB Layers | 2 (Top and Bottom Copper) |
| Board Material | FR-4 (proposed) |
| Board Thickness | 1.6 mm (nominal target) |
| Copper Weight | 1 oz (target) |
| PCB Design Tool | KiCad 10 |
| Routing Status | 0 unrouted connections |
| Manufacturing Outputs | Gerber X2, drill files, component position files |

*Board stack-up values are intended manufacturing
specifications and have not yet been confirmed
through fabrication.*

## Design Validation

The schematic and PCB layout were checked using
KiCad 10's built-in verification tools.

| Verification | Result |
|---|---|
| Electrical Rules Check (ERC) | Passed — 0 errors, 0 warnings |
| Design Rules Check (DRC) | Passed — 0 errors, 0 warnings |
| Unrouted Connections | 0 |
| Physical Hardware Testing | Not performed |

**Note:** Passing ERC and DRC confirms compliance
with the configured design checks; it does not
guarantee electrical functionality, manufacturability,
or successful hardware operation. Final fabrication
and assembly review is still required.

## Manufacturing Files

The project includes manufacturing outputs generated
from KiCad 10 for fabrication review and preparation.

- [Gerber and Drill Files](Manufacturing/)
- [Component Position Files](Manufacturing/)
- [Bill of Materials (BOM)](BOM/)

**Manufacturing Status:** Files generated for documentation
and review. The design has not yet been submitted for
fabrication or validated by a PCB manufacturer.

## Bill of Materials (BOM)

The BOM includes component references, quantities,
and component information for the PCB design.

- [BOM Excel Workbook](BOM/ESP32_IoT_Sensor_Controller_BOM.xlsx)
- [BOM PDF](BOM/ESP32_IoT_Sensor_Controller_BOM.pdf)

**Total Components:** 36 per board
(according to the prepared BOM).

*Component availability, exact ordering part numbers,
and assembly compatibility should be confirmed
before procurement.*

## PCB 3D Views

### Top View
![ESP32 IoT Sensor Controller - PCB Top View](Images/ESP32_IoT_Sensor_Controller_3D_Top.png)

### Bottom View
![ESP32 IoT Sensor Controller - PCB Bottom View](Images/ESP32_IoT_Sensor_Controller_3D_Bottom.png)

## PCB Layout Views

### Top Copper and Silkscreen
![ESP32 IoT Sensor Controller - Top PCB Layout](Images/ESP32_IoT_Sensor_Controller_Layout_Top.png)

### Bottom Copper and Silkscreen
![ESP32 IoT Sensor Controller - Bottom PCB Layout](Images/ESP32_IoT_Sensor_Controller_Layout_Bottom.png)

*Layout previews captured from KiCad Gerber Viewer.
Red represents top copper; blue represents bottom copper.*

## Circuit Schematic

The complete circuit schematic was designed using KiCad 10,
featuring the ESP32-WROOM-32E, USB-to-UART interface,
3.3V power regulation, and SHT31 temperature and
humidity sensor.

![ESP32 IoT Sensor Controller Circuit Schematic](Images/ESP32_IoT_Sensor_Controller_Schematic.svg)

[View full-resolution schematic](Images/ESP32_IoT_Sensor_Controller_Schematic.svg)
