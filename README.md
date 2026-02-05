# 🌿 Cotton Leaf Disease Detection System

This repository contains a **Cotton Leaf Disease Detection System** that uses deep learning and computer vision techniques to automatically identify diseases in cotton leaves. The system helps farmers and agricultural researchers detect diseases early, which can prevent crop loss and improve yield quality.

---

## 🧠 Project Overview

Cotton plants are susceptible to several diseases that can significantly reduce yield if not detected early. This project leverages image classification to detect four major cotton leaf conditions from leaf images:

1. **Bacterial Blight**  
2. **Curl Virus**  
3. **Fusarium Wilt**  
4. **Healthy Leaves**

By analyzing leaf images, the system classifies them into one of these four categories.

---

## 🛠 Features

- Detects cotton leaf diseases automatically from images  
- Classifies leaves into four categories  
- Uses VGG16,ResNet50,DenseNet121 for feature extraction
- Easy to run locally or in Google Colab

---

## 📦 Dataset

The dataset used in this project is the **Cotton Leaf Disease Dataset** from Kaggle.  

- Contains **1710 images** of cotton leaves captured in real-time and from internet sources  
- Images are labeled into **four classes**: Bacterial Blight, Curl Virus, Fusarium Wilt, and Healthy Leaves  
- Suitable for training deep learning models for disease classification

**Implementation**
- A hybrid deep learning + machine learning model.
- Use Normalization and Resizing for preprocessing.

- Combines VGG16, ResNet50, and DenseNet121 for feature extraction.

- Uses Logistic Regression, SVM, and Random Forest as classifiers.

- Final decision made using Soft Voting Ensemble.

- Performed 7 performance metrics accuracy,precision,recall,F1 score,FPR,Specificity,Support.


📥 **Download link:**  
https://www.kaggle.com/datasets/seroshkarim/cotton-leaf-disease-dataset

You can also find variants or similar datasets on **Kaggle** by searching *"cotton leaf disease"*

---

## 🚀 How to Clone this Project

To get a **local copy** of this repository, run:

```bash
git clone https://github.com/Yagnathanakanti/Hybrid-Deep-Learning-for-Cotton-Leaf-Disease-Detection.git
cd Hybrid-Deep-Learning-for-Cotton-Leaf-Disease-Detection

