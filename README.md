# Proposal


# Walking & Dancing Robot Reacting to Proximity Sensors

I propose to build a dancing, walking robot that is activated due to proximity. 

## Summary

The dancing robot is a simple figure constructed out of 2 micro servos per leg. 
The robot will be instructed to 'dance' and 'walk' according to proximity (10 inches). Once a the robot is activated to dance, LED lights will blink to indicate proximity. 

The main goal of this project is to explore a new components and sensors in programming as well as create a working Robot with Arduino. The main function of the robot will be as entertainment. People will interact with the device by placing their hands within the sensor range (10 inches). 


## Component Parts

-Micro Servo or any other (x4)
-Breadboard
-Thin sheet wood (2 pieces measuring 6.2 x 4.6 cm). 
-Cardboard (small pieces for feet).

Proximity Sensor:
- 1 IR LED receiver 
- IR LED emitters (at least 2)
- 100K resistor 
- Jumper wires
- Electrical tape
- Buzzer(MAYBE)


On the software side, there's a web page that shows you the power consumption over time of whatever is plugged in to your outlet, and allows you to remotely turn on or off the power to whatever is plugged in. This software will have a few main components:
- A database, to store reported current usage data. (DATA)
- A user login system, to uniquely identify people coming to the site and connect to the correct devices. (DATA)
- A graphing system, to draw out historical power usage data. (OUTPUT)
- A few buttons to control the on/off state of the devices. (INPUT)

### Block Diagram

![Dancing Robot Diagram](img/new doc 2018-04-18 22.31.07_1.png)

## Challenges

I anticipate trying to create a proximity sensor as challenging as I have never used one before. 
I also anticipate trying to create the right circuit to make the robots legs move as challenging as this would need to be done very accurately in order to make sure they move at the same time. 
I will also try to not mix up the LED receiver with the LED emitter, as they all look the same.

## Timeline
 -Week 2: Order components 
- Week 3: Build a first version of the software that displays current power usage and an on/off switch.
- Week 4: Integrate all the components together and debug.
- Week 5: Present complete project.
