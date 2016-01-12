# -//Brain
OSD PCB wit Sensors and usefull stuff for the FPV Rover


The Rover-Brain is complete PDB with integratetd OSD, BEC, Current Sensor, Voltage Sensor, RSSI Filter, LC Filter, and 3 Step Switch. 
It´s to keep the FPV-Rover Clean of a wire mess and to have all necessary information of your onboard system in your Video-Downlink.

I used a Mashup of the Legendary E-OSD and put some sensors and other usefull parts on one PCB. It fit´s for 2S and 3S.

The Development, Schematic and Software of the 3-Way Switch was done by JReise http://jreise.de/ (more software and Infos)
The Development, Schematic and Software of the E-OSD was done by ?? Arrgh i dont know ^^

For Setting it up You just need an USBASP to flash the OSD Firmware and the .HEX file of the AtTiny13 which is in use as an 3-Step Swicht (for flashing the pure .hex file i Use Burn-O-Mat) 
Here is the software for the attiny13: http://jreise.de/RCUSB/Daten/2-Stufen-RC-Schalter.zip  all rights by JReise !!!

For the OSD i use the G-OSD GUI which is awseome and easy to handel !



You can manually set up the Voltage Divider with the Potentiometer P1 and the output of the Currentsensor with P2, so you can easyily adjust it to exactly that value that you need.

Pinout Legend (will be countinued later):
1 = ESC1 PWM
2 =
3 = 
4 = 
5 =
6 =
7 =
8 =
9 =
10=
11=
12=
13=
14=
15=
16=
17=
18= ESC2 PWM
