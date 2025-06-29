# 🍎🥦 Smart Fruit & Vegetable Classifier using VGG16

This project builds an *image classifier* to detect *fruits and vegetables* using *Transfer Learning (VGG16), **Roboflow dataset, and **Gradio interface* for real-time testing.

---

## 📂 Dataset

- *Source*: [Roboflow - RipeScan](https://roboflow.com)
- *Split*: Train, Validation, Test folders using project.version().download("folder").

---

## 🛠 Features

✅ Uses *VGG16 pre-trained on ImageNet* for feature extraction and fine-tuning.  
✅ *Data Augmentation* with ImageDataGenerator for robust training.  
✅ *Performance Visualization* using Plotly graphs (Accuracy, Loss, Confusion Matrix).  
✅ *Gradio web app* for real-time classification.  
✅ Easily extensible for your college project and real-time sorting pipelines.

---

## 🚀 Installation

```bash
pip install roboflow gradio pillow_heif==0.11.1 plotly seaborn tensorflow opencv-python
## 🚀 Setup & Installation

```bash
# Step 1: Install dependencies
!pip install roboflow gradio pillow_heif==0.11.1 --quiet
