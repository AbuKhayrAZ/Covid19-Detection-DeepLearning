# COVID-19 Detection from Chest X-Rays using Deep Learning

## 📌 Overview
This project focuses on the automated detection of COVID-19 from chest X-ray images using Convolutional Neural Networks (CNNs). By leveraging Deep Learning, the goal is to provide a rapid screening tool to assist medical professionals in identifying respiratory infections with high precision.

## 🚀 Project Status & Optimization Goal
* **Current Accuracy:** ~70% (Baseline Custom CNN)
* **Target Accuracy:** 90%+ 
* **Active Development:** I am currently implementing **Transfer Learning** (ResNet50/VGG16) and **Advanced Data Augmentation** to handle class imbalances and improve generalization on unseen medical data.

## 🛠️ Tech Stack
* **Frameworks:** TensorFlow, Keras
* **Libraries:** OpenCV, NumPy, Matplotlib, Scikit-learn
* **Environment:** Python 3.x, Jupyter Notebook

## 📊 Dataset
The model is trained on a dataset of chest X-ray images categorized into:
1.  **COVID-19 Positive**
2.  **Normal**

## 🧠 Methodology (Current Architecture)
1.  **Preprocessing:** Resizing images to 224x224, grayscale normalization, and pixel scaling.
2.  **Baseline Model:** A sequential CNN architecture with multiple Conv2D layers, Max-Pooling, and Dropout layers to prevent overfitting.
3.  **Evaluation:** Using Confusion Matrices and ROC-AUC curves to assess diagnostic performance beyond simple accuracy.

## 📈 Planned Improvements for 90%+ Accuracy
* **Transfer Learning:** Utilizing pre-trained weights from ImageNet using ResNet50.
* **Learning Rate Scheduling:** Implementing `ReduceLROnPlateau` to fine-tune the optimization process.
* **Class Weighting:** Adjusting loss functions to account for any data imbalance between 'Normal' and 'COVID' samples.

## 📬 Contact
**Azeez Ajibola** - [LinkedIn](https://linkedin.com/in/azeez-ajibola)
