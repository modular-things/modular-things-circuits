## 2022 12 13

Just some notes from the week, for improvements if we run more SAMD21 boards.

- usb extension connector should be 12.5mm across, not 12mm as current designs implement 
- don't expose the USB prongs on tCream (solder paste) layer 
- circuits shouldn't have GND underneath the usb extension bit: the extensions scrape solder mask off, and eventually contact the GND, fking the connection 
- low-fet should probably have a flyback diode present 
- consider sticking an i2c QWIIK on 'em, 