
### Modular-Thing Circuits

These should... go in a circuits repo, for them? IDK 

- stuff right wing and route
- labels, baby, labels... 
- make repo
  - log the base 
- start on button / switch... 
  - is rgb, button, and limit, etc... 
  - rgbb thing is done... then the stepper, before I get burnt out ? 
- OLED display 

OK the stepper... needs a 1x4 connector, then to be routed... 

That's routed... with the note that +3v3 to a logic-enabled endstop would need to be soldered after the fact. Nah fuck it, I'm routing it out. 

OK, I'm going to start a repo... push the log... 

### W/R/T Machine Week

- one... big one: is the computer there with it ? 
- five canonical examples... w/ one system 
  - drawing machine (big thing... but easy... ~ 2 hours) 
  - line following robot (needs pc detachment, so difficult) 
  - drum kit (buttons, solenoids) 
  - passive sensing... plant watering thing... 
- jake needs to make OSAP into an arduino library... fr fr 
- should also test webserial, my dude 
- is it just... planager, in the end ? 
- possible machines
  - pipette
  - drawing 
  - robot-arm-ish 
  - drink mixing machine 
  - timelapse machine 
- we need to test / build the usb-sync PHY, baby... that'll be your big lift, maybe ? 
- this means a few output / input devices 
  - do 'em with usb-extension thing... 
    - samd21
    - usb extension 
    - 2.0mm is tite if possible 
    - 1.5 sided / 1 sided when possible 
  - stepper motor
    - use the toshiba chips,
    - try w/ the new... anthony chip 
    - tmc2209 (optional)
    - quentin requests endstops 
  - potentiometer 
  - capacitive sensor, 
    - q-touch pins are labelled "y" in col "ptc" in d21 datasheet 7.1 
    - do two-backgammon things ?
  - ... limit switch / button 
  - microphone 
  - servo(s) ?
  - TOF 
  - low-side mosfet 
  - breakout-style 
- goals are like
  - zero-install machine building (modular-thing and webserial)
  - actually-simple machine description 
- my thoughts... I can pinch OSAP onto the D11, or some semblance of it, 
  - though flash-naming might produce some trouble ? 
  - we could instead do a series of USB-PHY circuits on the D21, have 'em fabbed 
  - then we do modular-thing 
  - what are the inputs / outputs that we want? 
