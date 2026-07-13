#  Plant Disease Detection using CNNs and YOLO

##  Project Overview

Plant diseases significantly impact crop yield and agricultural productivity. This project leverages deep learning techniques to automatically detect and classify plant diseases from leaf images, enabling faster and more accurate diagnosis.

The application supports both disease classification and disease localization using multiple CNN architectures and YOLO models integrated into a Flask web application.

---

##  Features

*  Plant disease classification from leaf images
*  Disease region detection using YOLO
*  Multiple CNN architectures with Transfer Learning
*  Image preprocessing and augmentation
*  User authentication using SQLite
*  Flask-based web interface
*  Image upload and prediction

---

## 🛠️ Technologies Used

* Python
* Flask
* TensorFlow / Keras
* PyTorch
* YOLO
* OpenCV
* NumPy
* SQLite
* HTML
* CSS

---

## 🤖 Deep Learning Models

### Classification Models

* VGG16 (Transfer Learning)
* MobileNet
* MobileNet with Transfer Learning
* MobileNet with Stepwise Transfer Learning
* MobileNetV3-Large
* GoogleNet
* AlexNet
* DenseNet201
* Xception

### Detection Models

* YOLOv5
* YOLOv6
* YOLOv7
* YOLOv8

---

## 📂 Dataset

This project was developed using publicly available datasets:

* PlantVillage Dataset
* Pepper Disease Dataset

The datasets are not included in this repository due to their large size.

---

## 📷 Application Workflow

1. User registers or logs in.
2. Upload a plant leaf image.
3. The image is preprocessed.
4. The CNN model predicts the disease class.
5. YOLO detects the affected region (if applicable).
6. The prediction result is displayed on the web interface.

---

## 📊 Results

The system evaluates multiple CNN architectures to identify the most effective model for plant disease classification. YOLO models are used to localize infected regions, improving disease visualization and analysis.

---

