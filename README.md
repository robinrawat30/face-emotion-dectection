# 🎭 Real-Time Face Emotion Recognition using Machine Learning

This project implements a **real-time facial emotion detection system** using **Machine Learning and Deep Learning techniques**. It detects human faces from live video streams and classifies their emotions into seven basic categories with high accuracy.

---

## 📌 Project Overview

Human emotions play a crucial role in communication and interaction. This system analyzes facial expressions in real time and identifies emotions such as **Happy, Sad, Angry, Fear, Disgust, Surprise, and Neutral**.

The project uses **OpenCV** for face detection and **Deep Learning models (CNN + DeepFace)** for emotion classification.

---

## 🧠 Emotions Detected
- 😄 Happy  
- 😢 Sad  
- 😠 Angry  
- 😨 Fear  
- 🤢 Disgust  
- 😲 Surprise  
- 😐 Neutral  

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **DeepFace**
- **TensorFlow / Keras**
- **NumPy**
- **Haar Cascade Classifier**
- **FER2013 Dataset**

---

## 📂 Dataset

- **FER2013 Dataset**
- 35,887 grayscale images (48×48 pixels)
- 7 emotion classes
- Widely used benchmark dataset for facial emotion recognition

---

## ⚙️ System Workflow

1. Capture real-time video using webcam  
2. Detect faces using Haar Cascade Classifier  
3. Preprocess face images (crop, resize, grayscale)  
4. Extract features using CNN / DeepFace  
5. Classify emotions  
6. Display detected emotion on video frame  

---

## 🚀 Installation & Setup

### 🔹 Step 1:
