🦴 Bone Fracture Detection using Deep Learning (X-Ray Classification)

A Deep Learning Computer Vision project that automatically detects bone fractures from X-ray images using a Convolutional Neural Network (CNN).

The model learns visual patterns from radiographic images and classifies them into:

Fractured Bone

Normal Bone

This project demonstrates how AI can assist medical imaging analysis by helping identify fractures with high accuracy.

🎯 Project Objective

Medical image interpretation can be time-consuming and requires specialized expertise. This project aims to build a deep learning model capable of assisting fracture detection from X-ray images, reducing the time required for preliminary diagnosis and supporting healthcare professionals.

📊 Model Performance

The trained model achieved the following evaluation results on the test dataset:

Metric	Score
Test Accuracy	93.51%
Precision	0.9205
Recall	0.9483
AUC Score	0.9819

These metrics indicate strong classification capability and reliable fracture detection performance.

🧠 Model Overview

The project uses a Convolutional Neural Network (CNN) architecture designed for image classification tasks.

Model Pipeline
X-ray Image
      ↓
Image Preprocessing
(resizing, normalization)
      ↓
CNN Feature Extraction
      ↓
Fully Connected Layers
      ↓
Binary Classification
(Fracture / No Fracture)

The model learns spatial features from X-ray images such as bone edges, discontinuities, and structural anomalies.

🛠️ Technologies Used
Category	Tools
Programming	Python
Deep Learning	TensorFlow, Keras
Data Processing	NumPy
Visualization	Matplotlib
Evaluation	Scikit-learn
Development	Jupyter Notebook
