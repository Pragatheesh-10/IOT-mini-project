# IOT-mini-project
# Project Name
Image processing based fire detection

This project implements fire detection using an ESP32 development board and OpenCV in Python. When the temperature exceeds a certain threshold, the ESP32 triggers the camera to detect fire using color-based methods in OpenCV.

## Components Used
- ESP32 development board
- Temperature sensor (DS18B20)
- LED and Buzzer for alert
- LCD display for temperature display
- PC camera for fire detection using OpenCV

## Directory Structure
- `ESP32/`: Contains the Arduino code for ESP32 and any required libraries.
- `Python/`: Includes the Python code for fire detection using OpenCV and `requirements.txt` for Python dependencies.
- `Images/`: Contains images or diagrams related to the project.

## Setup
1. Wire the components as described in the Arduino code (`ESP32/fire_detection_esp32.ino`).
2. Upload the Arduino code to your ESP32.
3. Install Python dependencies using `pip install -r Python/requirements.txt`.
4. Run the Python script (`Python/fire_detection_opencv.py`) to detect fire using the PC camera.

## Usage
- Monitor the temperature displayed on the LCD.
- If the temperature exceeds the threshold, the ESP32 triggers the camera and alerts using LED and Buzzer.
- The Python script detects fire using OpenCV and prints "Fire detected!" when a fire is detected in the camera feed.

For more details, refer to the README.md and code files in the respective directories.
