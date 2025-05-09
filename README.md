# Face Mask Detection with Live Alert System

This project is a real-time face mask detection system that uses your device's webcam to detect whether a person is wearing a face mask. It is built using **Python**, **OpenCV**, and **TensorFlow/Keras**, and utilizes a **Convolutional Neural Network (CNN)** model for classification.

# Objective
To develop a live alert system that helps ensure public safety by monitoring mask compliance in real-time, especially in high-risk environments.

# Features
- 🎥 Real-time face detection from webcam
- 🧠 CNN-based face mask classification
- 🟢 Green box around faces with masks
- 🔴 Red box around faces without masks
- 🗂️ Easy to train with your own dataset

# Tech Stack
- Python 3.11+
- OpenCV
- TensorFlow / Keras
- Numpy
- Haar Cascade Classifier

## 🗃️ Project Structure
── app/
│ └── mask_detection.py # Main script for real-time detection
├── model/
│ └── mask_detector_model.h5 # Trained CNN model
├── requirements.txt # Required dependencies
└── README.md # Project documentation

# Model Info
Input Shape: (128, 128, 3)
Model Type: Sequential CNN
Output: Binary classification — Mask / No Mask
Training Dataset: 2,000+ labeled images (can be updated)

# Use Cases
Offices and Workplaces
Public Transport
Hospitals & Clinics
Schools & Colleges





