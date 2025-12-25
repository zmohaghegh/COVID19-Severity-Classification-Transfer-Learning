# Automatic Classification of COVID-19 Severity via Deep Learning

This repository provides a Python/PyTorch implementation based on the research paper: **"Automatic Classification of the Severity of COVID-19 Patients Based on CT Scans and X-rays Using Deep Learning"**.

## 📌 Abstract Summary
As COVID-19 became a global pandemic, the need for rapid prognosis grew. This study focuses on classifying patients into three severity levels: **Normal**, **Mild/Moderate**, and **Severe**. Utilizing Transfer Learning with Deep CNNs (AlexNet, GoogleNet, and ResNet50), this implementation aids healthcare workers, especially in Low to Middle-Income Countries (LMIC), in managing patient priority and resources.

## 🚀 Key Research Implementation
- **Deep Models:** Comparative study between AlexNet, GoogleNet, and ResNet50.
- **Top Performer:** **ResNet50** achieved the highest accuracy in predicting severity.
- **Expert Validation:** Images were verified and classified by highly experienced radiologists from Agha Khan University Hospital.
- **Data Augmentation:** Implemented random rotations and batch processing to handle limited medical imaging data and prevent overfitting.

## 🛠️ Implementation Details (Based on Paper)
- **Framework:** PyTorch (Reproduced from the original MATLAB implementation).
- **Architecture:** ResNet50 with a fine-tuned final Fully Connected layer.
- **Optimizer:** SGDM (Stochastic Gradient Descent with Momentum).
- **Hyperparameters:**
  - Epochs: 6
  - Mini-batch Size: 64
  - Validation Frequency: 6
  - Data Split: 70% Train, 15% Val, 15% Test.

## 📊 Dataset Overview
Verified data from public repositories including COVID-19, SARS, and ARDS cases:
- **Normal:** 1335 images
- **Mild/Moderate:** 106 images
- **Severe:** 50 images

## 💻 Tech Stack
- Python
- PyTorch
- Torchvision
- Matplotlib (for analytical visualization)

---
**Author:** Zahra Mohaghegh  
*M.Sc. in Artificial Intelligence & Robotics*
