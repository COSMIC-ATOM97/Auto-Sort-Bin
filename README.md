# AutoSort Bin

## Description
The **AutoSort Bin** is an innovative waste management system that leverages IoT technology and deep learning to automate the segregation of waste into five categories: metal, paper, plastic, glass, and trash. This project aims to improve waste management by identifying waste types using a deep learning model, controlling bin lids with servo motors, and monitoring bin levels with ultrasonic sensors. The system promotes environmental sustainability and is scalable for various applications.

## Features
- **AI-Powered Waste Segregation**: Utilizes a Convolutional Neural Network (CNN) to classify waste based on images.
- **Bin Full Detection**: Ultrasonic sensors detect when a bin is full and display a message on the LCD.
- **Real-Time Updates**: ThingSpeak cloud integration allows data aggregation and monitoring.
- **Wide Categorization**: Classifies waste into five categories: paper, glass, metal, plastic, and trash.
- **Automation**: Servo motors open and close the bin lids based on waste type.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AutoSort-Bin.git

2. Install necessary dependencies:
   ```bash
   pip install tensorflow keras numpy matplotlib pillow opencv-python
3. Set up the ThingSpeak API key in the script for cloud integration.
4. Connect the hardware components as per the circuit diagram provided in the project report.

## Usage
- Power on the system and ensure all components are connected.
- Press the start button to activate the system.
- Place waste under the camera to capture an image.
- The system will:
- Classify the waste using the deep learning model.
- Open the corresponding bin lid for disposal.
- Display waste type and bin usage statistics on the LCD.
- If a bin is full, an alert will be displayed, and the lid will not open.

## Components
# Hardware
- Microcontroller: ESP32
- Input Devices:
- Camera (Webcam)
- Ultrasonic Distance Sensors (HC-SR04)
# Output Devices:
- 16x2 LCD (I2C interface)
- Servo Motors
# Software
- TensorFlow, Keras: Deep learning framework
- ThingSpeak: Cloud integration for data monitoring
- Wokwi: ESP32 circuit simulator
- Python Libraries: NumPy, Pillow, OpenCV, Matplotlib

## Experimental Results
- Training Accuracy: 86.56%
- Testing Accuracy: 85.68%
- Validation Accuracy: 84.83%
- Precision: 87%
- Recall: 80%
- F1 Score: 83%
## Future Improvements
- Integration of more accurate and stable deep learning models.
- Implementation of GSM modules for notifications.
- Use of advanced sensors (e.g., moisture, infrared) for error minimization.
- Solar-powered systems and additional features like odor control and UV sterilization.
- Contributing
# Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
