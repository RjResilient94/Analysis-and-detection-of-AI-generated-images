# 🧠 Analysis and Detection of AI-Generated Images

## 📌 Overview

This project tackles the increasingly relevant problem of identifying AI-generated images using traditional image processing techniques and classical machine learning algorithms.

It explores the use of **Hough and Radon transforms** for feature extraction and evaluates models like **SVM** and **Logistic Regression** to distinguish between real and AI-generated content. This approach focuses on geometric features instead of deep neural network detection.

---

## 📊 Dataset

- **Real Images:** From [CelebA](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset
- **AI-Generated Images:** From [ThisPersonDoesNotExist](https://thispersondoesnotexist.com) and FakeFace datasets
- Number of samples: ~10,000 images across both classes
- Images are preprocessed using grayscale, edge detection, and feature transform pipelines

---

## ⚙️ Tech Stack

- **Languages:** Python 3
- **Libraries:** OpenCV, NumPy, scikit-learn, matplotlib
- **Transforms:** Hough, Radon
- **Models:** Support Vector Machine (SVM), Logistic Regression
- **Tools:** Jupyter Notebooks, GitHub, Google Colab

---

## 📈 Results

- Achieved **accuracy ~91%** using SVM with Radon + edge features
- Visualization of decision boundaries and confusion matrix included
- Detected overfitting in CNN baselines and pivoted to handcrafted features

---

## 🚀 Project Structure

