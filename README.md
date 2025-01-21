# Wearable Fall Detection System with Arduino Nano 33 BLE

## Overview
This repository contains the documentation and resources for a wearable fall detection system implemented on a motorcycle helmet. The system leverages the **Arduino Nano 33 BLE Sense** board, equipped with an integrated accelerometer, to detect and predict falls or extreme events with high precision. Machine learning and advanced filtering techniques are employed to ensure robust and reliable performance.

## Features
- **Customizable Machine Learning Model**: Uses TensorFlow Lite for on-device inference.
- **Kalman Filter Integration**: Reduces sensor noise and improves the accuracy of data readings.
- **High Precision**: Achieves a fall detection accuracy of over **98.85%**, with peaks nearing **99.84%**.
- **Offline Functionality**: Operates without requiring constant internet connectivity.
- **Portable and Lightweight**: Designed as a wearable system integrated into a motorcycle helmet.

## System Components
1. **Hardware**:
   - [Arduino Nano 33 BLE Sense](https://store.arduino.cc/arduino-nano-33-ble-sense)
   - Integrated accelerometer sensor
2. **Software**:
   - TensorFlow Lite
   - Kalman filtering algorithm

## Methodology
The system combines:
1. **Cellular Neural Networks (CNN)**: Utilized for machine learning-based detection and classification.
2. **Kalman Filtering**:
   - Processes noisy sensor data for improved signal accuracy.
   - Minimizes false positives and negatives in event detection.

## How It Works
1. **Data Collection**:
   - Accelerometer data is collected in real-time.
2. **Data Filtering**:
   - The Kalman filter processes raw sensor data to eliminate noise.
3. **Event Recognition**:
   - A machine learning model trained on critical event data predicts falls or extreme accelerations.
4. **Result Evaluation**:
   - The system outputs a prediction with high precision, enabling timely interventions.

## Results
- **Model Accuracy**:
  - Fall detection accuracy: **98.85%**
  - Peak accuracy: **99.84%**
- **Kalman Filter Performance**:
  - Enhanced portability and reduced noise.
  - Significant reduction in false positives/negatives.

## Prototype
Although this was developed as a school project, the prototype demonstrates the viability of using the Arduino Nano 33 BLE Sense for wearable fall detection. The system is portable, accurate, and efficient, providing a foundation for future development.

## References
1. [Original Research](#)
2. TensorFlow Lite Documentation
3. [Kalman Filtering Applications](#)
4. IoT and Sensor Data Processing
5. Arduino Nano 33 BLE Sense Documentation


2. Install required libraries for Arduino:
   - TensorFlow Lite
   - Kalman filtering library
3. Load the provided code onto your Arduino Nano 33 BLE Sense.
4. Follow the instructions in the documentation folder for hardware assembly and testing.

## Future Improvements
- Expand the dataset for training to include more diverse fall scenarios.
- Integrate long-range communication modules for emergency notifications.
- Optimize power consumption for prolonged usage.

---

Feel free to contribute to this project by submitting issues or pull requests!
