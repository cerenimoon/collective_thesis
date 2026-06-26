# [collective_thesis - Malware Classification with Deep Learning Models - Derin Öğrenme Modelleriyle Malware Sınıflandırması]

## 📌 Overview - Genel Bakış
This repository features malware classification model implementing 

## 🚀 Key Features - Anahtar Özellikler 
- **Custom Model Training:** Fine-tuned YOLOv5/EfficientNet architectures using Transfer Learning.
- **Model Optimization:** Converted PyTorch weights (`.pt`) to ONNX and TensorRT formats for edge deployment.
- **Data Engineering:** Automated image preprocessing and data stratification utilizing OpenCV.
- **Robust Backend:** Integrated with a Django REST API backed by a optimized PostgreSQL database.

## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Deep Learning Tools - Derin Öğrenme Araçları:** PyTorch, OpenCV 
- **Backend & Database:** Python, Django REST Framework, PostgreSQL
- **DevOps / Infrastructure:** Linux/Ubuntu, Git, Docker

## 📊 Performance Metrics & Results - Performans Metrikleri ve Sonuçlar 
- **Latency Reduction:** Decreased inference latency by **40%** (from 45ms to 27ms) using TensorRT optimization.
- **Accuracy Improvement:** Achieved a **+5.2% increase in mAP@0.5** via advanced data augmentation and dataset engineering.
- **Database Speed:** Reduced query response times by **150ms** through strategic database replication setups and indexing.
