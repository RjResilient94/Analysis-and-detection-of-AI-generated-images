# 🧠 Analysis and Detection of AI-Generated Images

## 📌 Overview

This project explores the detection of AI-generated images using **traditional image processing** and **classical machine learning** techniques — completely avoiding deep learning models.

It focuses on extracting structural and geometric features from facial images using **Hough** and **Radon transforms**. These features are then used to train a **logistic regression classifier** to distinguish between real and synthetically generated faces.

---

## 📊 Dataset

- **Real Images:** CiFake Dataset  
- **AI-Generated Images:** CiFake Dataset
- Images are preprocessed into grayscale and passed through edge detection and feature transformation pipelines

---

## ⚙️ Tech Stack

- **Language:** Python 3  
- **Libraries:** NumPy, OpenCV, scikit-learn, matplotlib  
- **Transforms Used:** Hough Transform, Radon Transform  
- **Model:** Logistic Regression  
- **Tools:** Jupyter Notebooks, GitHub

---

## 📈 Results

- Achieved classification accuracy using **logistic regression on Radon-based features**
- Feature engineering led to meaningful geometric separation between real and synthetic images
- Demonstrated the viability of traditional ML approaches for synthetic image detection

---

## 🚀 Project Structure

```
Analysis-and-detection-of-AI-generated-images/
├── notebooks/          # Exploratory notebooks and feature analysis
├── src/                # Feature extraction, training logic
├── data/               # Placeholder for dataset or loader script
├── results/            # Plots, logs, confusion matrix
├── model/              # Trained model file (e.g., .pkl)
├── requirements.txt    # Dependencies
├── README.md           # This file
```

---

## ▶️ How to Run

```bash
git clone https://github.com/RjResilient94/Analysis-and-detection-of-AI-generated-images
cd Analysis-and-detection-of-AI-generated-images
pip install -r requirements.txt
```

Then open the notebook or run `src/train.py`

---

## 📌 Future Scope

- Add explainability using SHAP for logistic regression  
- Combine Radon + Hough features with statistical texture descriptors  
- Package into a Streamlit app for real-time detection  

---

## 🧑‍💻 Author

**Rajesh Padmanabhan**  
M.Tech in Applied AI – VNIT Nagpur  
Java Backend Engineer | AI Enthusiast  
📧 rajeshraaj64@gmail.com  
🌐 [LinkedIn](https://linkedin.com/in/rajeshraaj64)

---

> “When deepfakes blur the line, geometry tells the truth.”
