# Smart Dustbin (Ultrasonic + Servo)

An Arduino-based smart dustbin that opens its lid automatically when something comes close, using an ultrasonic sensor and a servo motor.

## How it works

1. The HC-SR04 ultrasonic sensor measures the distance in front of the bin.
2. If an object is within 20 cm, the servo turns to 90 degrees and the lid opens.
3. When nothing is detected, the servo returns to 0 degrees and the lid closes.
4. The measured distance is printed on the Serial Monitor.

## Hardware used

- Arduino board
- HC-SR04 ultrasonic sensor
- Servo motor
- Jumper wires and a power supply

## Pin connections

- Trigger pin: 9
- Echo pin: 10
- Servo signal pin: 11

## How to run

1. Open the .ino file in the Arduino IDE.
2. Connect your Arduino board to the computer.
3. Select the correct board and port in the Tools menu.
4. Click Upload.

## Author

Papun Behera
