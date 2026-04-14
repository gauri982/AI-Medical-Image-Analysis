# AI-Medical-Image-Analysis
AI-powered system for detecting pneumonia from chest X-ray images using deep learning (MobileNetV2).

# 🩺 AI-Powered Medical Image Analysis System

## 📌 Project Overview
This project uses Artificial Intelligence and Deep Learning to analyze medical images (Chest X-rays) and detect Pneumonia.

The system is built using **Transfer Learning (MobileNetV2)** and classifies images into:
- NORMAL
- PNEUMONIA

---

## 🎯 Objectives
- Automate disease detection using AI
- Assist doctors in faster diagnosis
- Reduce human error in medical imaging

---

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 🏗️ Project Architecture

Medical Image → Preprocessing → CNN Model → Prediction → Output

---

## 📊 Dataset

This project uses the Chest X-ray Pneumonia Dataset.

Download from:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

After downloading, place it in:

data/train/
data/test/

---

## 📁 Project Structure
I-Medical-Image-Analysis/
│
├── src/
│ ├── preprocess.py
│ ├── model.py
│ ├── train.py
│ ├── predict.py
│
├── images/ # screenshots (graphs, outputs)
├── models/ # saved model
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore

👩‍💻 Author

sakshi kakade
