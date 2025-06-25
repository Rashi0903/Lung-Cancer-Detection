# Lung-Cancer-Detection

# 🚀 Leveraging GANs, EfficientNet, and MobileNet for Enhanced Lung Cancer Detection

Welcome to the official repository of our project titled **"Leveraging GANs, EfficientNet, and MobileNet for Enhanced Lung Cancer Detection"** — a research-based initiative to push the boundaries of medical imaging and AI in healthcare.

📌 **Author:** Rashika Negi   
🏫 **Institution:** Graphic Era Hill University, Dehradun, India  
🧪 **Focus Area:** Deep Learning | Medical Imaging | Lung Cancer Segmentation & Classification

---

## 💡 Project Overview

Lung cancer remains one of the deadliest cancers worldwide, and early detection is key to improving survival rates. This project leverages cutting-edge deep learning models — **GANs for data augmentation**, **EfficientNet for accurate classification**, and **MobileNet for lightweight deployment** — to build a powerful and efficient lung cancer detection system from CT scan images.

---

## 🧠 Core Components

### 1. **Generative Adversarial Networks (GANs)**
- Used to generate synthetic lung CT images
- Solves data imbalance issues (especially rare cases like early-stage nodules)
- Boosts generalization performance for downstream models

### 2. **EfficientNet**
- A highly scalable and accurate CNN architecture
- Used for classifying lung cancer stages (Benign, Malignant, etc.)
- Pretrained with ImageNet and fine-tuned on our dataset

### 3. **MobileNet**
- Lightweight, real-time inference model
- Suitable for mobile/embedded healthcare solutions
- Excellent performance with reduced computational cost

---

## 📂 Dataset

- **Source:** Public lung CT scan dataset (Kaggle)
- **Format:** Grayscale 416x416 CT images
- **Preprocessing:** Normalization, resizing, and augmentation using GANs

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- PyTorch (for GANs)
- OpenCV, NumPy, Pandas
- Google Colab / Jupyter Notebook

---

## 📈 Results

| Model       | Accuracy | Precision | Recall | F1 Score |
|-------------|----------|-----------|--------|----------|
| EfficientNet | 94.6%    | 93.2%     | 95.1%  | 94.1%    |
| MobileNet    | 91.2%    | 89.7%     | 90.4%  | 90.0%    |
| With GAN     | +5% ↑ on average across all metrics |

> ⚡ Using GANs improved model robustness and reduced overfitting significantly.

---

## 🔍 How to Use

```bash
# Clone the repo
git clone https://github.com/your-username/lung-cancer-detection-GANs.git
cd lung-cancer-detection-GANs
