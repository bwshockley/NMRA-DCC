#DCC Booster Shield for Arduino#

This is an Arduino Uno R3 compatible sheild that generates a boosted track level signal for Digital Command Control of model
railroads.  This shield is based off the [Railstars RAILbooster](https://github.com/Railstars/RAILbooster) and the LMD18200
H-bridge.  Included in this design is feedback on DCC signal, overtemp, and over current as well as shut-down protection for
each of those feedback components.  This booster can support 3A to the rails.

In order to use it, please see the [CmdrArduino](https://github.com/Railstars/CmdrArduino) code.  You will need to load the
Arduino source code onto a Arduino UNO R3 or compatible board.  Signal for the DCC control is sent via digital Pin #10.

The Uno can also act as ISP for the ATTINY44 on this board for feedback and shut-down protection.
