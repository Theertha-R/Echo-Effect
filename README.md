# Smart  for women safety
## An innovative approach to women safety.

### Team name: Echo-Effect
### Team members:
    Member 1: THEERTHA R
    Member 2: SWATHY V
    Member 3: ANUPAMA P
    
### Project description:
The project emphasizes on women safety by providing a wearable footwear as safety equipment. On giving continuous 3 taps on the footwear while in danger can give notification alert to the contacts presaved.

### The problem statement:
In 2021, there were over 428,278 reported incidents of women abuse. There lacks a fast accessible mechanism to alert on the necessary personnel which can help in accessing undelayed response which can save many!!

### The solution:
To provide a reliable and affordable access to safety. Smart Footwear is userfriendlywhich is lightweight and portable. Timely actions can result in impactful alerts.

Technical details

Technologies/Components Used

For Software:
Languages Used:C++ Arduino IDE (Programming the ESP8266)
Frameworks Used:

Arduino Framework (for microcontroller programming)
Blynk IoT Platform (for remote monitoring and control, like displaying data on an LCD widget)
Libraries Used:

ESP8266WiFi.h (for managing Wi-Fi connections)
WiFiClientSecure.h (for secure HTTPS requests to Telegram API)
BlynkSimpleEsp8266.h (for interfacing with Blynk IoT platform)
TinyGPS++.h (for parsing GPS data such as latitude, longitude, speed, etc.)
SoftwareSerial.h (for creating software-based serial communication between the ESP8266 and GPS module)
Arduino Timer Library (used for scheduling tasks like checking the touch sensor)
Tools Used:

Arduino IDE (for writing and uploading the code to ESP8266)
Telegram Bot (to handle communication and send messages)
Blynk App (for IoT dashboard and visualization)
Serial Monitor (for debugging and testing the GPS output)
For Hardware:
Main Components:

ESP8266 NodeMCU (microcontroller for Wi-Fi connectivity and processing)
GY-GPS6MV2 Module (GPS module to fetch latitude and longitude)
Touch Sensor Module (to trigger the alert message, e.g., TTP223 capacitive touch sensor)
Specifications:

ESP8266 NodeMCU:
Operating Voltage: 3.3V
Built-in Wi-Fi module
Flash memory: 4MB
GY-GPS6MV2 Module:
Operating Voltage: 3.3V/5V
Baud Rate: 9600 bps
Protocol: NMEA (to send GPS coordinates)
Touch Sensor (e.g., TTP223):
Operating Voltage: 3.3V–5V
Output: Digital (HIGH or LOW)
Tools Required:

USB Cable (for programming and powering the ESP8266)
Breadboard (for prototyping and connections)
Jumper Wires (for wiring the components together)
