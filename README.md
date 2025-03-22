# Voice-Controlled-Robot-Car-Using-Arduino-Bluetooth-and-L293D-Motor-Driver
This project demonstrates how to control a robot car using voice commands via Bluetooth. The system consists of an Arduino Uno, an HC-05 Bluetooth module, an L293D motor driver, and two DC motors. The user can send voice commands such as "forward", "backward", "left", "right", and "stop" to control the car.

Components Required
Arduino Uno

HC-05 Bluetooth Module

L293D Motor Driver Module

2 DC Motors

2 9V Batteries

Jumper Wires

Circuit Diagram

Working Principle
The HC-05 Bluetooth module receives voice commands from an Android app.

The Arduino reads the incoming command via the Serial communication.

Based on the received command, the Arduino sets the corresponding motor driver pins HIGH or LOW.

The L293D motor driver controls the two DC motors accordingly.

Motor Control Logic:

"forward": Both motors move forward.

"backward": Both motors move backward.

"left": Left motor stops, right motor moves forward.

"right": Right motor stops, left motor moves forward.

"stop": Both motors stop.

How to Use
Connect all components as per the circuit diagram.

Upload the Arduino code.

Pair your phone with the HC-05 module using a Bluetooth terminal app.

Send commands (forward, backward, left, right, stop) via the app.

The robot moves accordingly.

[Jitendra Sharma] (GitHub: https://github.com/jitendrasharma-eng/Voice-Controlled-Robot-Car-Using-Arduino-Bluetooth-and-L293D-Motor-Driver.git)
