I have made an Electrnic voting machine using the microcontroller AT 89C51 from the 8051 family.

image

It consists of two parts: Software and Hardware.

Components:

8051 microcontroller- AT89S52
USB ISP Programmer
16x2 LCD
Push Buttons
Connecting wires
Breadboard
NodeMcu
Proteus software
ProgISP software
Software used are:

Keil Microvision: to write and run your code. Proteus: to make and simulate circuit

Steps to be followed for software are:

1- Write your Bluetooth code in your KEIL software. Make sure to select the AT89C51 microcontroller.

2- Save it as .c file

3- Run, build and translate your code to make sure all the errors have been removedand and the code works fine.

4- The .c file can't be directly fed into the micrcontroller. Only .HEX files can be loaded. So, convert your .c file into .HEX (Fefer any youtube video)

5- Now open your proteus and import the model from the downloaded folder.

6- Some of the components used might not have it's library pre-installed in your proteus. So make sure to download the nexessary libraries from https://www.theengineeringprojects.com

7- Double click on your micrcontroller and add the .HEX file

8- Click on run

The hardware part is made with the help of Node MCU.
