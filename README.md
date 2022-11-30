# modular-things-circuits

Hardware repo for [modular-things](https://github.com/modular-things/modular-things/). Each folder includes a shematic image, board image, and relevant design files in a Fusion 360 Archive. 

To design a new board, you can start with the [base design](base). Note that it is also possible to virtualize *almost any existing arduino project* as a modular-thing - these circuits are just a cohesive, demonstrative set. 

---

| accelerometer | |
| --- | --- |
| ![brd](accelerometer/board.png) | ![sch](accelerometer/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| LSM6DSO Accelerometer | 1 |
| 0R 1206 | 1 |
| 1k 1206 | 1 |
| 2k2 1206 | 2 |
| 10k 1206 | 1 |
| 0.1uF 1206 | 2 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| breadboard | |
| --- | --- |
| ![brd](breadboard/board.png) | ![sch](breadboard/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG (big) | 1 | 
| 0R 1206 | 1 |
| 10k 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| capacitive | |
| --- | --- |
| ![brd](capacitive/board.png) | ![sch](capacitive/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| 0R 1206 | 1 |
| 1k 1206 | 3 |
| 10k 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| low-fet | |
| --- | --- |
| ![brd](low-fet/board.png) | ![sch](low-fet/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| NMOS | 1 |
| 2x3 SMT Header | 1 |
| 2x4 SMT Header | 1 |
| 0R 1206 | 2 |
| 1k 1206 | 2 |
| 10k 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| oled | |
| --- | --- |
| ![brd](oled/board.png) | ![sch](oled/schematic.png) |

`note: an early version of these circuits need SCL and SDA to be flipped in between the board and the OLED module`

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| OLED Module | 1 |
| 0R 1206 | 1 |
| 4.99k 1206 | 2 |
| 10k 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| potentiometer | |
| --- | --- |
| ![brd](potentiometer/board.png) | ![sch](potentiometer/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| POTS | 2 |
| 0R 1206 | 1 |
| 10k 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| rgbb | |
| --- | --- |
| ![brd](rgbb/board.png) | ![sch](rgbb/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| RGB LED | 1 |
| SWTCH | 1 |
| 1x3 SMT Header | 1 |
| 0R 1206 | 1 |
| 1k 1206 | 3 |
| 10k 1206 | 2 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---

| servo | |
| --- | --- |
| ![brd](servo/board.png) | ![sch](servo/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| 1x3 SMT Header | 1 |
| 0R 1206 | 1 |
| 10k 1206 | 1 |
| 1uF 1206 | 1 |
| 10uF 1206 | 3 |

---

| stepper-hbridge | |
| --- | --- |
| ![brd](stepper-hbridge/board.png) | ![sch](stepper-hbridge/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| H-Bridge | 2 |
| 2x3 SMT Header | 1 |
| 0R 1206 | 2 |
| 120R | 2 |
| Shunt | 2 | use ~ 300mOhm, we think |
| 10k 1206 | 1 |
| 0.1uF 1206 | 2 |
| 1uF 1206 | 4 |
| 10uF 1206 | 4 |

---

| time-of-flight | |
| --- | --- |
| ![brd](time-of-flight/board.png) | ![sch](time-of-flight/schematic.png) |

| part | count | info ? |
| --- | --- | --- |
| ATSAMD21 | 1 | uc |
| JTAG 10-pin | 1 |
| VREG | 1 | 
| VL53 TOF | 1 |
| 0R 1206 | 1 |
| 4.99k 1206 | 2 |
| 10k 1206 | 1 |
| 0.1uF 1206 | 1 |
| 1uF 1206 | 2 |
| 10uF 1206 | 2 |

---