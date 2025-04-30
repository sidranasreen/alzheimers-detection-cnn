# Alzheimer's Detection Using CNN 🧠🖥️

This project uses Convolutional Neural Networks (CNNs) to detect the presence of Alzheimer's disease from MRI brain scan images. It aims to assist early diagnosis using deep learning-based medical image classification.

## 📂 Dataset
The dataset used is publicly available on Kaggle and contains MRI scans categorized into:
- Mild Demented
- Moderate Demented
- Non-Demented
- Very Mild Demented

## 🧠 Model Architecture
- Convolutional Neural Network (CNN)
- Layers: Convolution, MaxPooling, Flatten, Dense
- Activation Functions: ReLU, Softmax
- Loss Function: Categorical Crossentropy
- Optimizer: Adam

## 📊 Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix

## 💻 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib, scikit-learn

## 🚀 How to Run
```bash
git clone https://github.com/yourusername/alzheimers-detection-cnn.git
cd alzheimers-detection-cnn
python model.py
