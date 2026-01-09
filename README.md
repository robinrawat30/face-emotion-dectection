# 🎭 Real-Time Face Emotion Recognition using Machine Learning

This project implements a **real-time facial emotion detection system** using **Machine Learning and Deep Learning**. It detects faces from live webcam feed and classifies emotions into seven categories.

---

## 📌 Project Overview

Facial emotion recognition plays an important role in Human–Computer Interaction.  
This system uses **OpenCV** for face detection and **CNN / DeepFace** models for emotion classification.

---

## 🧠 Emotions Detected
- Happy
- Sad
- Angry
- Fear
- Disgust
- Surprise
- Neutral

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- DeepFace  
- TensorFlow / Keras  
- NumPy  
- Haar Cascade  
- FER2013 Dataset  

---

## ⚙️ Workflow

1. Capture live video
2. Detect face using Haar Cascade
3. Preprocess face image (48×48, grayscale)
4. Feature extraction using CNN / DeepFace
5. Emotion classification
6. Display emotion on video frame

---

## 🚀 How to Run

```bash
git clone https://github.com/USERNAME/REPO_NAME.git
cd Face_Emotion_Recognition_Machine_Learning
pip install -r requirements.txt
python main.py
