# Hand Gesture Recognition (Project #08)

The eighth project in my **AI/ML Learning Path**. This project focuses on **Human-Computer Interaction (HCI)** by recognizing and classifying hand gestures in real-time using a Convolutional Neural Network (CNN).

## 📌 Overview
This system identifies specific hand gestures through a webcam feed. It involves a combination of image preprocessing (to isolate the hand) and deep learning (to classify the shape), allowing for touchless interaction with computer systems.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** OpenCV, TensorFlow/Keras, NumPy
* **Architecture:** Convolutional Neural Network (CNN)
* **Processing:** Background Subtraction, Thresholding, ROI Extraction

## ⚙️ How It Works
1. **Background Subtraction:** The script captures a background frame and subtracts it from the current frame to isolate the moving hand.
2. **Thresholding:** Converts the ROI (Region of Interest) into a binary image (black and white) to highlight the hand's contour.
3. **CNN Classification:** The binary image is fed into a trained CNN model consisting of `Conv2D`, `MaxPooling`, and `Dense` layers.
4. **Action Mapping:** The predicted gesture class is displayed on the screen in real-time.

## 🚀 Quick Start
1. **Install Dependencies:**
   ```bash
   pip install tensorflow opencv-python numpy
2. **Run the Application**
3. **Calibration**
   Keep your hand within the green box (ROI) for the best detection results.

*From static image classification to real-time interactive systems.*
