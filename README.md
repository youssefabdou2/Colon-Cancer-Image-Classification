# Colon Cancer Image Classification 🧬🔬

This project develops a **deep learning pipeline** to classify colon histopathology images into **cancerous** (`cancer_good`) and **non-cancerous** (`normal_good`) categories. It leverages **Convolutional Neural Networks (CNNs)**, model evaluation metrics, and interpretability techniques like **Grad-CAM** to provide explainable predictions for medical research.

---

## 📊 Key Results

- **Accuracy:** 96.8%  
- **Sensitivity (Cancer Recall):** 97.4%  
- **Specificity (Normal Recall):** 95.7%  
- **PPV (Precision – Cancer):** 97.4%  
- **NPV (Precision – Normal):** 95.7%  

Confusion Matrix (Test Set):  
[[22 1]
[ 1 38]]



ROC Curve and evaluation metrics confirm strong performance with tight **95% confidence intervals**.

---

## 🔍 Visualizations

- **Confusion Matrix** – evaluates classification performance.  
- **ROC Curve & Threshold Analysis** – shows trade-off between sensitivity and specificity.  
- **Mini-Batch Preview** – visualization of colonoscopy images used for training.  
- **Grad-CAM Heatmaps** – highlight regions influencing the model’s decision.  

---

## ⚙️ Features
- End-to-end CNN pipeline (**PyTorch**).  
- Preprocessing: resizing, normalization, augmentation.  
- Training with validation monitoring and early stopping.  
- Performance evaluation: accuracy, sensitivity, specificity, PPV, NPV, ROC, CI.  
- Grad-CAM for interpretability.  
