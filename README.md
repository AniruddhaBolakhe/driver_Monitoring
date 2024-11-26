Drowsiness and Alcohol Detection System
A real-time system that detects driver drowsiness and alcohol levels to enhance road safety. The project integrates a camera, alcohol sensor, and buzzer to identify and alert when the driver shows signs of drowsiness or alcohol consumption.

Features
Drowsiness Detection: Monitors eye aspect ratio (EAR) to determine if the driver is drowsy. If eyes remain closed for more than 5 seconds, an alert is triggered.
Alcohol Detection: Measures alcohol levels using an alcohol sensor. Displays alcohol levels numerically on a dashboard.
Alerts: A buzzer is activated when:
The driver is drowsy.
Alcohol is detected.
Hardware Requirements
Raspberry Pi (any compatible model with GPIO support)
USB Camera (or Raspberry Pi camera module)
MQ-3 or similar Alcohol Sensor
Active Buzzer Module
Jumper Wires
Breadboard (optional)
Pin Connections
1. Alcohol Sensor
VCC → 3.3V
GND → GND
DOUT → GPIO 18
2. Buzzer
VCC → 3.3V
GND → GND
Signal → GPIO 17
3. Camera
USB Camera connected to a Raspberry Pi USB port or Camera Module connected to the CSI port.
Software Requirements
Python 3.6 or higher
Libraries:
Flask
OpenCV
Dlib
RPi.GPIO
SciPy
shape_predictor_68_face_landmarks.dat for facial landmark detection.



![image](https://github.com/user-attachments/assets/95dd7307-329e-4641-be94-9ee015ce8964)

