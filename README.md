# Alzheimer-segmentation-and-Classification-Code
Code for Alzheimer's disease with Gray matter segmentation and hybrid approach classification with XAI

This repository contains the implementation of our proposed hybrid deep learning model using Multi-Layer U-Net for brain segmentation and Multi-Scale EfficientNet with SVM for Alzheimer's disease classification. The project includes Explainable AI (XAI) integration using saliency maps.

## 🧠 Overview
- **Segmentation**: Multi-Layer U-Net to extract gray matter from MRI scans.
- **Classification**: Multi-Scale EfficientNet + SVM to classify AD, MCI, CN.
- **XAI**: Saliency maps used for interpretability.

## 📁 Folder Structure
├── segmentation/ # Multi-layer U-Net code
├── classification/ # EfficientNet feature extraction + SVM
├── xai/ # Saliency map visualization
├── requirements.txt # Python packages required
└── README.md

## ⚙️ Requirements
Python 3.8+
TensorFlow or PyTorch
scikit-learn
matplotlib
opencv-python

Install all dependencies:
pip install -r requirements.txt

## 📈 Results
The proposed model achieved:
- Dice Score: 91.52% (segmentation)
- Accuracy: 96% (classification)
