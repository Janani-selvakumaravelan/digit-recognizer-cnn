digit-recognizer-cnn
A Convolutional Neural Network (CNN) based deep learning model that recognizes handwritten digits (0–9) using the MNIST dataset. This project demonstrates image preprocessing, CNN architecture design, model training, evaluation, and digit prediction visualization.

🧠 Handwritten Digit Recognition using CNN
This project implements a **Convolutional Neural Network (CNN)** to recognize handwritten digits (0–9) using the **MNIST dataset**. Built with **TensorFlow/Keras**, this classic computer vision project demonstrates deep learning techniques for image classification.
📌 Project Highlights
- ✅ MNIST dataset (60,000 training & 10,000 test images)
- ✅ Image preprocessing and normalization
- ✅ Deep CNN architecture
- ✅ Accuracy evaluation and visualization
- ✅ Google Colab ready
Run on Google Colab
Click below to open and run the project in Google Colab:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

📂 Dataset
We use the **MNIST dataset**, preloaded in Keras. No manual download required.

```python
from tensorflow.keras.datasets import mnist
(X_train, y_train), (X_test, y_test) = mnist.load_data()
