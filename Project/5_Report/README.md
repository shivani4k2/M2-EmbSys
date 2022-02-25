# Smart Dustbin
## Block Diagram
![Screenshot (181)](https://user-images.githubusercontent.com/85895650/155697357-5a7da131-2058-4004-8c9a-3bb491a70f2d.png)
### Ultrasonic Sensor
* An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves. An ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay back information about an object's proximity.

### Servo Motor
* Servo motor is a rotatory actuatoror linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.
### LCD Display
* A liquid-crystal display (LCD) is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals combined with polarizers. Liquid crystals do not emit light directly,[1] instead using a backlight or reflector to produce images in color or monochrome.
### Switch
* Switch is used to provide the power supply on or off.
### Battery
* A battery is an energy source consisting of one or more electrochemical cells and terminals on both ends called an anode (-) and a cathode (+). Electrochemical cells transform chemical energy into electrical energy. Inside the battery is an electrolyte, often consisting of soluble salts or acids, it serves as a conductive medium, allowing the electric charge to travel through the battery.

# Description
Smart Dustbin as its name represents it works smartly or we can say that it is an automatic dustbin. It works like when you will come in front of this dustbin it will open automatically with the help of a servo motor. So there is some sensor work to detect the object in front of the dustbin.
# Identifying Features
* It should open the lid of the dustbin whenever it senses the human hand.
* It should close the lid of the dustbin after a specified amount of time.
# State of Art
* The main focus point here is to have a dustbin which is smart enough.
* The dustbin should open and close itself automatically.
* As the world pace farward, the technology needs to catch up to the world.  
# 5W's & 1H
![WH web](https://user-images.githubusercontent.com/85895650/155673863-8c8dd929-f173-4b44-82fa-902ceb1e86df.jpg)
# SWOT Analysis
![SWOT-Analysis-Template-04-TemplateLab com_-scaled](https://user-images.githubusercontent.com/85895650/155678758-0063bc84-e86b-4b49-9a7a-f8d0a4983a82.jpg)
# Requirements
## High level requirements
| ID  | High level requirements |
| ------------- | ------------- |
| HL1  |It should automatically open the lid when detect human|
| HL2  | The bin should automatically close the lid after specified amount of time|
## Low level requirements
| ID  | Low level requirements |
| ------------- | ------------- |
| H1L1  |It opens the lid of the dustbin according to the values of ultrasonic sensor.|
| H1L2  |According to the values the micro controller receives, it orders the rely to start motion.   |
| H2L1  | It closes the lid according to the timer or the delay we give during coding.|







