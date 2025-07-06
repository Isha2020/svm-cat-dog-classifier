# Cat vs Dog Image Classification using SVM  
**Internship Task-03 – Prodigy InfoTech**

This project implements a Support Vector Machine (SVM) model to classify grayscale images of cats and dogs based on basic image processing and machine learning techniques.

---

## 📁 Dataset
- Custom dataset with 426 grayscale images resized to 64x64 pixels.
- Folder structure:
- data/
├── cats/
└── dogs/

---

## 🔧 Tech Stack
- Python
- OpenCV
- NumPy
- Scikit-learn

---

## 🚀 Project Workflow

1. Load and preprocess images (grayscale + resize + flatten)
2. Label: `0 = Cat`, `1 = Dog`
3. Train-test split (80-20)
4. Train a Support Vector Machine (SVM) with a linear kernel
5. Evaluate performance using accuracy, classification report & confusion matrix

---

## 📊 Results

- ✅ **Accuracy**: 60.4%
- 🐱 **F1-Score (Cats)**: 0.72
- 🐶 **F1-Score (Dogs)**: 0.35

> ⚠️ The trained `.pkl` model file is not included due to size restrictions.  
> You can retrain the model by running the `svm_classifier.py` script.

---

## 📂 Files Included

- `svm_classifier.py` → Model training and evaluation code
- `README.md` → Project overview and results

---

## 🧑‍💻 Author

**Isha Sarkar**  
Machine Learning Intern – Prodigy InfoTech  
July 2025

