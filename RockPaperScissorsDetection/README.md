# Rock Scissors Paper Detection Project

## Overview

The **Rock, Scissors, Paper Detection Project** is a real-time gesture recognition system powered by a YOLO-based backend for detecting and classifying hand gestures. The project aims to build a robust end-to-end system that identifies rock, scissors, and paper gestures from live video input and determines the outcomes based on the game's rules.

This project highlights the efficient integration of advanced object detection techniques with interactive applications, making it ideal for:
- **Educational purposes**
- **AI-powered games**
- **Gesture-controlled systems**

Users can further enhance the system by training their own models, importing new data, and evaluating performance using the provided tools.

## Features

1. **Real-Time Gesture Detection**: The system uses a YOLO-based backend to detect and classify gestures accurately and in real-time.
2. **Outcome Prediction**: Automatically determines game outcomes (win/lose/draw) based on the detected gestures.
3. **Custom Data Integration**: Users can add new data through the data import or data collection tools and label their own data for model training.
4. **Model Evaluation**: Evaluate trained models by providing the path to a `.tflite` file, using the tools available in the `Tools` folder.

## Contents

- **`Data`**: Contains data derived from the [RPS dataset](https://universe.roboflow.com/roboflow-58fyf/rock-paper-scissors-sxsw) for training and testing the model.

- **`Models`**: Stores the trained YOLO-based model and its quantized versions, prepared for deployment.

- **`Tools`**: This folder contains only the **Model Evaluation Graph** as part of the **GraphUx project**, allowing users to:
  - Input a trained `.tflite` model.
  - Visualize and analyze the performance of the model.

## Getting Started

1. **Model Training and Evaluation**:
   - Train the YOLO-based model using the provided dataset or custom data.
   - Download the trained model `.tflite` file from trained job.
   - Use the **Model Evaluation Graph** in the `Tools` folder to evaluate the model's accuracy and effectiveness.

2. **Data Collection and Labeling**:
   - Use Data collection graphUx Template to collect and label gesture data if needed.
   - Incorporate labeled data into the training pipeline to improve the model.

3. **Deploy and Test**:
   - Use the trained model on live video input for real-time detection.
   - Observe gesture detection and automated game outcome predictions.

## Future Enhancements

- Add support for additional gestures and rules to expand beyond "rock, scissors, paper."
- Optimize the model for faster performance on edge devices.
- Automate parts of the data collection and labeling process for user convenience.

---

This project provides a hands-on experience with gesture recognition using advanced computer vision techniques, offering a fun and interactive way to explore AI-based applications.
