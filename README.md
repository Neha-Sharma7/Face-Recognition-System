# 🧠 Face Recognition System using PCA & SVM

## 📌 Project Overview

This project implements a **Face Recognition System** using classical machine learning techniques. It uses **Principal Component Analysis (PCA)** for dimensionality reduction (Eigenfaces) and **Support Vector Machine (SVM)** for classification.

The system processes an image dataset, extracts meaningful facial features, and accurately predicts the identity of individuals.

---

## 🎯 Objectives

* Build a face recognition pipeline using ML techniques
* Reduce high-dimensional image data using PCA
* Train a robust SVM classifier
* Evaluate model performance on unseen images

---

## 🧩 Project Structure

```
face-recognition-pca-svm/
│
├── notebook/
│   └── Face_Recognition_System.ipynb
│
├── dataset/ (optional / ignored if large)
│
├── outputs/
│   ├── sample_prediction.png
│   ├── accuracy_graph.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Tech Stack

* **Language:** Python
* **Libraries:**

  * NumPy
  * Pandas
  * OpenCV
  * Scikit-learn
  * Matplotlib

---

## 🧠 Methodology

### 🔹 1. Data Preprocessing

* Convert images to grayscale
* Resize images to uniform size
* Flatten images into vectors

---

### 🔹 2. Feature Extraction (PCA)

* Reduce dimensionality of image data
* Extract principal components (Eigenfaces)
* Retain maximum variance

---

### 🔹 3. Model Training (SVM)

* Train SVM classifier on extracted features
* Use labeled dataset for supervised learning

---

### 🔹 4. Prediction

* Input a new image
* Apply PCA transformation
* Predict identity using trained SVM model

---

## 📂 Dataset

Due to size limitations, the dataset is hosted externally:

👉 **Download Dataset:** [https://drive.google.com/drive/folders/1YSrUedT9rIs_VDqhCJqGx3iUMLekZURT?usp=drive_link]

### Dataset Description:

* Images organized in folders (one per person)
* Each folder contains multiple face images
* Used for supervised classification

---

## ▶️ How to Run

### 🔹 Run on Google Colab

1. Open the notebook
2. Download dataset from link
3. Upload dataset to Colab
4. Update dataset path
5. Run all cells

---

### 🔹 Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/face-recognition-system.git
cd face-recognition-system
pip install -r requirements.txt
jupyter notebook
```

---

## 📊 Results

* Efficient face recognition achieved using PCA + SVM
* Reduced computation using dimensionality reduction
* Good classification performance on test data

👉 Add your actual accuracy here (e.g., **Accuracy: 90%**)

---

## 📸 Output

* Face prediction results
* Accuracy visualization
* PCA feature representation

(Add screenshots inside `/outputs` folder)

---

## 🚀 Future Improvements

* Real-time face recognition using webcam
* Deep learning models (CNN, FaceNet)
* Web deployment using Flask/Django
* Improve dataset size and diversity

---

## 💡 Key Learnings

* Practical implementation of PCA
* Understanding of SVM classifier
* Image preprocessing techniques
* End-to-end ML pipeline

---

## 👩‍💻 Author

**Neha Sharma**
B.Tech IT | AI & Data Science Enthusiast

---

## 📌 Note

This project demonstrates classical machine learning approaches for face recognition and serves as a foundational implementation before moving to deep learning techniques.
