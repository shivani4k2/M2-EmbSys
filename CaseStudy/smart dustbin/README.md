# Smart Dustbin

### Block Diagram
![Screenshot (181)](https://user-images.githubusercontent.com/85895650/157060332-4f22e4f7-4f40-42bf-9e7b-35ad973f318c.png)

### Sensors
* Ultrasonic sensor - An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves. An ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay back information about an object's proximity.
### Actuators
* Servo Motor - Servo motor is a rotatory actuatoror linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.
* Display - In this project we used LCD. A liquid-crystal display (LCD) is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals combined with polarizers.
### Micro Controller
* Micro Controller is the brain of the system. In this project we are using Arduino UNO,it is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino. It maps to the values sent by the ultrasonic sensor and controls the servo motor.


### High level requirements
| ID  | High level requirements |
| ------------- | ------------- |
| HL1  |It should automatically open the lid when detect human|
| HL2  | The bin should automatically close the lid after specified amount of time|
### Low level requirements
| ID  | Low level requirements |
| ------------- | ------------- |
| H1L1  |It opens the lid of the dustbin according to the values of ultrasonic sensor.|
| H1L2  |According to the values the micro controller receives, it orders the rely to start motion.   |
| H2L1  | It closes the lid according to the timer or the delay we give during coding.|

### Applications
* Can be used at home, office, amusement parks etc.
* Waste disposal and prevents odour.
* One of the home automation appliance.
* Comes under the campaign "SWATCH BHARATH".
