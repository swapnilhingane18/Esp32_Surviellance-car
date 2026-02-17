🚗 ESP32 Surveillance Car with Live Camera & Pan-Tilt Control
📌 Project Overview

This project is a WiFi-controlled surveillance car developed using ESP32-CAM.
It provides live video streaming directly in a web browser and allows real-time control of the car’s movement, speed, lighting, and camera orientation (pan & tilt).

The ESP32 runs as a standalone WiFi hotspot, so the system works without internet and can be accessed from any mobile phone or laptop browser.

🎯 Features

📷 Live video streaming using ESP32-CAM

🌐 Browser-based control panel (no mobile app required)

🚗 Real-time car movement (forward, backward, left, right, stop)

🎚 Speed control using PWM

💡 Headlight brightness control

🎥 Pan & tilt camera movement using servo motors

⚡ WebSocket-based real-time communication

📡 Offline operation using WiFi SoftAP mode

🛠 Hardware Components

ESP32-CAM (OV2640 camera module)

DC motors with motor driver (L298N / L293D)

Servo motors for pan & tilt mechanism

Robot chassis with wheels

Battery / power supply

Jumper wires

💻 Software & Technologies Used

Programming Language: Embedded C++

Framework: Arduino framework for ESP32

Microcontroller: ESP32-CAM

Communication: WiFi (SoftAP mode)

Protocol: WebSockets

Frontend: HTML, CSS, JavaScript

IDE: Arduino IDE

⚙️ Working Principle

ESP32 creates its own WiFi network.

User connects to this WiFi using a phone or laptop.

Accessing the ESP32 IP address opens a web-based control interface.

Live camera feed is streamed using WebSockets.

Control inputs (buttons and sliders) are sent to ESP32 in real time.

ESP32 processes commands to control motors, servos, and lighting.

▶️ How to Run the Project

Open the .ino file in Arduino IDE.

Select the correct ESP32 board and COM port.

Upload the code to ESP32-CAM.

Open Serial Monitor to get the ESP32 IP address.

Connect your phone or laptop to the ESP32 WiFi network.

Open the IP address in a browser to control the car and view live video.

Learning Outcomes (Added)

Through this project, the following skills were developed:

ESP32 WiFi and camera configuration

Real-time WebSocket communication

Embedded motor and servo control

Frontend-backend integration for IoT systems

Debugging hardware-software interaction

Designing complete end-to-end embedded solutions

Unlike basic robotic cars, this project:

Does not require internet or cloud services

Does not require a mobile application

Uses WebSocket instead of slow HTTP polling

Provides full camera pan-tilt control

Runs completely on ESP32 standalone hardware

Performance Highlights (Added)

Low latency control: WebSocket communication provides near real-time response.

Stable video stream: OV2640 camera optimized for smooth streaming.

Offline reliability: No dependency on cloud or internet services.

Cross-platform compatibility: Works on Android, iOS, Windows, and Linux browsers.


📈 Applications

Remote surveillance and monitoring

Security robotics projects

IoT and embedded systems learning

Final-year engineering project

Smart robotic vehicle demonstrations

🔮 Future Enhancements

Face detection and recognition

Obstacle detection using ultrasonic sensors

Password-protected web interface

Video recording to SD card

Improved mobile-friendly UI


👤 Author

Swapnil Hingane
Electronics & Telecommunication Engineering

