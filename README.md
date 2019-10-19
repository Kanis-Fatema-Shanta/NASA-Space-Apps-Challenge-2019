# NASA-Space-Apps-Challenge-2019
Smart Garbage Bin


Introduction: 
 Most of the cities, towns and villages in Bangladesh are not well designed to facilitate the suitable garbage collection methodsCommon Public dustbins are filling over with the garbage and no one is concerned to clear them up as and when they get completely packed with overflowing garbage.Keeping in view of this big problem, it will be a good suggestion to do something to deal with this unmanaged waste and from this, the concept of ‘Smart Dustbin’ came out.
Objectives
To design a “Smart Dustbin” which is a GSM enabled bin which automatically detects the garbage level and sends message to respective municipal authorities updating the status of the bin.

Background:
The main concept behind the Smart Dustbin using Arduino project is Object Detection. I have already used Ultrasonic Sensor in Object Avoiding Robot, where upon detecting an object, the Robot will change its course of direction.
A similar methodology is implemented here, where the Ultrasonic Sensor is placed on top of the dustbin’s lid and when the sensor detects any object like a human hand, it will trigger Arduino to open the lid.


Smart Dustbin- 

steps:
1. Take Arduino uno, Ultrasonic sensor, servo motor, Jumper wires, 9v battery and dustbin box.
2. Connect servo motor yellow pin(signal pin) to Arduino digital pin no. 9
3. Connect servo +Vcc pin to Arduino +5V pin.
4. Connect servo GND pin to Arduino GND pin.
5. Take Ultrasonic sensor connect sensor TRIG pin to Arduino pin no. 2.
6. Connect sensor ECHO pin to Arduino pin no. 3.
7. Connect servo at the top of Dustbin with the help of glue gun.
8. Connect washer and thread to the dustbin box.
9. Make a hole infront of dustbin box and fit ultrasonic sensor as shown in image.
10. Upload the code.
11. Power the Arduino with a 9V battery.






Case-1 :➢ When any object comes close to the sensing area, the lid will open automatically.
 
Case 2 :➢ When a dustbin gets full, a message will be sent to the municipal corporation.



We use NASA data set here: Logistic Reduction:Universal waste Management system.

 



