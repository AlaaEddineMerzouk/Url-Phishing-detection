# 🔐 Malicious URL Detection Using Machine Learning

This project is part of a mini-project for the **Data Security** module (Academic Year 2024/2025). It presents an AI-based solution to detect malicious URLs using various machine learning models.

## 📚 Project Description

Cybercriminals often use malicious URLs in phishing, malware distribution, and defacement attacks. This project aims to build and evaluate several machine learning models to classify URLs as:

- **Benign**
- **Phishing**
- **Defacement**
- **Malware**

The dataset and feature extraction techniques enable a robust model for accurate classification.

---

## 📁 Files in this Repository

- `malicious-urls.ipynb`: The main Jupyter notebook containing all code for preprocessing, model training, and evaluation.
- `README.md`: This file, providing an overview of the project.

---

## 🧠 Models Used

The following ML algorithms were implemented and evaluated:

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | ~96%     | High      | High   | High     |
| MultinomialNB       | ~92%     | Medium    | Medium | Medium   |
| Random Forest       | ~96%     | High      | High   | High     |
| Decision Tree       | ~95%     | Medium    | Medium | Medium   |
| SVM (Linear Kernel) | ~94%     | High      | High   | High     |

---

## 🧾 Dataset

- **Source**: [Kaggle - Malicious URLs Dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset/data)
- **Features**: Raw URLs and class labels
- **Classes**: Benign, Phishing, Defacement, Malware

---

## ⚙️ Steps Performed

1. **Data Loading & Cleaning**
2. **Label Encoding**
3. **TF-IDF Feature Extraction**
4. **Train/Test Split**
5. **Model Training (5 models)**
6. **Evaluation & Comparison**
7. **Confusion Matrix & Classification Report**

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/malicious-url-detection.git
   cd malicious-url-detection
