Smart Glove for Deaf and Dumb People

Gesture to Speech and Text Conversion System

?? Project Overview
Communication is a fundamental human need, yet deaf-mute, paralyzed, and bedridden individuals often struggle to express their basic requirements.  
This project presents a Smart Gesture Recognition Glove that converts hand gestures into real-time text and voice messages using wearable sensors and Bluetooth communication.

The system enables users to communicate essential needs such as water, food, medicine, help,etc., through simple finger movements and wrist tilts.

?? Aim
To design a low-cost, portable wearable glove that detects hand gestures using sensors, processes them using a microcontroller, and converts them into meaningful speech and text output  on a smartphone.

 ? Objectives
- Detect finger bending using flex sensors
- Detect wrist tilt using MEMS accelerometer (ADXL)
- Convert sensor data into predefined digital commands
- Transmit messages wirelessly via HC-05 Bluetooth
- Enable speech and text output on a mobile device

 ?? Working Principle
- Flex Sensors detect finger bending by change in resistance
- MEMS Accelerometer  detects wrist orientation (X, Y, Z axes)
- Arduino converts analog values into binary logic
- Each combination of finger bends represents a predefined message
- Bluetooth module sends message to smartphone
- Mobile app converts text into speech

Gesture Mapping Example
 Flex Combination | Output Message |

| 000 | I Need Help |
| 001 | I Want Water |
| 010 | I Want Food |
| 011 | I Want Medicine |
| 100 | I Want Coffee |
| 101 | I Want Bedsheet |
| 110 | I Want Washroom |
| 111 | I Want To Go Out |

?? Hardware Components
- Arduino Nano / Arduino Uno
- Flex Sensors (3)
- MEMS Accelerometer (ADXL335 / ADXL345)
- HC-05 Bluetooth Module
- LED Indicator
- 9V Battery
- Hand Glove
- Connecting wires & breadboard

 ?? Software Tools
- Arduino IDE (Embedded C)
- Proteus / TinkerCAD (Simulation)
- Android Bluetooth Text-to-Speech App


?? Simulation & Testing
- Individual calibration of flex sensors
- Proteus simulation of Arduino and Bluetooth communication
- Real-time testing using glove gestures
- Successful Bluetooth communication up to ~10 meters
- Accurate speech and text output on smartphone

 ?? Results
- All eight gestures successfully recognized
- Clear text displayed on mobile application
- Voice output generated for every command
- Low power consumption
- Fast response and high portability

? Advantages & Limitations

Advantages
- Low-cost and lightweight
- Easy to operate
- Real-time gesture-to-speech conversion
- Portable and wearable
- Suitable for physically challenged users

Limitations
- Flex sensor calibration is sensitive
- Limited to predefined gestures

 ?? Future Scope
- Machine learning-based gesture recognition
- Full sign language translation
- GSM/GPS integration for emergency alerts
- Smartwatch-style wearable
- Vibration feedback for hearing impaired

?? Conclusion
The Smart Gesture Recognition Glove successfully enables communication for deaf, dumb, paralyzed, and bedridden individuals.  
This project demonstrates the real-world impact of wearable biomedical engineering solutions in healthcare and assistive technology.

Supervisor: Dr. Updesh Verma  
Department of Biomedical Engineering  
SRM University Delhi-NCR

-?? References
- R.S. Khandpur – Handbook of Biomedical Instrumentation  
- Arduino.cc Documentation  
- IEEE Xplore – Smart Glove Research Papers  
- Mazidi – Embedded Systems  
