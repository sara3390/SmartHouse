# SmartHouse

# Video of the project
https://youtu.be/GzypG_V1_t4

# Introduction
 I have 6 projects all connected with a smart arduino house.
 
 # Connection 
<img src="/ConnectionDiagram.jpg" alt="Connection" />
<img src="/ConnectionList.jpg" alt="Connection" />

### 1 Breathing Light
In this project I connected the GND and VCC with G and V on the arduino plus board. The S actually controls the LED light, when S is on HIGH  level it is turned on and when it is on LOW level it is turned off. I made it with delay of 2ms for a blinking effect

### 2: Passive Buzzer

Usually for emiting sound we use buzzer whether active or passive. For my project I used passive buzzer firstly to emit fire alarm in the smart house.

### 3: Ode to joy
I made the "Ode to joy" in the same way as the fire alarm. 

### 4: Controlling LED light by pressing button

I made this project based on the previous project just the light is constantly turned on while the press button is pressed and when it is not pressed it is turned off.

### 5: Fan Control

In this project I used the fan module which controls the rotation direction and spped of the motor. This module is efficient and with high quality fan, which can put out the flame within 20cm distance.

### 6: LCD Display

With I2C communication module, this is a display module that can show 2 lines with 16 characters per line. On the back of LCD display, there is a blue potentiometer for adjusting the backlight. The communication address defaults to 0x27. The original 1602 LCD can start and run with 7 IO ports, but ours is built with Arduino IIC/I2C interface, saving 5 IO ports. Alternatively, the module comes with 4 positioning holes with a diameter of 3mm, which is convenient for you to fix on other devices.
I used this display and connected it with the push button to perform password for opening the door. Also I used to display a message: "Hello World" .


# NOTE: 
I used help from the official page for Arduino Smart House:
https://wiki.keyestudio.com/Main_Page
