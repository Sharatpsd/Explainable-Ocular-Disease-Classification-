# Explainable Ocular Disease Classification

This repository contains the official implementation of the research work entitled:

**“An Explainable Deep Learning Framework for Multi-Disease Ocular Classification and Myopia Severity Estimation”**

The project focuses on automated and interpretable analysis of retinal fundus images for multi-disease ocular classification, severity-aware myopia estimation, and explainable artificial intelligence (XAI)-based clinical decision support.

---

## 📌 Overview

Vision impairment caused by ocular diseases and refractive errors remains a major global health concern. This work proposes an explainable deep learning framework that integrates:

- Multi-disease ocular classification from fundus images  
- Severity-aware myopia estimation using diagnostic keyword-derived annotations  
- Explainability through Grad-CAM and SHAP visualizations  
- A guideline-based clinical decision support mechanism  

The goal is to bridge the gap between high-performance deep learning models and clinically interpretable decision support systems for precision eye care.

---

## 📊 Dataset

- **Dataset:** ODIR-5K (Ocular Disease Intelligent Recognition)
- **Type:** Public retinal fundus image dataset
- **Annotations:** Multi-disease labels and diagnostic keywords
- **Diseases Included:**  
  - Normal  
  - Diabetic Retinopathy  
  - Glaucoma  
  - Cataract  
  - Age-related Macular Degeneration (AMD)  
  - Hypertensive Retinopathy  
  - Myopia  
  - Other diseases  

The dataset is used for both multi-disease classification and myopia severity estimation.

---

## 🧠 Models Implemented

### Baseline Models
The following pre-trained CNN architectures are implemented for baseline comparison:
- VGG16
- VGG19
- Xception

### Proposed Model
- **ResNet50** (pre-trained on ImageNet)
- Custom classification head
- Severity-aware myopia estimation module
- Explainability using Grad-CAM and SHAP

---

## 🧪 Experiments and Evaluation

The framework is evaluated using standard classification metrics:
- Accuracy
- Precision
- Recall
- F1-score
- AUC (Area Under the ROC Curve)

Additional analysis includes:
- Disease-wise performance evaluation
- Confusion matrix analysis
- Feature representation analysis using t-SNE
- Explainability assessment using Grad-CAM and SHAP

---

## 🔍 Explainability (XAI)

To improve transparency and clinical trust:
- **Grad-CAM** is used to highlight discriminative retinal regions influencing model predictions
- **SHAP** is employed to analyze feature contribution patterns

These visual explanations help verify whether the model focuses on anatomically meaningful retinal structures.

---

## 📁 Repository Structure

