# TIMBIT-01 Transceiver

The TIMBIT-01 is a custom transciever PCB based around the XBee-PRO SX 900MHz RF module, designed for long-range communication between Arbalest Rocketry's 2026 GOOSE 5 rocket and ground station.

This project was designed in collaboration with Georgii Lavreniuk with guidance from Arbalest's Ground Station lead Jose Zambrano Lopez.

## Specifications
- 4-layer board with a power plane and three ground planes
- XBee-PRO SX RF module used as the central transciever
- +5V power in using 2-pin MOLEX Micro-fit header regulated to +3.3V
- 2x6-pin MOLEX Micro-Fit headers for UART/SPI lines to host computer
- USB-C headed UART lines bridged through an FTDI chip for bring-up/debug
- SMA connector routed with 50 Ohm matched impedance network

---

## 3D Views

**Top View**
![TIMBIT-01 3D Top](Images/TIMBIT-01_3D_view_top.png)

**Bottom View**
![TIMBIT-01 3D Bottom](Images/TIMBIT-01_3d_view_bottom.png)

---

## Layer Views

**Layer 1**
![Layer 1](Images/TIMBIT-01_layer1.png)

**Layer 2**
![Layer 2](Images/TIMBIT-01_layer2.png)

**Layer 3**
![Layer 3](Images/TIMBIT-01_layer3.png)

**Layer 4**
![Layer 4](Images/TIMBIT-01_layer4.png)

---

## Project Files

* `XBeeSXPro_Breakout.PrjPcb` (project)
* Schematics: `XBeeRadioMain.SchDoc`, `FTDI_Chip.SchDoc`, `Peripherals.SchDoc`, `LED_Indicators.SchDoc`
* `MainPCB_XBeeSXPro_Breakout.PcbDoc` (layout)
* `XBeeBOM.BomDoc` (BOM)

---

