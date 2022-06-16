# RoomAccess

Description

Monitoring of total number of people present in a room. Photo electric sensor identifies a person entering a room and updates the database. If total number of people exceed the defined threshold, then an alarm notifies the personnel. If rule is being violated for quite some time then intensity of alarm increases. 

Solution

Two pairs of sensors are incorporated (combination of laser emitter and foto sensor). One sensor counts the incoming people and other one outgoing. When specific threshold is hit the alarm is turned on. If count remains same for some time and number of people remain same or is increased, intensity of alarm will increase. The second sensor is responsible for outgoing count. When count reaches below threshold the alarm stops.

Hardware

-Arduino UNO 
-Photo Sensor (2) 
-Laser Emitter (2) 
-Piezo buzzers 
-220 ohm resistor 
-470 ohm resistor 
-USB (A to B) 
-Breadboard 
-Jumper wire pack (M/M)&amp;(M/F)


Circuit Diagram


![daiagram-hamza1-01](https://user-images.githubusercontent.com/61425791/174098279-827d4b5b-ca4a-4a40-83ac-f5700f3e4887.png)
