# Smart Dustbin

## 1. About Smart Dustbin
### 1.1 Description
Smart Dustbin as its name represents it works smartly or we can say that it is an automatic dustbin. It works like when you will come in front of this dustbin it will open automatically with the help of a servo motor. So there is some sensor work to detect the object in front of the dustbin.
### 1.2 Identifying features
* It should open the lid of the dustbin whenever it senses the human hand.
* It should close the lid of the dustbin after a specified amount of time.
### 1.3 State of Art
* The main focus point here is to have a dustbin which is smart enough.
* The dustbin should open and close itself automatically.
* As the world pace farward, the technology needs to catch up to the world. 
### 1.4 5W's&1H
![WH web](https://user-images.githubusercontent.com/85895650/155673863-8c8dd929-f173-4b44-82fa-902ceb1e86df.jpg)
### 1.5 SWOT Analysis
![SWOT-Analysis-Template-04-TemplateLab com_-scaled](https://user-images.githubusercontent.com/85895650/155678758-0063bc84-e86b-4b49-9a7a-f8d0a4983a82.jpg)

## 2.Requirements
### 2.1 High level requirements
| ID  | High level requirements |
| ------------- | ------------- |
| HL1  |It should automatically open the lid when detect human|
| HL2  | The bin should automatically close the lid after specified amount of time|
### 2.2 Low level requirements
| ID  | Low level requirements |
| ------------- | ------------- |
| H1L1  |It opens the lid of the dustbin according to the values of ultrasonic sensor.|
| H1L2  |According to the values the micro controller receives, it orders the rely to start motion.   |
| H2L1  | It closes the lid according to the timer or the delay we give during coding.|


## 3.Block Diagram and Blocks Explanation
### 3.1 Block Diagram
![Screenshot (181)](https://user-images.githubusercontent.com/85895650/157060332-4f22e4f7-4f40-42bf-9e7b-35ad973f318c.png)
### 3.2 Sensors
* Ultrasonic sensor - An ultrasonic sensor is an instrument that measures the distance to an object using ultrasonic sound waves. An ultrasonic sensor uses a transducer to send and receive ultrasonic pulses that relay back information about an object's proximity.
### 3.3 Actuators
* Servo Motor - Servo motor is a rotatory actuatoror linear actuator that allows for precise control of angular or linear position, velocity and acceleration. It consists of a suitable motor coupled to a sensor for position feedback.
* Display - In this project we used LCD. A liquid-crystal display (LCD) is a flat-panel display or other electronically modulated optical device that uses the light-modulating properties of liquid crystals combined with polarizers.
### 3.4 Micro Controller
* Micro Controller is the brain of the system. In this project we are using Arduino UNO,it is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino. It maps to the values sent by the ultrasonic sensor and controls the servo motor.

## 4.Architecture
### 4.1 Behavioural Diagram
#### 4.1.1 High level flowchart behavioural diagram
![high](https://user-images.githubusercontent.com/85895650/157006887-8967c43b-fb41-4e2c-a973-370e97d7284a.png)
#### 4.1.2 Low level flowchart behavioural diagram
![low](https://user-images.githubusercontent.com/85895650/157006902-542e9a9e-866e-4bf9-9d9a-a5055846d070.png)

## 5.Test Plan and Output
### 5.1 Test Plan
|Test ID|Description|Input|Expected Output|Actual Output|Passed or Not|
|------|-------------|--------------|-------|---------|---------|
|01|Ultrasonic Sensor|27cm(set)|Send 1 to micro controller|Sending 1 to micro controller|✅|
|02|Servo Motor|160 degrees(set)|Rotate on receiving data from micro controller|Rotate on receiving data from micro controller|✅|
### 5.2 Output
* Servo motor(OFF) with no human

![Screenshot (188)](https://user-images.githubusercontent.com/85895650/157021478-7788bbd2-1057-4830-8332-f2a579a526b4.png)
* Servo motor(ON) on detecting the human

![Screenshot (189)](https://user-images.githubusercontent.com/85895650/157021493-3f3de725-c1b5-4dc1-8c02-8ef82be9fcbb.png)

## 6. Application
* Can be used at home, office, amusement parks etc.
* Waste disposal and prevents odour.
* One of the home automation appliance.
* Comes under the campaign "SWATCH BHARATH".




