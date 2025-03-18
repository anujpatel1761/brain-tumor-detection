# 🧠 Brain Tumor Detection using YOLOv8

## 📌 Project Overview

This project aims to develop an AI-powered brain tumor detection system using **YOLOv8** for real-time, GPU-accelerated object detection in MRI scans. The model is trained on a high-quality dataset with labeled tumor regions.

## 🚀 Project Progress

### ✅ **Phase 1: Dataset Preparation** (✔ Completed)

- 📂 **Dataset Used**: MRI Brain Tumor Detection Dataset
- 🔍 **Classes**: Glioma, Meningioma, Pituitary Tumor, No Tumor
- 📏 **Data Cleaning**: Removed noisy/mislabeled images
- 📊 **Exploratory Data Analysis (EDA)**: Verified image sizes, label distribution, and bounding box correctness

### 🔄 **Phase 2: Model Training** (🟡 In Progress)

- 📌 Converted dataset into YOLOv8-compatible format
- 🛠 **Training YOLOv8 Model** (Currently Running...)
- 🎯 **Goal**: Achieve >90% accuracy

### 🔜 **Phase 3: Model Evaluation & Optimization** (Upcoming)

- 📈 Hyperparameter tuning with Bayesian Optimization
- 🔎 Validate model on unseen MRI scans
- 🖥 Deploy model for real-time inference

## 📁 Project Structure

```
brain-tumor-detection/
│── data/
│   ├── images/
│   ├── labels/
│── notebooks/
│   ├── exploratory_data_analysis.ipynb
│── models/
│   ├── yolov8-brain-tumor.pt
│── scripts/
│   ├── train.py
│── .gitignore
│── README.md
```

## 🏆 Achievements

- ✅ Successfully pushed project to **GitHub**
- ✅ Implemented **data preprocessing & augmentation**
- ✅ Analyzed dataset with **EDA & visualization**

## 🛠 How to Run the Model

1. **Clone the repository**
   ```bash
   git clone https://github.com/anujpatel1761/brain-tumor-detection.git
   cd brain-tumor-detection
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Train YOLOv8 model**
   ```bash
   python scripts/train.py
   ```
4. **Run inference on MRI scans**
   ```bash
   python scripts/infer.py --image sample_mri.jpg
   ```

## 📌 Next Steps

- 🏗 **Fine-tune YOLOv8 for higher accuracy**
- 🖥 **Deploy as a web-based AI tool**
- 🚀 **Optimize for real-time detection on edge devices**

📢 **Stay tuned for more updates!** 🎯

