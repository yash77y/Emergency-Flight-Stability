# Emergency-Flight-Stability
An embedded systems project that simulates an aircraft’s automatic stability correction mechanism using Arduino.
The system detects tilt conditions and performs corrective action through a servo motor acting as a rudder,
while displaying real-time system status on an LCD.

Overview-
This project demonstrates how sensor input can be processed with decision logic to control actuators in real time.
A potentiometer is used to simulate aircraft tilt. Based on predefined thresholds,
the system detects left/right deviation and corrects it automatically.

Components Used-
Arduino Uno,
Potentiometer (tilt input simulation),
Servo Motor (rudder control),
DC Motor (propulsion simulation),
16x2 I2C LCD Display,
Breadboard and jumper wires,
Switch.

Working Principle-
The potentiometer provides analog input representing tilt,
If the tilt crosses safe limits, the Arduino triggers corrective rudder movement using a servo motor,
A DC motor turns on when the system is powered.

The LCD displays real-time status:
Power Off,
System Stable,
Tilting Left / Correcting Left,
Tilting Right / Correcting Right.

Logic Flow-
Sensor Input → Threshold Decision Logic → Actuator Control → Status Display

Applications-
Basic demonstration of aircraft stability concepts,
Embedded systems learning,
Sensor–actuator interfacing practice,
Real-time control logic implementation.

Here the video link to the project-
https://youtu.be/roX8tC0vCZs

Author-
Yash Salvi
