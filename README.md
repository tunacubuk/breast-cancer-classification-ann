# Breast Cancer Classification with Artificial Neural Networks (ANN)

This project implements an **Artificial Neural Network (ANN)** to classify breast cancer data as benign or malignant using **TensorFlow** and **Keras**. It was developed as part of my studies in **Management Information Systems** at **Muğla Sıtkı Koçman University**.

## 📊 Project Overview
The model processes a breast cancer dataset to predict diagnosis based on various features. Key steps include:
* **Data Cleaning**: Handling missing values and converting categorical strings to numeric types.
* **Preprocessing**: Feature scaling using `MinMaxScaler` to normalize data between 0 and 1.
* **Neural Network Architecture**:
    * **Input Layer**: Automatically matches the number of features.
    * **Hidden Layer**: 5 nodes with **ReLU** activation.
    * **Output Layer**: 1 node with **Sigmoid** activation for binary classification.

## 📈 Performance Results
The model achieved high accuracy and reliable performance metrics:
* **Accuracy (ACC)**: **97%**
* **R2 Score**: **0.87**
* **Confusion Matrix**: High precision and recall for both classes.

## 🛠️ Tech Stack
* **Language**: Python
* **Libraries**: 
    * `pandas`, `numpy` for data manipulation.
    * `tensorflow.keras` for deep learning.
    * `scikit-learn` for preprocessing and evaluation metrics.

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/tunacubuk/breast-cancer-classification.git](https://github.com/tunacubuk/breast-cancer-classification.git)
