ESP32-CAM Intelligent Camera Web Server (2025)
Esp32CamModuleFaceRecognition-2025

A standalone ESP32-CAM based intelligent camera system that provides real-time MJPEG video streaming and on-device face detection using an embedded web server.
The project runs entirely on the ESP32-CAM module without requiring cloud services or a connected PC.

=>Project Overview
This project demonstrates how a low-cost microcontroller can be used to build a complete embedded vision system.
The ESP32-CAM captures live video, optionally performs face detection on-device, and streams the output directly to a web browser using HTTP.

It is designed as an educational and demonstration project for embedded systems, IoT, and edge AI concepts.

=>Key Features
Real-time MJPEG video streaming over HTTP
On-device face detection (no cloud processing)
Browser-based live view and image capture
Standalone operation (ESP32 runs as a web server)
Uses on-board PSRAM for frame buffering
LED flash support for low-light conditions
Accessible from any modern web browser
->Face Detection vs Recognition
->Face Detection: Supported on ESP32-CAM (detects faces and draws bounding boxes)
->Face Recognition: Not supported on ESP32 due to hardware limitations
->Face recognition is possible on ESP32-S3 with higher processing power

=>Hardware Used
ESP32-CAM (AI Thinker)
OV2640 Camera Module
On-board PSRAM
FTDI USB-to-TTL Programmer
Jumper Wires
5V Power Adapter
Web Browser (Client)

=>Software & Tools
Arduino IDE / PlatformIO
ESP32 Board Package by Espressif
esp_camera library
esp_http_server
Wi-Fi library (built-in)

=>How It Works (High Level)
OV2640 camera captures image frames
Frames are stored in PSRAM
Optional face detection runs on ESP32
Frames are JPEG encoded
MJPEG stream is served via HTTP
Browser displays live video feed

=>Performance Notes
Best performance at lower resolutions
Face detection works reliably at low resolutions
Higher resolutions reduce FPS and disable detection
Designed for demo and educational use, not production surveillance

=>Applications
Embedded systems & IoT education
Edge AI demonstrations
Smart doorbell prototypes
Basic surveillance projects
Attendance systems (with ESP32-S3 upgrade)

=>Full Documentation
For detailed explanation, including:
Complete project documentation
Code structure and explanations
Hardware & software setup
Performance analysis
Images and project poster

=>Visit the official project page:
https://mayank.wiki/college-2025/

=>Author
Mayank Kulkarni
Founder – MKTechs
Embedded Systems | IoT | Edge AI | Full-Stack Development
-> https://mayank.wiki

=>Disclaimer
This project is intended for educational and learning purposes only.
It is not designed for professional security or surveillance deployments.

=>License
## Third-Party Licenses & Attribution
This project uses components from the Espressif ESP32 SDK and related libraries.
Portions of the code are based on software provided by  
**Espressif Systems (Shanghai) PTE LTD**,  
licensed under the **Apache License, Version 2.0**.
Apache License 2.0:  
http://www.apache.org/licenses/LICENSE-2.0

