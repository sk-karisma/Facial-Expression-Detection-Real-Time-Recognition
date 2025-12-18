# Facial Expression Detection – Real-Time Recognition

This project implements a **Real-Time Facial Expression Recognition System** using **Computer Vision** and **Deep Learning**.  
It detects human faces from a live webcam feed and classifies facial expressions into different emotion categories using a **Convolutional Neural Network (CNN)**.

---

## Project Overview

The system performs the following tasks:

1. Captures live video from a webcam  
2. Detects faces in each frame using **OpenCV Haar Cascade**  
3. Preprocesses detected face regions  
4. Predicts facial expressions using a **pretrained CNN model**  
5. Displays the predicted emotion in real time  

This project is intended for **local execution** and real-time experimentation.

---

## Features

- Real-time face detection using webcam  
- Facial expression classification using a CNN  
- Supports common emotion classes (e.g., Happy, Sad, Angry, Neutral, etc.)  
- Uses OpenCV for image processing  
- Uses TensorFlow/Keras for deep learning  

---

## Project Structure
```
Facial-Expression-Detection-Real-Time-Recognition/
│
├── Real-Time Facial Expression Detection & Recognition using CNN.ipynb
├── fer.h5
├── haarcascade_frontalface_default.xml
├── webcam_test.py
├── Facial Expression Recognition.json
```

---

### File Description

- **`webcam_test.py`** – Runs real-time facial expression detection using webcam  
- **`fer.h5`** – Pretrained CNN model for emotion classification  
- **`haarcascade_frontalface_default.xml`** – Haar Cascade model for face detection  
- **`.ipynb` notebook** – Model training, experimentation, and evaluation  
- **`.json` file** – Supporting metadata or configuration  

---

## Dataset Used

The CNN model is trained on the **FER-2013 dataset**
