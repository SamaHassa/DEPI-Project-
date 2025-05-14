# 🧠 DEPI Project – Skin Cancer Classification

This repository contains the codebase for the **Skin Cancer Classification** project developed as part of the **DEPI**. The goal is to build an AI-powered system that supports early detection and classification of various skin cancer types using metadata and dermoscopy images.

---

## 📌 Project Summary

Skin cancer is one of the most common cancers globally. Early detection significantly increases treatment success rates. This project applies **Machine Learning (ML)** and **Deep Learning (DL)** to:
- Analyze patient metadata and skin lesion characteristics
- Classify skin lesion images using computer vision
- Provide a fast, scalable, and automated diagnostic tool

---

## 🛠️ Technologies Used

### ✅ Machine Learning
- **Random Forest**
- **XGBoost**
> Trained on extracted metadata (age, lesion location, etc.)

### ✅ Deep Learning
- **YOLOv8** (You Only Look Once – Version 8)
> Applied to dermoscopy images for lesion detection and classification.

### ✅ Other Tools
- **Pandas**, **NumPy**, **Matplotlib**, **scikit-learn**
- **Ultralytics YOLOv8**
- **Streamlit** (for deployment and UI)
- **Roboflow** (for dataset management)

---

## 📂 Dataset

The dermoscopy images used for the deep learning part are hosted on Roboflow:

🔗 [SmartDerm Dataset on Roboflow](https://universe.roboflow.com/smartderm-ys1a2/smartderm-dq8ae/dataset/1)

You can download and preprocess the dataset directly through the Roboflow interface or use their API.

---

## 🚀 Getting Started

### 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SamaHassa/Skin_Cancer_DEPI.git

🧪 Results
ML models achieved high accuracy on structured metadata using RF and XGBoost.

YOLOv8 provided fast and accurate predictions on dermoscopy images.

An interactive Streamlit app was built to test predictions on real or uploaded images.

💡 Future Improvements
Add ensemble methods to combine ML and DL predictions.

Expand the dataset to include more diverse skin tones and conditions.

Integrate patient history and external medical data for richer context.

🤝 Contributions
Contributions are welcome! If you'd like to improve the model or dashboard, feel free to fork this repo and submit a pull request.

