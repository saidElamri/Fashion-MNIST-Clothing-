# 👕 Fashion MNIST Classification using TensorFlow

A deep learning project built with **TensorFlow** to classify clothing images from the **Fashion MNIST** dataset.  
Developed and documented by **Said Elamri** 👨‍💻.

---

## 📘 Overview

This project demonstrates how to build, train, and evaluate a neural network for image classification using the **Fashion MNIST** dataset.  
It uses **TensorFlow Keras**, **Matplotlib** for visualization, and includes **training curves**, **accuracy metrics**, and **image previews** of the dataset.

---

## 📂 Dataset

**Fashion MNIST** is a dataset of 70,000 grayscale images (28×28 pixels) in 10 categories:

| Label | Class Name |
|:------|:------------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

Each image represents a fashion item in one of these categories.

---

## 🧠 Model Architecture

The neural network is built using TensorFlow’s Sequential API:

```python
model = tf.keras.Sequential([
    tf.keras.layers.Flatten(input_shape=(28, 28)),
    tf.keras.layers.Dense(128, activation='relu'),
    tf.keras.layers.Dense(10, activation='softmax')
])

🧑‍💻 Author

Said Elamri
Data Science & AI Enthusiast
📍 Based in Morocco
🌐 Passionate about Machine Learning, Computer Vision, and TensorFlow projects.
