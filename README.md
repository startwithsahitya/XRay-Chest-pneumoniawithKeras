# 🫁 Pneumonia Detection using Computer Vision & Deep Learning

An end-to-end computer vision project that detects pneumonia from chest X-ray images using deep convolutional neural networks and transfer learning.

---

## 📌 Overview

This project applies computer vision techniques to classify chest X-ray images into:
- Normal  
- Pneumonia  

The model learns visual patterns like lung opacity and texture variations using a pretrained CNN.

---

## 👁️ Computer Vision Pipeline

Input Image → Preprocessing → Data Augmentation → Feature Extraction → Classification → Prediction

---

## 🧠 Model Architecture

- Base Model: DenseNet121  
- Transfer Learning + Fine-tuning  
- Global Average Pooling + Dropout  
- Sigmoid Output Layer  

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 📂 Dataset

Chest X-ray Pneumonia Dataset (Kaggle)  
Split into Train / Validation / Test  

---

## ⚙️ Tech Stack

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 Training Strategy

- Data augmentation  
- Undersampling for class balance  
- Learning Rate Finder  
- Cyclic Learning Rate  

Training phases:
1. Transfer Learning  
2. Fine-tuning  

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/pneumonia-detection-cv.git
cd pneumonia-detection-cv
pip install -r requirements.txt
