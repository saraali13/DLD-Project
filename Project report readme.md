# DLD PROJECT 
# BLUETOOOTH CONTROLLED CAR USING ARDUINO

## Abstract:

The objective of our project was to design and implement a Bluetooth-controlled car using an Arduino microcontroller. 
We used digital logic design principles to create a system that allows users to wirelessly control the car’s movement via a mobile app. 
Our results demonstrate successful communication between the app and the car, allowing users to move the car forward, backward, left, and right.

## Acknowledgement:

Expressing our sincere gratitude to our course instructor for their guidance and unwavering support.
The YouTube community played a crucial role in providing step-by-step instructions, practical demonstrations, and troubleshooting tips.
Online articles, research papers, and documentation were instrumental in understanding the technical aspects.
As a team we all work together and due to our hard work and dedication we successfully designed a Bluetooth controlled car using Arduino Nano

## Introduction:

Digital logic design deals with creating circuits and systems that process digital information. It is a fundamental aspect of designing electronic systems.
In our project, we utilized this field and its principles to develop a Bluetooth-controlled car. 
By integrating hardware and software, we aimed to create a seamless connection between the car and a mobile app.
This project highlights the importance of digital logic design in modern electronic systems and showcases its application in bridging the gap between hardware and software functionalities.

## Project Overview:

#### The components of our project:
### Arduino Nano Board: 
This serves as the central processing unit for the car, receiving and executing commands sent via Bluetooth, and controlling the motors.
### Bluetooth Module (HC-05): 
This module enables remote control of the car using Bluetooth devices such as mobile phones.
### Motor Driver (L298N): 
The L298N motor driver is responsible for controlling the motors and dictating the car's movement.
### Motors: 
These integral components drive the car and determine its motion.
### Battery and Holder: 
The battery, along with its holder, provides the necessary power supply for the car's operation.

#### Connection between the mobile application and the car:
The HC-05 Bluetooth sensor allows us to establish open Bluetooth connections, allowing us to connect the Bluetooth module with our mobile application.
Upon connecting, the mobile application sends character data as input to the Arduino Nano microcontroller.
The Arduino Nano responds to the received data and executes the corresponding code, enabling the desired movement of the car based on the provided instructions.

## Design Methodology:
Establish a Bluetooth connection between the Arduino and the mobile app.
The Arduino is programmed to receive character data from the mobile app, which served as an objective during the design phase.
A prototype was developed to demonstrate Arduino-controlled LED functionality. 
This prototype showcased the basic principles of communication and control between the Arduino and external components.
Aimed to create an internet-controlled car. However, due to certain issues, an alternative method was chosen.
The design flow involves designing the circuit, connecting Arduino Nano to the other components, programming the Arduino, 
and testing the functionality to achieve the desired outcome.

## Hardware Description:

### Arduino Nano Board:
The Arduino Nano is a widely used microcontroller board, perfect for various projects, and is based on the ATmega328P chip.
Its main Functionality is to act as the central processing unit for the car, 
the Arduino Nano receives Bluetooth commands and controls the motor and other components of our car.
Arduino Nano's digital pins are connected to the motor driver (L298N) to control the motors.
While Arduino Nano's serial communication pins (TX and RX) are connected to the Bluetooth module (HC-05) for wireless communication.

### Motor Driver (L298N):
The L298N is a module that includes a dual H-bridge motor driver, allowing bidirectional control of DC motors.
Its Functions include receiving signals from the Arduino Nano and enabling the control of the motors to move forward, backward, or stop.
To connect the L298N to the Arduino Nano, use digital pins on the Arduino Nano board for motor control.
Connect the motor terminals to the output pins of the L298N.

### Bluetooth Module (HC-05):
The HC-05 is a module used for Bluetooth serial communication.
The HC-05 Bluetooth module enables wireless communication between the Arduino Nano and a mobile phone or any Bluetooth-enabled device.
Connect the HC-05 to the Arduino Nano's serial pins to establish wireless communication.
Pair the HC-05 with your mobile phone to send control commands to the car.

### Motors and Battery:
The motors serve as the propelling force for your car. Connect them to the motor driver (L298N) following the provided schematic.
Battery is used as an appropriate power source to supply energy to the motors and other components of the car.

## Software Description:

### Software Tool Used:
The Arduino Integrated Development Environment (IDE) is utilized for software-related purposes offering a user-friendly interface that facilitates the programming and management of Arduino projects.
It serves as a software tool specifically designed for writing, compiling, and uploading code to the Arduino board.
Within the Arduino IDE, there are two essential functions: void setup() and void loop().
The void setup() function is responsible for initializing variables, setting pin modes, and performing other necessary setup tasks.
On the other hand, the void loop() function runs repeatedly after the void setup() function is completed. It is commonly used to control motors, handle sensor input, facilitate communication, and carry out various other tasks until the Arduino is turned off.

### Language Used:
Arduino IDE programming uses a simplified version of C/C++.

## Result And Analysis:
The Serial Monitor is utilized for debugging code, testing concepts, and direct communication with the Arduino board.
Arduino BlueControl is an application employed for test bench results.
In the given scenario, the car moves forward with the character 'F', backward with 'B', left with 'L', right with 'R', and stops with 'S'.

## Discussion:

### Interpreting the Results:
The successful establishment of communication between the Bluetooth module (HC-05) and the Arduino-based car holds immense significance. It empowers the ability to remotely control the car using a mobile phone’s Bluetooth functionality. 
This accomplishment facilitates a convenient and wirelessly operated experience for controlling the car.

### Comparing Findings with Theoretical Expectations:
The findings align perfectly with the theoretical expectations, as there is no difference observed between them.
This indicates a successful match between the expected outcomes and the actual results.

### Challenges Faced:
Lack of a proper application for Bluetooth control.
Difficulty in motor driver pin configuration, specifically enabling pin and speed PWM pin.
Establishing a connection between Arduino and Bluetooth module and encountering errors in the code after establishing the connections.
Determining the correct Arduino receiver pin for Bluetooth TX and RX pins

### Overcoming these Challenges:
Exploring alternative app solutions to meet the requirements.
Understand the pin configuration and errors.
Identifying the appropriate receiver and transmitter pins for communication.
Debugging and troubleshooting the code thoroughly, checking for missing libraries, syntax errors, or pin configuration conflicts to resolve the errors.
By finding suitable solutions, the project progressed smoothly.

## Conclusion:

Successfully implemented Bluetooth control, enabling the car to respond to commands from a smartphone or joystick.
The car performs various movements like moving forward, backward and stopping based on Bluetooth input.
Gained experience in integrating hardware components and writing code for motor control, Bluetooth communication, and sensor integration.
Troubleshooting challenges helped us to improve our problem-solving abilities.
The car demonstrated effective wireless control using Bluetooth technology.
This project expanded our knowledge of electronics, microcontrollers, and robotics.
Consider improving the Bluetooth range by exploring different Bluetooth modules.
Optimize power consumption to extend the car's battery life.

## Future Work:
Use joysticks to provide smoother and more precise control for the car.
Adding other sensors for obstacle avoidance.
Implementing adjustable speed settings.
Develop complex movement patterns for more advanced functionality.

## Reference:
https://www.youtube.com/watch?v=V0CKi89dTcM&ab_channel=CrazyThink
https://www.youtube.com/watch?v=sXs7S048eIo&ab_channel=TinkernutLabs
https://projecthub.arduino.cc/samanfern/bluetooth-controlled-car-c71cd0
https://youtu.be/tujih1afqiE?si=JJscoY__bbGNAnmC
https://www.instructables.com/Arduino-Bluetooth-Controlled-Robot-Car-1/
