# Side Winder FFB Adapter

## Introduction

Adapt-FFB-Joy is an AVR microcontroller based device that looks like a joystick with advanced force feedback features in a Windows machine without need for installing any device drivers to PC.

## Circuit Diagram

[![][circuit]][circuit] 

## Build

May 2019

I got a hold of the capacitors required and the DB15 Breakout

[example breakout Board @ Amazon](https://amzn.eu/d/2lSi5U0) 

[![][DB15]][DB15]

I then build this in a breadboard setup and connected it back to the Joystick.

[![][setup]][setup] 
[![][board]][board]



Results not as expected, I didn't get he FFB (no matter which tool I tried) &  I also got some twitching on the readouts as you can see from the gif below.

[![][twitch]][twitch] 


## Future

It may be length or quality of cables, so the plan is to build this back up again on a breadboard and try again.

[![][DB15v2]][DB15v2]

## Links

* [GitHub - tloimu/adapt-ffb-joy: adapt-ffb-joy](https://github.com/tloimu/adapt-ffb-joy)	

* [Reviving an old gameport joystick - Ars Technica OpenForum](https://arstechnica.com/civis/viewtopic.php?f=53&t=1307787)																

* [Google Code Archive - adapt-ffb-joy](https://code.google.com/archive/p/adapt-ffb-joy/)	
* [Google Code Archive - sidewinder-arduino](https://code.google.com/archive/p/sidewinder-arduino/)	
* [Google Code Archive - sw3dprousb](https://code.google.com/archive/p/sw3dprousb)	

* [Microsoft SideWinder - Wikipedia](https://en.m.wikipedia.org/wiki/Microsoft_SideWinder)	
* [Microsoft SideWinder - Wikipedia](https://en.m.wikipedia.org/wiki/Microsoft_SideWinder#Force_Feedback_Pro)	

* [Reverse Engineering the Force Feedback Pro - DescentBB](https://descentbb.net/viewtopic.php?f=8&t=19061&sid=29e01b6d793a0064676c2eac7d3a78b3)	
* [Reverse Engineering the Force Feedback Pro - DescentBB](https://www.descentbb.net/viewtopic.php?f=8&t=19061#p295208)	
* [USB Converter for MS Sidewinder 3DPro, PP, and FFP - DescentBB](https://www.descentbb.net/viewtopic.php?t=15526)	

* [Wolfmans Howlings](http://blog.wolfman.com/articles/2009/10/24/converting-a-sidewinder-3d-pro-joystick-to-usb)	

* [FFB-Vert](http://www.iowajohnsons.com/FFBVert/FFBVert.html)	

* [MS Sidewinder FFB Pro working with USB adapter! - Hardware and Controllers - Rise of Flight Forum](https://riseofflight.com/forum/topic/45292-ms-sidewinder-ffb-pro-working-usb-adapter/)	

* [Computer vision inside a Microsoft force feedback pro, the madness - YouTube](https://www.youtube.com/watch?v=IvXyDwlAN8k)	
* [What&#39;s Inside the Microsoft Sidewinder Force Feedback Pro Joystick - YouTube](https://www.youtube.com/watch?v=wVMvXAtynp0)	
* [Converting Sidewinder Precision Flightstick Pro To USB - YouTube](https://www.youtube.com/watch?v=Or2Szf32lL4)	

* [FFB-FFP-USB-adapter - EasyEDA](https://easyeda.com/feather/FFB_FFP_USB_adapter-iHBvN5nhz)	

[circuit]: images/adaptffbjoy-circuit.png "XX"
[board]: images/sidewinderFFBBoard.jpg "XX"
[setup]: images/sidewinderFFBSetup.jpg "XX"
[twitch]: images/sidewinderFFBTwitch.gif "XX"
[DB15]: images/DB15BreakoutAdapter.jpg "XX"
[DB15v2]: images/DB15Breakout2.png "XX"