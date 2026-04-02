# Smart Glasses for Visually Impaired

## Description
A standard eyeglass frame (used as the wearable base)
 ESP32-CAM module mounted on top (acts as brain + camera)
 USB cable (for power + programming)
 Wireless earbuds (likely for audio output)

This is a wearable assistive device designed to help visually impaired people navigate safely and understand their surroundings.

## Objective of the Project
The main goal is to:

Detect obstacles and objects in real time
Provide feedback through sound or vibration
Assist blind users in independent navigation
## Working Principle
1. Image Capture

The ESP32-CAM continuously captures images of the environment using its onboard camera.

2. Processing

There are two possible modes:

Basic Mode: Only distance/obstacle detection (using sensors if added)
Advanced Mode: Image processing / object detection using AI (via server or lightweight model)
3. Decision Making

Based on the captured data:

Detect obstacles (e.g., wall, person, object)
Recognize objects (optional advanced feature)
4. Output Feedback

The system alerts the user using:

--> Audio (through earbuds)

## Hardware Components Explained
1. ESP32-CAM
Acts as the main controller
Has built-in WiFi + camera
Captures and processes images
2. Eyeglass Frame
Provides a wearable structure
Keeps the camera aligned with user’s view
3. Power Supply (USB)
Supplies power to ESP32-CAM
Also used for uploading code
4. Earbuds
Used for audio feedback
Can be connected via Bluetooth (implemented here /can used mannual)

## System Workflow
Device is powered ON
Camera starts capturing frames
Data is processed locally or sent via WiFi
System detects obstacle/object
Feedback is given to the user instantly

## Features of Your Project
 Wearable and portable design
 Real-time environment monitoring
 Low-cost implementation
 Wireless communication (WiFi/Bluetooth)
 Expandable with AI features

## Technologies Used
- Python
- Machine Learning
- OpenCV

## How to Run
1. Install required libraries
2. Run the main Python file
   
## Advanced Features (You Can Add)
To make your project stand out:
-->Navigation Support
GPS + mobile app integration

## Author
Srilipta Mishra
