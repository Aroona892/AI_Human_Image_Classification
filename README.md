# 🧠 AI_Human_Image_Classification

This project builds a deep learning pipeline to classify images as either **AI-generated** or **human-captured**. With the increasing realism of AI art from tools like Midjourney or DALL·E, this model helps detect and flag synthetic images for content verification and digital forensics.

---

## 📦 Dataset

- Source: [Kaggle - AI Generated Images vs Real Images](https://www.kaggle.com/datasets/cashbowman/ai-generated-images-vs-real-images)
- Loaded via `kagglehub` and processed using `torchvision.datasets.ImageFolder`

---

## 📊 Features

- 🧼 Preprocessing with resizing, normalization, and data augmentation
- ⚖️ Handled class imbalance using `RandomOverSampler` from `imbalanced-learn`
- 🧪 Stratified train-validation split
- 🔁 Trained multiple models: `ResNet18`, `VGG16`, `MobileNetV2`, and `EfficientNetB0`
- 📈 Metrics: Accuracy and loss tracked per epoch
- 📊 Visualized class distributions and training performance

---

## 🛠 Tech Stack

- Python, PyTorch
- torchvision, imbalanced-learn
- kagglehub
- matplotlib, seaborn
- Jupyter Notebooks

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Aroona892/AI_Human_Image_Classification.git
cd AI_Human_Image_Classification
