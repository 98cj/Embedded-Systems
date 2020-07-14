# Line-Following-Robot-Using-Arduino 
## Undergrad Project 1 - 3rd Semester - Nov'2016
This project shares an insight of embedded systems , how it works which IDE it uses through a simple line following robot using “Ardunio Uno” which is an open source electronic prototyping platform . 
The aim of this project is to learn about different embedded systems and learn their IDE. In this project i have a made a simple line following robot which follows a black trail until it is obstructed or  the path ends.

## Steps:

- download & install **Arduino IDE**.
- Upload a simple LED blink code on Arduino board using the cable provided with the board. 
- Create folder LFR_ARDUINO and **git clone https://github.com/98cj/Line-Following-Robot-Using-Arduino.git**
- Setup the Arduino board connections.
- Upload the code on Ardunio board and test.


## Module Specification :

#define lmotor : Defining the left motor at the very start of the program 

#define rmotor : Defining the right motor at the very start of the program 

pinMode() : Configures  the specified pin to behave either as an input or an output. See the description of digital pins for details on the functionality of the pins.

DigitalWrite(): Write a HIGH or a LOW value to a digital pin .If the pin has been configured as an output with pinMode(), its voltage will be set to the corresponding value: 5V (or 3.3V on 3.3V boards) for HIGH, 0V (ground) for LOW.

Void loop(): The loop() function does precisely what its name suggests, and loops consecutively, allowing the program to change and respond.



# Tech Stack/Resources Needed :
- Arduino Uno Board
- Ardunio IDE
- DC motors
- Photodiodes
- IR-LEDs
- Chassis and Wheels
