# Arduino Ultrasonic Radar

This is a small Arduino project that simulates a radar using a servo motor and an ultrasonic sensor.

The servo rotates left and right while the ultrasonic sensor measures the distance to objects.  
When an object is detected, LEDs and a buzzer give feedback depending on how close the object is.

## Components

- Arduino Uno
- HC-SR04 ultrasonic sensor
- Servo motor
- 2 red LEDs
- Buzzer
- Breadboard
- Resistors
- Jumper wires

## How it works

The servo motor continuously scans from 0° to 180°.  
The ultrasonic sensor measures the distance in front of it.

Depending on the distance:

- **15–10 cm** → LEDs and buzzer blink slowly
- **10–7 cm** → LEDs and buzzer blink faster
- **< 7 cm** → LEDs and buzzer stay on continuously and the servo stops

## Pins used

Ultrasonic sensor  
- Trig → Pin 9  
- Echo → Pin 10  

Servo  
- Signal → Pin 11  

LEDs  
- Pin 12  

Buzzer  
- Pin 13  

Demo Video

You can watch the demo here: https://youtu.be/ipJeJnoHg5g?is=sgujNoojCdUiAbF1
