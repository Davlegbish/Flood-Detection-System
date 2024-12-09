# Flood-Detection-System Using Ardiuno
This is my final year project at Afebabalola University IOT Early Flood Detection System Using Arduino is an intelligent system that maintains a careful eye on many natural characteristics to predict a flood, so we may embrace caution ,and prevent the damage caused by the flood. Natural disasters, such as flooding, may cause extensive property damage and loss of life. The method uses several natural elements to 
detect floods in order to prevent or mitigate their effects. Because the system includes a Wi-Fi connection, its discovered data may be retrieved from anywhere pretty easily via IOT.To detect a flood the system observes various natural factors, which includes humidity, temperature, and water level and flow level. To collect data of mentioned natural factors the system consists of different sensors which collects data for individual parameters, for detecting water level using water level sensor.

# EQIUPNMENT USED

1. Arduino Uno : The ATmega328P-based Arduino UNO is a microcontroller board. It contains 14 
digital I/O pins (of which 6 may be used as PWM outputs), 6 analog inputs, a ceramic resonator operating at 16 MHz, a USB connection, a power connector, an ICSP 
header, and a reset button.

2. Water level Sensor : The water level sensor is a device that detects excessively high or low liquid levels in a fixed container.

3. SIM900 : The SIM900 GSM/GPRS shield is a GSM modem that may be used in a number of Internet of Things applications. This shield allows you to do practically everything a standard mobile phone can do, such as sending SMS messages, making phone calls, connecting to the Internet through GPRS, and much more.

4. 16x2 LCD display : LCD 16x2 refers to Liquid Crystal Display, which uses plane panel display technology and is used in computer monitors and TVs, smartphones, tablets, mobile devices.

5. Breadboard : A breadboard a board on which to prototype or develop circuits. It enables you to arrange components and connections on the board in order to construct circuits without the need for soldering.

6. Jumper Wires : Jumper wires are basic cables with connecting points on each end that may be used to link two locations without soldering.

 
# FLOW CHART


![image](https://github.com/user-attachments/assets/8edab92d-01ba-4b32-9686-d42af09fd307)


# Operating Principal of IOT Early Flood detection system using Arduino

Division of project in different modulus

1)	Information gathering stage
2)	Processing stage
3)	Transmission stage
4)	Notification stage

A.	Information gathering stage
This stage involves the use of the water level sensor to collect the reading of the three-water levels.
•	Water level above 80% (HIGH)
•	Water level above 50% (MEDIUM)
•	Water level below 50% (LOW)

B.	Processing stage
This stage involves the processing of the data gotten from the water level sensor with the application of Arduino uno.

C.	Transmission stage
At this stage the data processed by the application of the Arduino, will be transmitted to the 16x2 LCD display which will display the three water level (HIGH),(MEDIUM) and (LOW) as well as the SIM900.

D.	Notification stage
This stage involves the use of SIM900 to notify the three- water levels (HIGH), (MEDIUM) and (LOW) which will notify in form of text message (SMS) and call.

