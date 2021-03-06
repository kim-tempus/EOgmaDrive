<!---
  EOgmaDrive
  Copyright(c) 2017 Ogma Intelligent Systems Corp. All rights reserved.

  This copy of EOgmaDrive is licensed to you under the terms described
  in the EOGMADRIVE_LICENSE.md file included in this distribution.
--->

# EOgmaDrive

Repository for the EOgmaNeo-based self driving car (SDC).

Three sub-directories contain Readme.md files that further describes each configuration. A summary for each configuration is presented below.

Included are two configurations (1 & 2) used to build a 1/10 scale 2WD RC self driving car, and a third configuration to create a hand-sized 3D printed self driving car (uSDC).

**Configuration1** was used in producing the following Ogma YouTube video:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=0ibVhtuQkZA
" target="_blank"><img src="http://img.youtube.com/vi/0ibVhtuQkZA/0.jpg" 
alt="Self Driving Car Learns Online and On-board on Raspberry Pi 3" width="480" height="360" border="1"/></a>

**Configuration3** was used in producing the following Ogma YouTube video of the uSDC:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=9GNbVkMb8Qw
" target="_blank"><img src="http://img.youtube.com/vi/9GNbVkMb8Qw/0.jpg" 
alt="World's Smallest Self-Driving Car - a Raspberry Pi Zero on wheels.." width="480" height="360" border="1"/></a>

As seen in the above video, an [InfiniTrax](http://infinitrax.com/product.php) "1080 BEAST" modular track was used with the uSDC.

A [Unity](https://unity3d.com/) based simulation [OgmaDrive](https://github.com/ogmacorp/OgmaDrive) was used to prototype the SDC, using C# scripts and the EOgmaNeo library.

## Configuration1

- Steam Controller with wireless dongle

SDC:

- Traxxas Rustler RC car
- Raspberry Pi3
- Pi Camera v2
- Pi Camera case
- Active cooling case "Eleduino Raspberry Pi 3 and Raspberry Pi 2 Model B Acrylic Case with High Quality Mini Fan"
- 2 pcs 18650 batteries with battery pack (for powering the steering servo)
- Arduino UNO
- Breadboard
- Anker PowerCore 10000 (for powering the Pi)
- Using fast event-based version of EOgmaNeo + OpenCV's Canny Edge + PySerial (for Arduino communication)

RF Version Extra:

- Pi-Top with Raspberry Pi 3
- Arduino UNO (or Leonardo, USB to RPi)
- RF Transmitter/Receiver Modules "Makerfocus 2pcs Wireless Module NRF24L01+PA+LNA in Antistatic Foam Arduino Compatible with Antenna"

## Configuration2

Base station, for limited communication with the SDC:

- Pi-Top
- Raspberry Pi3
- Arduino UNO (or Leonardo, USB to RPi)
- XBee Arduino shield (v1.0 or modified v1.3)
- XBee Pro (S1, with u.fl antenna)

SDC:

- Traxxas Rustler RC car (optional clear body)
- Raspberry Pi3
- Raspberry Camera (mounted to front bumper)
- Pimoroni Pibow case
- Freetronics PiLeven (i2c to RPi, UART to XBee)
- XBee Arduino shield (v1.0 or modified v1.3)
- XBee Pro (S1, u.fl antenna)
- Power Bank (to PiLeven or RPi)
- Servo pass-through connector (attached to PiLeven)

## Configuration3

- Steam Controller with wireless dongle
- InfiniTrax modular track system (optional)

uSDC:

- 3D Printed base, RPi ZeroW mount, and camera mount
- Raspberry Pi ZeroW
- Pimoroni Explorer pHAT (motor drivers)
- Pololu 136:1 sub-micro planetary gearmotors, wheels, and front ball caster
- Adafruit Lithium Ion Polymer Battery, with a PowerBoost and charger module
- SainSmart wide angle camera

## License and Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />The work in this repository is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. See the  [EOGMADRIVE_LICENSE.md](https://github.com/ogmacorp/EOgmaDrive/blob/master/EOGMADRIVE_LICENSE.md) and [LICENSE.md](https://github.com/ogmacorp/EOgmaDrive/blob/master/LICENSE.md) files for further information.

Contact Ogma via licenses@ogmacorp.com to discuss commercial use and licensing options.

EOgmaDrive Copyright (c) 2017 [Ogma Intelligent Systems Corp](https://ogmacorp.com). All rights reserved.
