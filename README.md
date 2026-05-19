# SafeSense

## Overview
SafeSense is an Arduino-based safety system developed during the UCL Robotics & AI Crash Course, where the project was awarded first place.

The system uses vibration and temperature sensors to detect possible earthquake activity and fire risks in real time. Depending on the hazard detected, the LCD display shows different emergency instructions to help users respond quickly and safely.

## Features
- Real-time hazard monitoring
- Earthquake detection using a vibration sensor
- Fire risk detection using a temperature sensor
- LCD safety alerts
- Detection of combined hazard conditions
- Expandable system design

## Technologies Used
- Arduino Uno
- C++
- LCD display
- Temperature sensor
- Vibration sensor

## How It Works
The system continuously reads data from the vibration and temperature sensors.

The Arduino processes this data and determines whether:
- earthquake activity is detected
- fire risk is detected
- both hazards are detected together

The LCD display then updates with different safety messages depending on the situation.

Examples:
- Earthquake → "Drop & Cover"
- Fire Risk → "Evacuate Calmly"
- Combined Hazard → "Critical Alert"

## Challenges
One challenge was making sure the temperature sensor was sensitive enough to detect hazards without causing too many false alarms. We also worked on combining multiple sensor conditions into one real-time response system.

## What I Learned
Through this project I developed experience in:
- sensor integration
- Arduino programming
- embedded systems
- debugging and testing
- real-time monitoring systems
- teamwork and collaborative problem solving

## Project Images
Project images are included in the images folder.

## Presentation
The full presentation is included in the presentation folder.
