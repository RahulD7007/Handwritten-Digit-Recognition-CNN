# 🧠 Handwritten Digit Recognition using CNN (MNIST)

> A Deep Learning project that classifies handwritten digits (0–9) using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.21-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-DeepLearning-red?logo=keras)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten digits from the **MNIST dataset**. The model is trained on **60,000 grayscale images** and evaluated on **10,000 test images**, achieving an impressive **99.22% test accuracy**.

The project demonstrates the complete deep learning workflow, including:

- Data loading
- Image preprocessing
- CNN architecture design
- Model training
- Performance evaluation
- Visualization of results
- Model saving for future inference

---

## 🚀 Features

✅ Image normalization and preprocessing

✅ CNN architecture built using TensorFlow & Keras

✅ Training and validation monitoring

✅ Performance evaluation using Classification Report

✅ Confusion Matrix visualization

✅ Random sample prediction visualization

✅ Trained model saved for deployment or future predictions

---

# 📂 Dataset

This project uses the famous **MNIST Handwritten Digit Dataset**.

| Attribute | Value |
|----------|-------|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Image Size | 28 × 28 pixels |
| Channels | Grayscale |
| Number of Classes | 10 (Digits 0–9) |

---

# 🏗 CNN Architecture

```
Input (28×28×1)
        │
Conv2D (32 Filters, 3×3)
        │
MaxPooling2D
        │
Conv2D (64 Filters, 3×3)
        │
MaxPooling2D
        │
Conv2D (64 Filters, 3×3)
        │
Flatten
        │
Dense (64)
        │
Dropout (0.5)
        │
Dense (10, Softmax)
```

---

# 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📊 Model Performance

| Metric | Score |
|--------|-------|
| Test Accuracy | **99.22%** |
| Test Loss | **0.0278** |

The trained model demonstrates excellent performance in handwritten digit classification with high precision and recall across all digit classes.

---

# 📈 Output Visualizations

The project automatically generates:

- 📷 Sample MNIST Images
- 📉 Training Accuracy Curve
- 📉 Training Loss Curve
- 📊 Confusion Matrix
- 🔍 Sample Predictions
- 💾 Trained CNN Model

---

# 📁 Project Structure

```
Handwritten-Digit-Recognition-CNN/
│
├── handwritten_digit_recognition.py
├── digit_recognition_cnn.keras
├── sample_digits.png
├── training_history.png
├── confusion_matrix.png
├── sample_predictions.png
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Handwritten-Digit-Recognition-CNN.git
```

Move into the project directory

```bash
cd Handwritten-Digit-Recognition-CNN
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python handwritten_digit_recognition.py
```

---

# 🧪 Workflow

```
Load Dataset
      │
      ▼
Preprocess Images
      │
      ▼
Build CNN Model
      │
      ▼
Train Model
      │
      ▼
Evaluate Performance
      │
      ▼
Generate Predictions
      │
      ▼
Save Trained Model
```

---

# 📌 Future Improvements

- Deploy using Streamlit
- Build a Flask REST API
- Predict custom handwritten images
- Hyperparameter optimization
- Support real-time webcam digit recognition

---

# 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

- Deep Learning fundamentals
- Convolutional Neural Networks (CNNs)
- TensorFlow & Keras
- Image preprocessing
- Model evaluation metrics
- Confusion Matrix analysis
- Data visualization

---