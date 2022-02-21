  # Parking System


### Block Diagram
![block diagram (2)](https://user-images.githubusercontent.com/85895650/154804668-5a9ce390-2ced-49ad-895c-5ec3fb5576ad.png)

* Ultrasonic sensor - It is used to sense the car and update the microcontroller that a car has arrived.
* LCD Display - It is used to display the number of empty or filled parking slots.
* Servo motor - It is used for opening and closing of gate at the entrance and exit of parking slot.
* IR sensor - It is used to detect the presence of car in the parking slot and update it to the microcontroller.
* Camera - It is used to take picture of the number plate of the car.
* Wifi module - It is used to send the captured number plate data to the cloud.
* Buzzer - It is used to indicate the driver that the car is not parked properly.

### High level requirements

| ID  | High level requirements |
| ------------- | ------------- |
| HL1  |Detecting the vehicle|
| HL2  | Storing the data  |
| HL3  | Detecting the number of vacant slots |

### Low level requirements

| ID  | Low level requirements |
| ------------- | ------------- |
| H1L1  |vehicle detection using ultrasonic sensor|
| H2L1  | Storing the data into cloud  |
| H3L1  | Vacant slots detection using IR sensors |

### Applications
* Free parking space can improve the traffic situation in cities.
* Optimized usage of parking lot space.
