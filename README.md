# SafeSense

## Overview
SafeSense is an Arduino-based multi-hazard detection system developed during the UCL Robotics & AI Crash Course, where the project was awarded first place.

The system monitors environmental conditions in real time using vibration and temperature sensors to detect earthquake activity and fire risks. It displays clear emergency instructions through an LCD interface to help users respond quickly and safely during emergencies.

## Features
- Real-time hazard monitoring
- Earthquake detection using vibration sensors
- Fire risk detection using temperature sensors
- Dual-condition emergency alerts
- LCD safety instruction display
- Modular and expandable system design

## Technologies Used
- Arduino Uno
- C++
- LCD display
- Temperature sensor
- Vibration sensor
- Embedded systems logic

## How It Works
The system continuously reads data from:
- a vibration sensor for earthquake activity
- a temperature sensor for fire risks

The Arduino processes the sensor data in real time and determines:
- earthquake risk
- fire risk
- combined critical hazard conditions

The LCD display updates based on the detected hazard condition, providing users with immediate safety instructions.

Examples:
- Earthquake → "Drop & Cover"
- Fire Risk → "Evacuate Calmly"
- Combined Hazard → "Critical Alert"

## Challenges
One challenge was balancing temperature sensor sensitivity while reducing false alarms as the threshold of the temperature which was initially too high. We also worked on integrating multiple sensor conditions into a single real-time response system.

## What I Learned
Through this project I developed experience in:
- embedded systems
- sensor integration
- Arduino programming
- real-time monitoring systems
- debugging and testing
- collaborative engineering
  
## Project Images
The full project images are included in the images folder.

## Presentation
The full project presentation is included in the presentation folder.
