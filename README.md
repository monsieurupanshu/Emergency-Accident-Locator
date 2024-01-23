# Overview
The Emergency Accident Locator (EAL) is a technologically advanced system designed to automatically detect vehicular accidents and swiftly communicate their locations to emergency services. Utilizing a combination of GPS and GSM technologies, EAL aims to reduce response times, thereby increasing the chances of survival and reducing the severity of injuries in accidents.

# Features
- Automated Detection: Utilizes sensors to detect accidents without human intervention.
- GPS Integration: Provides precise location data of the accident site.
- GSM Module: Enables real-time communication with relatives or emergency contacts by sending alert notifications.
- Rapid Response Facilitation: Speeds up the process of emergency response.
- Scalability: Adaptable to different vehicle types and environments.

# Infrastructure
## Hardware
- ARM Cortex M4 based STM32F407 Discovery Board
- GSM/GPRS Module (like SIM800A)
- GPS Module for accurate location tracking
- Ultrasonic Sensor
- MPU-9250 sensor module for motion detection
- Power supply units and backup systems
- Necessary interfacing and communication apparatus

## Software
- STM32CubeIDE for programming the microcontroller
- Embedded software for sensor data processing and decision-making logic
- Communication protocols for interfacing with GSM/GPS modules
- Software for integration with emergency response systems

# Future Plans
- The EAL system aims to enhance its capabilities by incorporating an automated call feature to connect with the nearest emergency services, like 911, especially targeting remote locations. This enhancement will leverage advanced location-based services to determine the closest emergency response team, ensuring even quicker and more efficient aid in critical situations.
