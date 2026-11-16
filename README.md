# Smart Elderly Care: Real-Time Fall Detection & Alert System

## Project Overview
An IoT-based wearable fall detection prototype designed to help monitor elderly people and provide alerts when a possible fall is detected. The system uses an ADXL345 accelerometer with an ESP8266 microcontroller to identify sudden motion patterns associated with a fall. A buzzer provides a local alert, while the Blynk platform is used to send wireless notifications.

## Objectives
- Detect possible falls using accelerometer readings.
- Process sensor data using an ESP8266.
- Provide a local audible alert through a buzzer.
- Send a remote notification through Blynk.
- Operate as a portable, battery-powered prototype.

## Hardware Components
- ESP8266 development board
- ADXL345 3-axis accelerometer
- Buzzer
- Lithium-ion battery and suitable power circuitry
- Connecting wires and prototype enclosure

## Software / Platforms
- Arduino IDE
- ESP8266 board support package
- ADXL345 library (as used by your implementation)
- Blynk IoT platform

## Working Principle
1. The ADXL345 continuously measures acceleration along its X, Y, and Z axes.
2. The ESP8266 reads the sensor data and evaluates it using the fall-detection logic programmed in the firmware.
3. When the programmed conditions indicate a possible fall, the system activates the buzzer.
4. The ESP8266 uses Wi-Fi to communicate with Blynk and trigger an alert.

> The exact detection thresholds, timing window, Blynk event name, and wiring must match the implemented prototype. Document your actual values rather than using unverified example values.

## Repository Structure
- `Code/` – ESP8266 firmware
- `Circuit-Diagram/` – wiring and connection notes
- `Documentation/` – component details and test plan
- `Images/` – project photographs and screenshots
- `Results/` – measured test observations

## Setup
1. Install Arduino IDE and add ESP8266 board support.
2. Install the libraries required by your actual sketch.
3. Configure your Wi-Fi and Blynk credentials securely.
4. Connect the ADXL345 and buzzer according to your circuit.
5. Upload the sketch to the ESP8266.
6. Test the system in a controlled, safe environment.

## Important
This is an educational prototype, not a certified medical device or guaranteed emergency-response system. Do not rely on it as the sole means of fall monitoring. Never include Wi-Fi passwords, Blynk authentication tokens, or other credentials in a public repository.

## Team / Contribution
Add your team members and your exact contribution here.
