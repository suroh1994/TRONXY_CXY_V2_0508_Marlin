# Marlin Firmware for an ANET A8

This repo contains the Marlin firmware in version 2.1.2.5 with adaptations to fit the Anet A8 clone I got a hold of. 

The printer has: 
- a Tronxy CXY V2 0508 motherboard 
- a RepRapDiscount Smart Controller display and control (I didn't try to get the buzzer to work)
- a belt tensioner on the X-axis which shortened the possible movement on the x-Axis (you're hopefully not affected by this design error on my part)

Besides the configuration, I had to update the pins on the pins_MELZI_TRONXY.h to fit the mainboard.