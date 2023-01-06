# modular-things-circuits

Hardware repo for [modular-things](https://github.com/modular-things/modular-things/) custom circuits. Each folder includes a shematic image, board image, and relevant design files in a Fusion 360 Archive. 

`/samd21` contains the OG modular-things circuits based on the ATSAMD21E18A  

`/xiao` contains newer designs based on the seeed xiao development boards, in particular the RP2040 version  

`/backpacks` contain modular PHY add-ons, in development  

`/jewel` contains the stub of a usb-power-delivery based xiao-like module we are ~ planning  

To design a new board, you can start with the [base design for samd21s](samd21/base) or the [base design for the xiao platform](xiao/base). 

Note that it is also possible to virtualize *almost any existing arduino project* as a modular-thing - these circuits are just a cohesive, demonstrative set. 