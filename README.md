# Automated-valet-parking-system

## Brief Description
Nowadays, finding a parking is really a tough job and little expensive too for an average earning person. So we have modified the existing model of automated parking system to make it cost effective. For making the implementation cost less , we have designed our parking model that will obviously make the parking charges less and will lead to the revolution in the parking world.

We have divided our parking in two parts- Left part is a kind of individual parking system where all the slots needs to be implemented with sensors to manage the data . In the model that is on Right side, we will be dividing the whole parking into some subparking areas and we willl be  monitoring the cars coming in and out at entry level of that subparking. In this model the requirement of sensors will be less ,which will obviously reduce the implement charges.
 
 

## Hardware used
* Arduino Uno 
* 20×4 LCD Display 
* I2C LCD Module 
* Male Header  
* 7 IR Sensors 
* 2 Mini Servo Motor SG-90 
* Female DC Power Jack  

## Software/Simulator Used
* ArduinoIDE  
* Proteus 8 

## Process flow
* Start the system by connecting to the power supply. 
* Move the car inside the parking through main entrance .
* First sensor at the entrance senses the car and opens the gate , the next sensor senses and closes the gate .
 * Total number of slots decreases.
* If car moves in left , sensor at each parking slot senses and update the slot from empty to fill on display. 
* If car moves in right side , first sensor at subparking entrance senses and opens the gate and the slot in subparking area decreases.The next sensor senses the car     and closes the gate.
* When avail in subparking area is 0 , the sensor after sensing displays no place on the screen 
* When the total slot is 0 , and when car comes in front of the first sensor , it senses and displays "Sorry Parking Full" on the display. 
* And then the car starts to come out and slot gets increses upto to its limit.
