# 🩺 Pediatric Pneumonia Detection using Deep Learning (VGG19)

This project leverages deep learning to detect pneumonia in pediatric patients using chest X-ray images. A Convolutional Neural Network (CNN) model with a VGG19 backbone was trained to classify chest X-rays as either *Pneumonia* or *Normal*. The goal is to assist in faster and more reliable medical diagnosis.

---

## 📌 Project Overview

Pneumonia remains one of the leading causes of death in children globally. Traditional diagnosis relies on radiologists, which can be time-consuming and prone to human error. This project proposes a robust deep learning-based alternative to automate the detection process using medical imaging.

---

## 🧠 Methodology

- **Architecture**: Pre-trained **VGG19** model with custom dense layers
- **Techniques Used**:
  - Data Augmentation: Rotation, flipping, brightness shift, zoom
  - Batch Normalization and Dropout for regularization
  - EarlyStopping and Adamax optimizer
- **Training**: Trained for 5 epochs using a generator for efficient loading and augmentation

---

## 📊 Dataset

- **Source**: [Kaggle - Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- **Images**: Pediatric chest X-rays
- **Classes**: `NORMAL`, `PNEUMONIA`
- **Preprocessing**: Rescaling, normalization, augmentation

---

## 🏆 Results

- **Model Accuracy**: **~88%**
- **Architecture**: CNN with VGG19 base
- **Saved Model**: [`cnn-example-pneumonia-resnet50_bnorm_adamax_es_e4.weights.h5`](cnn-example-pneumonia-resnet50_bnorm_adamax_es_e4.weights.h5)

---

## 📁 Project Structure


---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Devesh0508/Pediatric-Pneumonia-Detection.git
cd Pediatric-Pneumonia-Detection

