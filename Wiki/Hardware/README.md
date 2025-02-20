# Computer-Control Programs - Hardware Guide

This is the guide for buying and setting up the hardware for the computer-control programs.

If you already have the hardware, skip ahead to the software tutorial.
- [Software Tutorial](/Wiki/Software/README.md)


## Before you Begin

Before you begin, make sure you meet all of the following requirements:

1. You have a working [microcontroller setup](https://github.com/PokemonAutomation/Microcontroller) and you know how to run microcontroller programs. **(DO NOT SKIP the Microcontroller tutorial. It provides the necessary background to run Computer-Control.)**
2. You have computer running 64-bit Windows or macOS. As of this writing, no other platforms are supported. But if you use Linux, then you may be knowledgeable to adapt our macOS guide to work for your Linux. 
3. You have a regular Switch (not a Switch Lite) if you want to use programs requiring video feedback.
4. Be willing to spend an additional $20 - $50 USD for the new hardware.

Your computer must be sufficiently powerful:

- If you intend to control **1** Switch: A dual-core processor @ 3 GHz no older than 2015 should be sufficient.
- If you intend to control **2** Switches: A quad-core processor @ 3 GHz no older than 2015 should be sufficient.
- If you intend to control **4** Switches: 6-8 cores minimum.


## Serial Hardware

In order to use computer-control programs, your computer needs to be able to control your game console (duh!).

The way we do it is by using a [serial connection](https://en.wikipedia.org/wiki/Serial_port) to connect the microcontroller to the computer. This allows the computer to take control of your game console.

<img src="images/serial-setup.jpg">


The serial hardware setup will depend on what microcontroller you have.

- [Arduino Leonardo](ArduinoLeonardo.md)
- [Teensy 2.0 and Teensy++ 2.0](Teensy2.md)
- [Pro Micro](ProMicro.md)
- [Arduino Uno R3](ArduinoUnoR3.md)

## Video Hardware

Some programs also need to see the screen! So a video capture card is also needed. See the capture card guide [here](VideoHardware.md).

<hr>

**Discord Server:** 

[<img src="https://canary.discordapp.com/api/guilds/695809740428673034/widget.png?style=banner2">](https://discord.gg/cQ4gWxN)

