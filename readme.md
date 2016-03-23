# IoT node pcb

PCB design for AVR ENC28J60 IoT node board. This repository contains only board
design files, design files for 3D printable case are stored in different repository.

## Features

 - AVR [ATmega328P](http://www.atmel.com/devices/atmega328p.aspx) main microcontroller ([Arduino Pro Mini](https://www.arduino.cc/en/Main/ArduinoBoardProMini)).
 - Ethernet connection with [enc28j60](http://www.microchip.com/wwwproducts/en/en022889) chip.
 - 3V3 switching voltage stabilizator.
 - Two RJ-11 connectors for sensors.
 - Powered using  5.5 mm power socket. Central positive,  7-12V.
 - Modular design.
 - Notification LED.
 - Intended  to be manufactured by [dirtypcbs.com](http://dirtypcbs.com/).
 - Optional on board 5V voltage stabilizer. You don't need to rely to voltage stabilizer on Arduino module.

## Images

![Assembled node](img/node-assembled.jpg "Assembled node")

![Board design](img/board.png "Node board design")
