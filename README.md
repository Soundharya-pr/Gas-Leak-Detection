# Gas-Leak-Detection
This project aims to create an efficient, user-friendly system to detect hazardous gas leaks, specifically tailored for environments like hotels, restaurants, and residential spaces. Gas leaks pose severe risks, such as fires and health hazards, which this system seeks to mitigate through prompt detection and notification, significantly enhancing safety. Using a combination of sensors and a GSM notification module, this system provides real-time alerts and visual indicators to ensure quick responses, thereby preventing potential disasters associated with gas leaks.

# Project Overview
The Smart Gas Leak Detection System is an embedded solution that continuously monitors air quality to detect gas leaks. When the system senses gas above a certain threshold, it activates various alarms and notifications. The system operates on the following principles:

Early Detection: The MQ2 gas sensor continuously scans for gas presence in the surroundings.
Alert System: Upon detecting gas, the system uses visual and audible alarms, along with SMS notifications, to promptly alert individuals.
Real-Time Monitoring: A dedicated LCD display shows gas concentration levels and system status, allowing users to observe conditions at a glance.
Objective
The primary objective of this project is to quickly and accurately detect gas leaks, thus reducing fire and explosion risks in confined spaces. By deploying this system, establishments can ensure safety for occupants and minimize property damage.

# Components Used
Microcontroller: Arduino Nano
MQ2 Gas Sensor
GSM 8100L Module
LM2596 Module
LED and Buzzer
LCD Display

# Working Principle
The system continuously monitors air quality using the MQ2 gas sensor. When gas levels exceed the safety threshold, the sensor sends a signal to the Arduino Nano, which triggers.
The GSM 8100L module to send SMS notifications to pre-defined contacts.
LEDs and a buzzer to alert nearby individuals visually and audibly.
The LCD display to show gas concentration levels and alert status, allowing for real-time observation.
The system’s design emphasizes ease of deployment, stability, and user-friendly operation, ensuring that users can configure and operate it with minimal training.

# Methodology
Analysis and Component Selection: Hardware and software components are chosen based on safety requirements and operational efficiency.
Integration and Validation: The components are integrated, and thorough testing ensures the system's reliability under various conditions.
Deployment: The final design, with intuitive controls and enclosures, is ready for installation in specified environments.
