# 🩻 Chest X-Ray Pneumonia Detection using ResNet50

## 📌 Project Overview

This project uses **Transfer Learning with ResNet50** to automatically classify chest X-ray images as **Normal** or **Pneumonia**. The model was trained on a labeled chest X-ray dataset and is designed to assist in the early detection of pneumonia from medical images.

---

## 📂 Dataset

**Dataset Name:** Chest X-Ray Images (Pneumonia)

**Source:** Kaggle

**Dataset Link:** https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### Classes

* 🟢 Normal
* 🔴 Pneumonia

The dataset contains chest X-ray images categorized into two classes for binary image classification.

---

## 🏗️ Model Architecture

This project uses **ResNet50** as the base model with transfer learning.

### Architecture

* ResNet50 (Pre-trained on ImageNet)
* Global Average Pooling Layer
* Dense Layer
* Dropout Layer
* Output Layer (Sigmoid)

### Techniques Used

* Transfer Learning
* Data Augmentation
* Image Rescaling
* Dropout Regularization
* Early Stopping
* Adam Optimizer
* Binary Crossentropy Loss

---

## 📊 Results

| Metric              | Value      |
| ------------------- | ---------- |
| Validation Accuracy | **93.75%** |
| Test Accuracy       | **87.00%** |
| Pneumonia Recall    | **98.00%** |

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* ResNet50
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure

```text
x_ray_predictions/
│
├── x_ray_predictions.ipynb
├── requirements.txt
├── README.md
├── pneumonia_resnet50.keras
└── images/
    ├── accuracy.png
    ├── loss.png
    └── sample_prediction.png
```

---

## 📈 Features

* Chest X-Ray Image Classification
* Pneumonia Detection
* Transfer Learning with ResNet50
* Data Augmentation
* Early Stopping
* Model Evaluation
* Single Image Prediction
* Model Saving

---

## 🔮 Future Improvements

* Fine-tune the complete ResNet50 model
* Deploy as a Streamlit or Flask web application
* Add Grad-CAM for model interpretability
* Support batch image prediction
* Improve performance through hyperparameter tuning

---

## 👨‍💻 Author

**Mayank Singh**

If you found this project helpful, consider giving it a ⭐ on GitHub.
