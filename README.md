# PRODIGY_ML_03
Cat and Dog SVM Classification

---

# 🐱🐶  Cat vs Dog Image Classification using SVM

## 📌 Overview

This project is part of my internship tasks, where the goal is to build a **Support Vector Machine (SVM)** model to classify images of **cats** and **dogs**.
We use the **Kaggle Cats vs Dogs dataset**, preprocess the images, train an SVM model, and evaluate its performance.

---

## 🗂️ Project Structure

```
PRODIGY_ML_03/
│
├── dataset/                # Dataset folder (Cat and Dog images)
├── svm_classifier.ipynb # Jupyter Notebook with code
├── requirements.txt     # Dependencies
├── classifier.pkl       # Trained SVM model (saved)
└── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Soundar586/PRODIGY_ML_03.git
cd PRODIGY_ML_03
```

### 2️⃣ Install Dependencies

Make sure you have **Python 3.8+** installed.

```bash
pip install -r requirements.txt
```

---

## 📊 Dataset
I use the **Kaggle Dogs vs Cats dataset**:

* [Dataset Link](https://www.kaggle.com/c/dogs-vs-cats/data)
* Contains 25,000 images (cats and dogs).
* I give the sample data for the clarification in the file

### Dataset Preparation

1. Download the dataset from Kaggle.
2. Place it inside the `dataset/` folder.
---

## 🛠️ How It Works

1. **Image Preprocessing**

   * Resize all images to **64x64 pixels**.
   * Convert to grayscale or keep RGB depending on the model.
   * Flatten image arrays for SVM.

2. **Model Training**

   * Use `sklearn.svm.SVC` with a linear or RBF kernel.
   * Fit model on training data.

3. **Evaluation**

   * Calculate **accuracy** and plot a **confusion matrix**.

---

## 🚀 Usage

### Run in Jupyter Notebook

```bash
jupyter notebook svm_classifier.ipynb
```

Inside the notebook:

* Train the SVM model
* Test predictions
* View classification results

---

## 📈 Results

* **Model Accuracy:** \~85–90% (depending on preprocessing & kernel)
* Works well on clean, centered cat/dog images.
* Struggles with noisy backgrounds.

---

## 🔮 Future Improvements

* Use **deep learning (CNN)** for higher accuracy.
* Data augmentation for better generalization.
* Build a **Flask web app** for live predictions.

---

## 📜 License

This project is for educational purposes. You are free to modify and use it for learning.

---
