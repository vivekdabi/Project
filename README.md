# Project
surveillance camera car using the ESP32-CAM  module

The aim of this project is to design and implement a surveillance camera car 
using the ESP32-CAM module, which can stream live video to a web browser 
over a wireless network and move in multiple directions using motor control. The 
goal is to provide a low-cost, wireless, and flexible surveillance solution for 
monitoring purposes in various scenarios, such as security, exploration, or 
monitoring of hazardous areas. The project will focus on integrating the ESP32
CAM with motor control systems, enabling users to control both video streaming 
and the movement of the vehicle via a web interface.


 Components Used 
2.1 ESP32-CAM Module (1) 
The ESP32-CAM module is a low-cost board that integrates the ESP32 
microcontroller and a 2MP camera. The module is capable of running a small 
web server and can stream video over Wi-Fi. It supports Bluetooth and Wi-Fi, 
making it ideal for IoT applications. It also provides multiple I/O pins for 
connecting to external peripherals such as motor drivers and sensors. 
2.2 Motor Driver Module (L298N) (1) 
The L298N motor driver is used to control the two DC motors that drive the 
wheels of the car. It can control the direction and speed of the motors using the 
input signals from the ESP32-CAM. The L298N is an H-Bridge motor driver, 
which allows for forward, reverse, and turning motions. 
2.3 DC Motors with Wheels (4) 
Two set of DC motors are used to power the car's movement. These motors are 
connected to the motor driver and are responsible for moving the car in different 
directions. They are mounted on the chassis with wheels attached to provide 
mobility. 
2.4 Chassis (1) 
A chassis is used as the physical base or frame to mount all the components of 
the project. It holds the motors, the ESP32-CAM module, the battery, and the 
motor driver in place. The chassis can be made from materials like plastic, metal, 
or wood. 
2.5 Li-ion Battery Pack (1) 
The 18650 Li-ion battery pack provides the necessary power to the entire 
system. It is rechargeable, making it efficient for long-term use. The battery is 
connected to the ESP32-CAM module, the motor driver, and the motors to ensure 
continuous operation. 
2.6 Jumper Wires 
Jumper wires are used for connecting different components on the breadboard or 
directly to the ESP32-CAM module and motor driver. 
2.7 Breadboard / PCB (1) 
A breadboard is used for organizing the circuit connections in a neat and non
permanent way. If needed, a printed circuit board (PCB) can be used for more 
permanent and organized connections. 

Key Connections: 
 ESP32-CAM → Motor Driver (L298N) 
o GPIO pins from the ESP32-CAM are connected to the IN1, IN2, 
IN3, and IN4 pins of the motor driver to control motor directions. 
o The motor driver receives the power from the Li-ion battery to drive 
the motors. 
 ESP32-CAM → Power 
o The 5V output from the Li-ion battery pack is connected to the 5V 
pin of the ESP32-CAM to provide necessary power for both the 
board and the camera. 
 DC Motors → Motor Driver 
o Each motor is connected to the motor driver’s output pins (OUT1, 
OUT2, OUT3, OUT4) to control movement direction and speed. 
 Optional: Voltage Regulator 
o A voltage regulator is used to ensure that the ESP32-CAM receives 
a stable 5V power supply.

<img width="682" height="676" alt="image" src="https://github.com/user-attachments/assets/9d537f5b-4159-4f2d-b05d-ec1a42c60952" />




