# Smart-Home-Automation-and-Security-System-IOT

Overview

This Smart Home Automation System is designed to monitor and control various aspects of your home, including temperature, humidity, water level, and security. It utilizes various sensors and the ESP8266 Wi-Fi module to provide real-time data and control through a remote application. This system can help you maintain a comfortable and secure home environment.

Features
Temperature Monitoring: The system uses a temperature sensor to continuously measure the indoor temperature and provide real-time updates.
Fire Alert: If the temperature exceeds a predefined threshold, the system will trigger a fire alert to notify you.
Humidity Regulation: A humidity sensor is used to maintain the desired humidity level in your home.
Water Level Detection: An ultrasonic sensor is employed to monitor the water level in a container and send alerts if it overflows.
Security: A buzzer is included for security alerts or to signal various conditions.
Remote Control: The system is equipped with an ESP8266 Wi-Fi module that allows you to control and monitor datastreams from your sensors using a remote application.
Hardware Requirements
To set up this system, you will need the following components:

ESP8266 Wi-Fi module
Temperature sensor (e.g., DHT22)
Humidity sensor
Ultrasonic sensor
Buzzer
Power source
Container for water level monitoring (if applicable)
Internet connection for the ESP8266
Installation
Hardware Setup: Connect the sensors (temperature, humidity, ultrasonic) and the buzzer to the ESP8266 module as per the provided wiring diagrams.

Software Setup: You will need to program the ESP8266 module with the appropriate code. This code will read data from the sensors, monitor conditions, and send alerts if necessary. Be sure to configure your Wi-Fi credentials in the code to enable remote communication.

Remote Application: Create a remote application on your computer or mobile device to receive and display sensor data. The application should be able to connect to the ESP8266 module via Wi-Fi.

Power On: Power on the system and ensure that the ESP8266 module connects to your Wi-Fi network.

Calibration: Calibrate the sensors as needed to ensure accurate readings.

Set Thresholds: Define the temperature threshold for fire alerts and the desired humidity level for the humidity sensor.

Water Level Monitoring: If you are using the ultrasonic sensor for water level detection, set it up in a container and configure the system to send alerts when the water level is too high.

Usage
Once the system is set up, it will continuously monitor temperature, humidity, and water level. You can interact with the system through the remote application. Here's how you can use the system:

View real-time temperature and humidity data.
Receive fire alerts if the temperature exceeds the set threshold.
Monitor the water level in the container and receive alerts if it overflows.
Activate the buzzer for security alerts or specific conditions.
Troubleshooting
If you encounter issues with the system, check the following:

Ensure that all connections are secure.
Verify that the ESP8266 module is connected to the Wi-Fi network.
Calibrate sensors if readings are inaccurate.
Review the code for any programming errors.
Contributing
If you would like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request. We welcome contributions that enhance the system's functionality, usability, or security.

![Screenshot 2023-10-15 181622](https://github.com/Shivam-Verma1/Smart-Home-Automation-and-Security-System-IOT/assets/107926305/d8103ee3-ec78-4e7a-af1a-6cb82424a1c7)
![Uploading WhatsApp Image 2023-10-15 at 6.17.21 PM.jpeg…]()
