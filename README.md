# Pneumonia Detection in Chest X-Ray Images using ResNet50V2

## 🧠 Project Summary

This project addresses the classification of chest X-ray images to detect signs of **pneumonia**, a common and serious complication observed during the COVID-19 pandemic. 

Leveraging the power of **Artificial Intelligence** and **Deep Learning**, the study uses the **ResNet50V2** architecture—pretrained on large image datasets—to classify X-ray images into two categories: with pneumonia and without pneumonia.

The project highlights the importance of medical image analysis in times of health crises, aiming to support overwhelmed healthcare systems with fast, automated diagnostics.

## 📊 Objectives

- Preprocess a dataset of chest X-ray images
- Apply transfer learning using the **ResNet50V2** convolutional neural network
- Evaluate model performance to optimize classification results

## 🧰 Tools & Libraries

- Python  
- TensorFlow  
- Keras  
- PyTorch  
- NumPy, Pandas, Matplotlib (for data handling and visualization)

## 📁 Dataset

- Chest X-ray images labeled as:
  - **Pneumonia**
  - **Normal**
- Publicly available datasets such as the [Chest X-Ray Images (Pneumonia) dataset on Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) were used.

## 🔍 Workflow

1. **Data Preprocessing**
   - Image resizing and normalization
   - Train-test split
2. **Modeling**
   - Load pretrained **ResNet50V2**
   - Add custom classification layers
   - Fine-tune with transfer learning
3. **Evaluation**
   - Accuracy, precision, recall, and confusion matrix
   - Optimization of hyperparameters

