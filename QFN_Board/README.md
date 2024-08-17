# CH32V003 QFN USB C Breakout

## Project Description
A Breakout Board for the QFN Variant of the CH32V003, with pins broken out for
I2C, SPI, UART, USB, and with a USB-C Connector, and an NRST Button.  

This Board has been designed with generic and minimal parts, to make the
production and assembly of these boards easy and cheap for novices, looking to
get into the hobby and/or use the `CH32V003` Chips

NOTE: If using the USB Pins for other purposes, please keep in mind that USB_DM
and USB_PU are connected togehter with a 1.5K resistor. Remove this if needed

## Gallery
![Front of Board](/QFN_Board/Images/Front.png?raw=true)
![Back of Board](/QFN_Board/Images/Back.png?raw=true)
![Isometric View of Board](/QFN_Board/Images/Isometric.png?raw=true)
![Real Printed Boards](/QFN_Board/Images/Boards.jpg?raw=true)

## Parts List
`J2    Generic 16 Pin USB C Connector`  
`J1     3 x 2.54mm (0.1") Pin Header`  
`J3    12 x 2.54mm (0.1") Pin Header`  
`J4    12 x 2.54mm (0.1") Pin Header`  

`R1    0805 1.5K Resistor`  
`R2    0805 5.1K Resistor (Can leave unpopulated, or use 5K - 22K instead)`  
`R3    0805 5.1K Resistor (Can leave unpopulated, or use 5K - 22K instead)`  

`C1    0805 100nF Capacitor`  
`C2    0805 100nF Capacitor`  
`C3    0805 10uF  Capacitor (Can leave unpopulated, or use 100nF instead)`  

`SW1   Generic 6mm x 3mm Tactile Button`  

`U1    QFN20 0.4mm Pitch CH32V003`  
`U2    AMS1117 3.3c Voltage Regulator`  

## Pinout
**USB**
   * `Pullup  PD2`
   * `D-      PD3`
   * `D+      PD4`

**SPI**
   * `SCLK    PC5`
   * `MOSI    PC6`
   * `MISO    PC7`

**I2C**
   * `SDA     PC1`
   * `SCL     PC2`

**UART**
   * `TX      PD5`
   * `RX      PD6`

## Dimensions
The PCB is 22mm x 40mm, with 4 x 2.6mm holes in a rectangle pattern; 18mm x 36mm.  
![Drawing of Board](/QFN_Board/Images/Drawing.png?raw=true)

----
Copyright (c) ADBeta 2024
