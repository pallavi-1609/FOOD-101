# 🍱 Food-101 Image Classification using Deep Learning

Welcome to the **Food-101 Project**!  
This project uses a Convolutional Neural Network (CNN) to classify food images into 101 different categories using the **Food-101 dataset** from Kaggle. It's built using Python, TensorFlow, and Keras, and runs smoothly on Google Colab.

---

## 📊 Dataset

- Dataset: [Food-101 on Kaggle](https://www.kaggle.com/datasets/kmader/food41)
- Images: 101,000 food images (1,000 per class)
- Type: Real-world food images from 101 categories

---

## 🚀 Project Highlights

- ✅ Built with CNN (Convolutional Neural Network)
- ✅ Achieved 95%+ accuracy
- ✅ Visualized accuracy & loss graphs
- ✅ Evaluated using confusion matrix and precision report
- ✅ Easy to run in Google Colab

---

## 🧠 Model Architecture

- Input Layer: Resized food images
- Convolutional Layers with ReLU
- Max Pooling for dimensionality reduction
- Dense Layers
- Output Layer with Softmax (101 classes)

---

## 📈 Results and Evaluation

### 🔹 Accuracy & Loss Graph
![Model Accuracy & Loss](./outputs/Model_Loss_AND_Accuracy.png)

### 🔹 Confusion Matrix
![Confusion Matrix](./outputs/confusion_matrix.png)

---

## 🛠️ Requirements

Install the following dependencies (or see `requirements.txt`):

```bash
tensorflow
keras
matplotlib
numpy
pandas
scikit-learn
