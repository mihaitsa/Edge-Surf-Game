# Edge Surf Game on Arduino

## Introduction
This is a simplified version of the Edge Surf Game that you can play when your internet is down, but this time it's on an Arduino, and it uses a matrix as the main output device. I believe this to be useful for others, as it can be played when the internet is down.

## Overview

In the game, the player controls the movements using a joystick, and the goal of the game is to make as high of a score as possible while avoiding obstacles, and it's calculated based on the time you lasted. 

## Hardware design

### Components Required for the project

- **Arduino One board**
- **16x2 LCD screen**
- **Joystick Module**
- **Jumper wires**
- **Breadboard**
- **LED Matrix**

### Bill of Materials (BOM)

- **Arduino Uno Board**  
  - Description: Microcontroller development board  
  - Quantity: 1  
  - Datasheet/Link: [Arduino Uno Datasheet](https://www.arduino.cc/en/uploads/Main/Arduino_Uno_Rev3-schematic.pdf)

- **16x2 LCD Screen**  
  - Description: Alphanumeric LCD (HD44780 compatible)  
  - Quantity: 1  
  - Datasheet/Link: [16x2 LCD Datasheet](https://components101.com/sites/default/files/component_datasheet/16x2-Character-LCD-Module-Datasheet.pdf)

- **Joystick Module**  
  - Description: Analog joystick with button  
  - Quantity: 1  
  - Datasheet/Link: [Joystick Module Datasheet](https://www.electronicoscaldas.com/datasheet/PS2-Joystick.pdf)

- **Jumper Wires**  
  - Description: Male-to-Male and Male-to-Female wires  
  - Quantity: ~20  
  - Datasheet/Link: Generic  

- **Breadboard**  
  - Description: Breadboard
  - Quantity: 1   
  - Datasheet/Link: Generic  

- **8x8 LED Matrix**  
  - Description: LED matrix with MAX7219 driver  
  - Quantity: 1  
  - Datasheet/Link: [MAX7219 Datasheet](https://datasheets.maximintegrated.com/en/ds/MAX7219-MAX7221.pdf)



[Block Diagram](images/DiagramBlock.jpg)
[Electric Diagram](images/ElectricDiagram.jpg)
[Physical Hardware](images/physical.jpg)
## Software design

## Results