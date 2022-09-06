# MSX HX-10 USB Keyboard

## Intro
My First Computer was an MSX HX-10.
At one point it stopped working because the joystick was continueing registering as being directed up.
It's on my project list to try and repair the board but in the meantime I thought it was a good idea to setup the keyboard as a USB device (and at least get to use it).

[![][msx2]][msx2]

## Firmware

https://github.com/tmk/tmk_keyboard
https://github.com/peteclarkez/tmk_keyboard/tree/master/keyboard/msx_hx10

Upon looking at he options for making this work i found the tmk firmware. It was relatively easy to rebuild this to include the new keyboard details

The following links contained some good tutorials to get started.

 * [TMK Tutorial 1](https://deskthority.net/workshop-f7/how-to-build-your-very-own-keyboard-firmware-t7177.html)
 * [TMK Tutorial 2](https://deskthority.net/workshop-f7/how-to-build-your-very-own-keyboard-firmware-t7177.html#p141386)


## Hardware

The adapter that used to connect the keboard to the board is a 2mm pitch so it's relatively easy to use an adapter to integrate this with a normal teensey board

 * [2mm to 2.54mm Pitch Adapter](http://www.proto-advantage.com/store/product_info.php?products_id=3800084) 
 * [Teensey 2++](https://www.pjrc.com/store/teensypp.html)
 

|               |       |
|:-------------:|:-----:|
| [![][msx7]][msx7] | Adapter Hardware |
| [![][msx3]][msx3] |  Teensey & Adapter Hardware |
| [![][msx1]][msx1] | Adapters connected to the keybaord matrix |


## Firmware Customisation

First thing was to use 

[![][msx9]][msx9] 


 * MSX Generic KeyMap http://map.grauw.nl/articles/keymatrix.php
 * MSX Info Incl Txt Keymap http://problemkaputt.de/portar.htm#peripheralinterface

* MSX HX-10 Firmware https://github.com/peteclarkez/tmk_keyboard/tree/master/keyboard/msx_hx10

## LEDs

|               |       |
|:-------------:|:-----:|
| [![][msx6]][msx6] | I highlighted the trace on the image in order to ensure i got the right pins for the leds | 
| [![][msx4]][msx4] | Here we have a link attached to the pins overhanging the end of the chip in order to flash the led for power permanently and the caps lock when needed |
## Keyboard Fix

When I got everything running There were a number of the keys which didn't work properly so I ordered an applied some keyboard fix to the electrical contacts.

http://www.nightfallcrew.com/16/12/2015/toshiba-hx-10-64k-msx-keyboard-pad-fix/


|               |       |
|:-------------:|:-----:|
| [![][msx8]][msx8] | Keyboard Fix |


Toshiba MSX HX-10
=================
  
#### Toshiba MSX HX-10
 * [msx.org](https://www.msx.org/wiki/Toshiba_HX-10P)
 * [computing history](http://www.computinghistory.org.uk/det/15464/Toshiba-MSX-HX-10/)
 * [night Fall Crew](http://www.nightfallcrew.com/07/11/2010/toshiba-msx-home-computer-hx-10/)

### Other Links used in the making of this


 * [Keyboard dissasembly pics](https://www.msx.org/forum/debates-en-espa-ol/hardware/ayuda-con-teclas-de-msxtoshiba-hx-10)

 * [ModelM TMK Keyboard](https://github.com/lmorchard/tmk_keyboard/tree/bdde5f9413ce5c3ea627f201b04f04fe371806ce/keyboard/modelm)

 * [HID Listen for Debug](/ekmps/shops/ultracabs/images/standard-joystick-set-with-mixed-pushbuttons.-90-p.jpg)
 

|               |       |
|:-------------:|:-----:|
| [![][msx1]][msx1] | [![][msx2]][msx2] |
| [![][msx3]][msx3] | [![][msx4]][msx4] |
| [![][msx5]][msx5] | [![][msx6]][msx6] |
| [![][msx7]][msx7] | [![][msx8]][msx8] |
| [![][msx9]][msx9] | |

[msx1]: images/20171013_141401.jpg "XX"
[msx2]: images/20171013_141442.jpg "XX"
[msx3]: images/20171021_115750.jpg "XX"
[msx3]: images/20171021_115901.jpg "XX"
[msx4]: images/20180502_210624.jpg "XX"
[msx5]: images/20180502_210705.jpg "XX"
[msx6]: images/KeyBoardTrace.jpg "XX"
[msx7]: images/ProtoAdvantage.jpg "XX"
[msx8]: images/keyboardFix.jpg "XX"
[msx9]: images/keyboardMatrix.jpg "XX"