# ✍️ Handwritten Digit Recognition using Artificial Neural Networks (ANN)

**Author:** Gargi

**Registration Number:** 23BCE11333

**Application Number:** IN26011023

**Batch Number:** 2B

**Email ID:** [gargi.23bce11333@vitbhopal.ac.in](mailto:gargi.23bce11333@vitbhopal.ac.in)

---

## 📌 Objective

The objective of this project is to develop an **Artificial Neural Network (ANN)** using **TensorFlow/Keras** to accurately classify handwritten digits (0–9) from the **MNIST dataset**. The model demonstrates how feedforward neural networks can learn complex patterns from image data and automate handwritten digit recognition tasks such as postal code and document processing.

---

## 📂 Dataset

* **Dataset:** MNIST in CSV (Kaggle)
* **Images:** 60,000 handwritten digit images
* **Image Size:** 28 × 28 pixels (784 features)
* **Classes:** 10 (Digits 0–9)

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Scikit-learn
* Kaggle API

---

## ⚙️ Methodology

### 1. Data Understanding

* Explored the dataset structure and class distribution.
* Visualized handwritten digit samples.
* Verified image dimensions (28 × 28 pixels).

### 2. Data Preprocessing

* Checked for missing values.
* Normalized pixel values from **0–255** to **0–1**.
* Split the dataset into **80% training** and **20% testing**.
* Applied **One-Hot Encoding** to target labels.

### 3. ANN Architecture

| Layer          | Configuration        |
| -------------- | -------------------- |
| Input Layer    | 784 Features         |
| Hidden Layer 1 | 128 Neurons (ReLU)   |
| Hidden Layer 2 | 64 Neurons (ReLU)    |
| Output Layer   | 10 Neurons (Softmax) |

### 4. Model Training

* **Optimizer:** Adam
* **Loss Function:** Categorical Crossentropy
* **Evaluation Metric:** Accuracy
* **Epochs:** 10
* **Framework:** TensorFlow/Keras

### 5. Model Evaluation

The trained model was evaluated using:

* Test Accuracy
* Test Loss
* Confusion Matrix
* Classification Report
* Accuracy vs Epoch Graph
* Loss vs Epoch Graph

---

## 🧠 Model Summary

| Layer           | Output Shape | Parameters |
| --------------- | ------------ | ---------: |
| Dense (ReLU)    | (None, 128)  |    100,480 |
| Dense (ReLU)    | (None, 64)   |      8,256 |
| Dense (Softmax) | (None, 10)   |        650 |

**Total Trainable Parameters:** **109,386**

---

## 📊 Results

| Metric             |      Value |
| ------------------ | ---------: |
| **Test Accuracy**  | **97.41%** |
| **Test Loss**      | **0.0983** |
| **Macro F1-Score** | **0.9739** |

The model successfully learned meaningful representations of handwritten digits and achieved excellent classification performance on unseen test data.

---

## ✅ Key Features

* Artificial Neural Network built using TensorFlow/Keras
* Multi-class handwritten digit classification
* Data normalization and one-hot encoding
* Comprehensive model evaluation using multiple metrics
* Training and validation performance visualization

---

## 📌 Conclusion

This project demonstrates the effectiveness of **Artificial Neural Networks** for handwritten digit recognition. The proposed ANN achieved **97.41% test accuracy**, indicating its ability to accurately learn complex patterns from image data.

Although fully connected neural networks perform exceptionally well on relatively simple datasets such as MNIST, **Convolutional Neural Networks (CNNs)** generally provide superior performance on larger and more complex image classification tasks by efficiently capturing spatial features and translation invariance.

Overall, this project provides a strong foundation for understanding deep learning workflows, neural network architecture design, image preprocessing, and model evaluation using TensorFlow and Keras.
