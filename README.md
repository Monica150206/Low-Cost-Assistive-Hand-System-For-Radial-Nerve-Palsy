# Low-Cost-Assistive-Hand-System-For-Radial-Nerve-Palsy Patients

Problem Statement :

Radial nerve palsy causes weakness or paralysis of the wrist and finger extensor muscles, making it difficult for individuals to perform everyday tasks such as holding objects, writing, eating, and dressing. Existing assistive devices are often expensive, bulky, and inaccessible to many patients, particularly those in low-income and rural communities. There is a need for an affordable, portable, and easy-to-use assistive device that can support hand movement and improve independence.

Proposed Solution :

This project presents a low-cost smart rehabilitation glove designed to assist finger movement in individuals with radial nerve palsy. The system utilizes a flex sensor to detect finger bending and an Arduino Uno to process the sensor data. Based on the detected movement, a servo motor actuates a tendon-driven mechanism to assist finger motion.

Module Split-Up :

 Module 1: 3D Design
Designed the assistive hand structure using CAD software.
Optimized the finger mechanism for smooth movement and comfort.

 Module 2: Hardware Development
Integrated Arduino Uno, flex sensors, servo motors, power supply, and electronic components.
Established reliable connections between sensors and actuators.

Module 3: Software Development
Programmed the Arduino using Embedded C in Arduino IDE.
Implemented sensor reading, signal processing, threshold detection, and PWM-based servo control.

 Module 4: Prototype Development
Assembled the complete assistive hand system.
Integrated the mechanical, electronic, and control units into a working prototype.

 Module 5: Testing & Validation
Calibrated flex sensors for accurate motion detection.
Tested servo response, finger movement, and overall system performance.
Optimized the system for smooth and reliable operation.

Components Used:
- Arduino Uno
- Flex Sensor
- Servo Motor (SG90/MG90S)
- 10kΩ Resistor
- Glove
- Nylon Thread/Tendon Mechanism
- Jumper Wires
- Power Supply

Working :

The flex sensors mounted on the assistive glove detect the bending of the user's fingers by changing their resistance.
The sensor outputs are read as analog signals by the Arduino Uno.
The Arduino converts these analog signals into digital values using its ADC (Analog-to-Digital Converter).
The program processes the sensor values and compares them with predefined threshold values.
Based on the detected finger movement, the Arduino generates PWM (Pulse Width Modulation) signals.
The PWM signals control the servo motors, which pull the tendon mechanism attached to the fingers.
The servo motors assist in finger and wrist extension, enabling the user to perform gripping and releasing actions.
The entire process runs continuously in real time, providing smooth and responsive assistance to individuals with radial nerve palsy.


Features :
- Low-cost rehabilitation solution
- Flex sensor-based finger movement detection
- Arduino Uno control system
- Servo motor actuation
- Lightweight wearable design
- Expandable to multiple fingers
- - Power Supply
