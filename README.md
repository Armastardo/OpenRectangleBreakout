# Open Rectangle Breakout
RaspberryPi Pico-powered breakout board for a stickless controller
  
<p align="center">
  <img src="https://github.com/Armastardo/OpenRectangleBreakout/blob/main/Pictures/KicadRender.png?raw=true" />
</p>

<p align="center">
  <img src="https://github.com/Armastardo/OpenRectangleBreakout/blob/main/Pictures/Measurements.png?raw=true" />
</p>

Design files are available in this repository. Production files for JLCPCB in the releases page. Currently untested.

## Table of contents
* [Features](#features)
* [Usage](#usage)
* [To-do](#to-do)
* [Acknowledgements](#acknowledgements)

## Features
- USB-C to GCC and USB-C to N64 cable compatible with integrated port or with a [Model-U](https://github.com/Crane1195/Model-U).
- Can use non detachable OEM/Third party gamecube cables.
- Uses [HayBox](https://github.com/JonnyHaystack/HayBox) and [Pico Rectangle](https://github.com/JulienBernard3383279/pico-rectangle) default pinout. Labeled accordingly with some extra pins broken out if you want to expand functionality (WASD layout, add another LED, etc).

## Usage
1. Order via JLCPCB using the production files in the releases page.
	- Solder screw terminals if prefered.
2. Connect them to the PC and the first time it'll show up as a mass storage device.
3. Drop your prefered firmware in uf2 format and once it disconnects it should be good to go.
	- If you connect while pressing the BOOT button, it'll show again as a mass storage device so you can update the firmware or replace it.

## To-do:
- Use it in a build! Please share pics if you do so. My discord username is Quark#0009

### Made using the Open Rectangle Template
OpenRectangleTemplate project] - https://github.com/Armastardo/OpenRectangleTemplate

This was just a proof of concept to see how easy it is to use the template. It's good! But I still need to work on both projects to get them to where I want.