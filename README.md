# Smart Rescue Badge for women safety
## An innovative approach to women safety.

### Team name: Echo-Effect
### Team members:
    Member 1: THEERTHA R
    Member 2: SWATHY V
    Member 3: ANUPAMA P
    
### Project description:
A Rescue Badge for Women Safety is an innovative mini-project concept aimed at enhancing women's safety in emergency situations. This wearable device, often in the form of a badge, pendant, or wearable accessory, can send distress signals.

### The problem statement:
In 2021, there were over 428,278 reported incidents of women abuse. There lacks a fast accessible mechanism to alert on the necessary personnel which can help in accessing undelayed response which can save many!!

### The solution:
To provide a reliable and affordable access to safety. Smart Footwear is userfriendlywhich is lightweight and portable. Timely actions can result in impactful alerts.

## Technical details

### Technologies/Components Used

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

### Working
- The user presses the panic touch in an emergency in a touch sensor.
- The microcontroller reads the input signal and activates the rescue mechanism.
- Notification is sent using Telegram bot 'Echo_Effect_bot' once the touch sensor is touched 3 times simultaneously.
- A distress message like "HELP! Touch sensor triggered three times" in telegram bot and 'Sending HELP!' message through blynk IOT app.

### Photos and videos
Video and Images of our project is given
https://drive.google.com/drive/folders/1ANogSmYQPLPjxc9ufg-RlQUS6agUsClL

### Screenshots
![Screenshot (4)](https://github.com/user-attachments/assets/d95a8d62-0a80-4066-9eb2-51ac088b78cd)

![Screenshot (5)](https://github.com/user-attachments/assets/ff32e1ef-0155-46e8-b780-df63edd3d35b)

![Screenshot (6)](https://github.com/user-attachments/assets/cb81d1ab-03a1-4450-aa8f-040722689ba7)

![Screenshot (7)](https://github.com/user-attachments/assets/dd3b083a-d798-4557-93b8-d835c1245a28)

![Screenshot (8)](https://github.com/user-attachments/assets/ad2ec406-f118-42a7-93a2-f8c67dc49035)

### Build Photos

![WhatsApp Image 2025-01-26 at 11 51 36_484caec9](https://github.com/user-attachments/assets/b1353fde-1188-46e2-9f81-37393ebc15c9)

### Team Contributions
- Theertha R - Blynk IOT
- Swathy V - Telegram Bot
- Anupama P - ESP8266 codes
