# [collective_thesis - Malware Classification with Deep Learning Models - Derin Öğrenme Modelleriyle Malware Sınıflandırması]

## 📌 Overview - Genel Bakış
- This repository features malware classification model implementing deep learning models based on Efficientnet architecture. 
- Bu kod tabanı, Efficientnet mimarisine sahip derin öğrenme modellerini uygulayan malware sınıflandırma modeli içermektedir.
<table align="center">
  <tr align="center">
    <td><img width="%100" alt="Ekran görüntüsü 2024-06-08 184211" src="https://github.com/user-attachments/assets/d0f5a75a-54b3-4935-9f7a-5a330987655b" /><br><b>Transfer Learning Architecture - Transfer Learning Mimarisi</b></td>
    <td><img width="%100"  alt="Ekran görüntüsü 2024-05-30 182744" src="https://github.com/user-attachments/assets/fd2fff5f-75e0-4d64-b4cd-c95fcc9feb06" />
<br><b>Image Preprocessing steps - Görüntü Ön işleme adımları</b></td>
  </tr>
</table>

## 🚀 Key Features - Anahtar Özellikler 
- **Custom Model Training - Özel:** Fine-tuned Efficientnet architectures using Transfer Learning for classification of malware images.
Efficientnet mimarileri Transfer Learning yöntemiyle malware görüntülerinin sınıflandırması için uyarlanmıştır.
Model weights are saved as PyTorch weights (`.pt`). Model ağırlıkları PyTorch (`.pt`) ağırlıkları olarak kaydedilmiştir. 
- **Data Preprocessing - Veri Ön işlemesi:** Image preprocessing via reshaping, compressing and turning into tensor structure utilizing OpenCV and PyTorch tools.
Görüntü işleme adımları, boyutlandırma, sıkıştırma ve tensor yapılarına dönüştürme OpenCV ile PyTorch araçlarıyla gerçekleştirilmiştir. 

## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Code Area - Kod Tabanı:** Python
- **Model Architecture - Model Mimarisi:** Efficientnet-b0 - Efficientnet-b7 Transfer Learning architectures are used.
Efficientnet-b0 - Efficientnet-b7 Transfer Learning mimarileri kullanılmıştır. 
- **Deep Learning Tools - Derin Öğrenme Araçları:** PyTorch, OpenCV 
- **DevOps / Infrastructure - Geliştirme ve Altyapı:**  Git, Github

## 📊 Performance Metrics & Results - Performans Metrikleri ve Sonuçlar 
- **Accuracy - Doğruluk:** Achieved a **96% validation accuracy rate** via  data augmentation and Transfer Learning improvement. 
