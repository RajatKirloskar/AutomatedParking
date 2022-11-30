## AutomatedParking

The automated parking system is developed using 2 Arduino Uno microcontrollers in combination with the Basic Stamp 2 microcontroller. The parking arena is connected to one Arduino Uno which transmits signals via the transmitter of NRF24L01 Wi-Fi module to the other Arduino Uno which is connected to the receiver. BS2 is connected to the second Arduino from where is receives the signal to drive to the open parking spot. 

An ultrasonic sensor is used to determine if the parking spot is open or has been taken by another vehicle. For this project, 4 parking spots are used for demonstration. Therefore 4 ultrasonic sensors are used to determine the availability of the parking spot.

Once the open parking spot is determined, BS2 sends a PWM signal to the servo motors such that the car can move and take take turns as and when necessary. The car uses a line following mechanism by taking inputs from 2 IR sensors to drive to the empty parking spot.

A Lithium-Ion 9V battery is used to power the BS2 and Arduino Uno.

Here is the pin diagram for interfacing the BS2 with the Arduino-
![image](https://user-images.githubusercontent.com/108690286/204914343-7a0ead7a-6ea4-4068-9fe6-c42037701185.png)
