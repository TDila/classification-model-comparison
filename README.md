# Classification Model Comparison – Final Year Project

This project involves a comparative analysis of three classification models:
- **Support Vector Machine (SVM)**
- **Naïve Bayes (GaussianNB)**
- **Deep Neural Network (DNN)**

The models are trained on the **Car Evaluation Dataset** from the UCI Machine Learning Repository.

---

## 📁 Folder Structure

project-root/
├── data/
│ ├── processed_train.csv
│ ├── processed_test.csv
│ ├── train_labels.csv
│ └── test_labels.csv
│
├── notebooks/
│ ├── car_dataset_preprocessing.ipynb
│ ├── svm_model.ipynb
│ ├── naive_bayes_model.ipynb
│ └── dnn_model.ipynb
│
├── results/
│ ├── confusion_matrix.png
│ ├── loss_accuracy_curves.png
│ └── model_comparison_metrics.png
│
├── report.pdf
├── requirements.txt
└── README.md

## 📊 Dataset Description

- **Source**: [UCI Car Evaluation Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation)
- **Samples**: 1,728
- **Features**: 6 (all categorical)
- **Target Classes**: 4 (`unacc`, `acc`, `good`, `vgood`)

---

## 🛠️ Technologies Used

- Python 3.x
- Google Colab / Jupyter Notebooks
- scikit-learn
- pandas
- TensorFlow / Keras
- seaborn, matplotlib

---

## 📌 Authors

- **Member 1 – Dataset & Preprocessing**: G. B. Tharusha Dilhara
- **Member 2 – SVM & Naïve Bayes Implementation**
- **Member 3 – Deep Neural Network Implementation**

---

## 📎 Project Submission

- 📂 GitHub Repository: https://github.com/TDila/classification-model-comparison
- 📄 PDF Report: Included in `report.pdf`