# Embedded_Microcontroller_Projects_X6
A repository containing 6 embedded projects developed on microcontrollers like an Arduino

1) Obstacle Avoidance Robot
![image](https://user-images.githubusercontent.com/82429124/211691933-70f1f399-7b69-4bdb-a973-cd891682f069.png)

 - This rover had an ultrasonic sensor (HC-SRO4) mounted onto it that allows it to detect obstacles in its path. 
- Upon meeting an obstacle, a servo motor rotates the sensor left and right. 
- If the sensor detects more space to the right of it, the Arduino tells the DC motors to move the rover to the left and vice versa. 
- This project allowed me to deal with construction, assembly, and wiring electrical connections with the Arduino and power source. It also involved some coding of which some are based on sound equations pulled from my physics courses.
- Video demo: https://www.youtube.com/watch?v=oGSny03s_TQ


2) Line Following Rover
![IMG_8945](https://user-images.githubusercontent.com/82429124/211692998-5f6725e5-f031-4b34-bff7-e7b32b0a3846.jpg)

This project consisted of creating an autonomous rover that would follow a line of tape on the ground. 
- Aside from the Arduino, the build consisted of 2 DC motors, an L293D motor driver, 2 power supplies, 2 QRD1114 sensors, 2 LEDs, several resistors (for the sensors and the LEDs). 
- Besides  following the line in straight lines, inclines and curves, there was also an LED atop each motor that would turn on if the motor below it was set to high power. 
Video Demo: https://www.youtube.com/watch?v=JziQ5z3_72w&ab_channel=MatthewGerges


3) Arduino Smart Home Devices
![image](https://user-images.githubusercontent.com/82429124/211693599-2d35bd56-51f5-4464-8398-f668edb7f130.png)

I created several versions of an automated light switch which were used to turn lights on an off via bluetooth and by clapping your hands twice. This is an earlier design of the project that used a potentiometer to turn the light on and off:  https://www.youtube.com/embed/mjeSwUrdcSE?feature=oembed

I also designed an RFID card reader to lock and unlock a 12 V solenoid. 
The lock was later placed on a cookie jar to prevent younger siblings from stealing my desserts:
https://www.youtube.com/watch?v=V4sLJYhIMZU

4) Jonah's Fast Creative Challenge
![image](https://user-images.githubusercontent.com/82429124/211693829-f9635330-526f-4c83-93ee-8aeef523881c.png)

This was a competition I won where I was challenged to make a creative project that revolved around the theme of Jonah's fast. The cross in the video is connected to a string that is glued to a power switch. When the string is pulled, the motor driver (connected to the switch) is turned on. This sends a signal to the motor which starts reeling in a string connected to a picture of Jonah much like an electric fishing rod. Video Demo: https://youtu.be/wDUipA_racA.

5) Electrical Longboard Build
![image](https://user-images.githubusercontent.com/82429124/211693540-d41aeb42-501a-4d51-90b7-c4c1ced20fef.png)

This project consists of several electronic components I attached to the base of a non-electric board I already owned. I mounted brushless dc motors onto the frame and connected them to a speed controller. The speed controller varies the resistance of the battery's voltage connected to it. The higher speed set on the controller, the lower the resistance and vice versa. I enjoyed the final product of this build particularly because I got to ride the longboard at high speeds. I also learnt a lot about circuitry, power, and batteries. However, during this project, I overcame unexpected obstacles such as dealing with a weak battery. I solved this challenge by disassembling my old hoverboard from which I took the Li-ion battery and buying new connectors for it.

6) Robotic Arm
![image](https://user-images.githubusercontent.com/82429124/211693964-d2e61598-cdd8-4612-be82-2c8f108d8dc8.png)

This project used several servo motors and potentiometers to pick up objects and move them from one location to another in the same way a mechanical crane would. In this design, the degree of rotation of the potentiometers determined the angle to which its respective servo motor would be set.
Video Demo: https://youtu.be/pG5s-Y0MxR0
