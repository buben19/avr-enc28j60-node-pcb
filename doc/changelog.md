# AVR ENC28J60 Node changelog

## v1.0

 - Initial version.
 - Single layer board design.
 - Intended to be manufactured by [plosnaky.cz](http://www.plosnaky.cz/).
 - Two RJ-11 connectors for DHT-22 sensor.
 - ENC28J60 communication module.

## v1.1

 - Changed board design to two layers.
 - Intended  to be manufactured by [dirtypcbs.com](http://dirtypcbs.com/)
 - Added external 5V voltage regulator ([LM78M05](https://www.fairchildsemi.com/datasheets/MC/MC78M05.pdf)).
 - Added jumper for enabling external voltage regulator (EVR).
 - Added jumper for enabling internal voltage regulator (IVR).
 - Added 10k pull-up resistors to DHT-22 data line.
 - Replaced notification LED current limiting resistor to SMD variant.

## v1.1.1

 - Fixed version number in schematic file.
 - Changed board label to "AVR ENC28J60 NODE".
 - Updated some part names.
