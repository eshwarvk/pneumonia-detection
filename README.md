# Pneumonia Detection using CNN

This project uses a Convolutional Neural Network (CNN) built from scratch to detect pneumonia from chest X-ray images.

## 🔍 Problem Statement
Pneumonia is a lung infection that can be deadly if not diagnosed early. This project aims to automate detection from X-ray images using deep learning.

## 📊 Dataset
- **Classes**: Pneumonia, Normal
- **Training images**: ~5000+
- **Validation images**: ~600
- **Test images**: ~16

## 🧠 Model Architecture
- 3 Convolutional Layers + MaxPooling
- Dense layers with Dropout
- Activation: ReLU and Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam

## 📈 Results
- Achieved ~71.63% accuracy (aiming for 95%)
- Model trained for 10 epochs

## 🚀 Future Work
- Improve accuracy using pre-trained models like VGG19
- Deploy the model via Flask or Streamlit

## 📁 Files
- `pneumonia_detection_cnn.ipynb`: Colab notebook
- `model.h5`: Trained model weights (coming soon)
- `README.md`: Project documentation

## 🤝 Contributors
- **Eshwar K**

