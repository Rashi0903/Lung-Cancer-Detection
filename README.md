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

> ![image](https://github.com/user-attachments/assets/8ce3834f-780e-4bce-99f2-1d6d2aac64e7)


> ⚡ Using GANs improved model robustness and reduced overfitting significantly.
>
## 📸 Visual Results
> Sample Images from the Dataset
> ![image](https://github.com/user-attachments/assets/536bba6a-305d-46cc-bcd0-0d3724e59b43)

>Augmented Images
>![image](https://github.com/user-attachments/assets/d2a467b4-7386-493c-8ad5-467cf3d3b061)

>EfficientNet
>Test Accuracy: 96.47%
>Precision: 91.63%
>Recall: 98.94%
>F1 Score: 95.14%
>![image](https://github.com/user-attachments/assets/74572ed1-3c8d-4463-bd8e-51a0858249fc)

>MobileNet
>Test Accuracy: 93.88%
>Precision: 93.79%
>Recall: 88.30%
>F1 Score: 90.96%
>![image](https://github.com/user-attachments/assets/a84f0d02-d236-4d88-91b9-4f88e58fed55)

>GAN
> Accuracy: 0.9294
> Precision: 0.9865
> Recall: 0.8706
> F1 Score: 0.9249
>![image](https://github.com/user-attachments/assets/66136408-b60f-495d-a223-72a6b7241cc7)


---

## 🔍 How to Use

```bash
# Clone the repo
git clone https://github.com/your-username/lung-cancer-detection-GANs.git
cd lung-cancer-detection-GANs
