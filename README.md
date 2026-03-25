# 📌 Resume Category Predictor

## 📖 Overview
The Resume Category Predictor is a Machine Learning + NLP-based project that automatically classifies resumes into predefined job categories such as Data Science, HR, Web Developer, etc.

This system helps automate the resume screening process, reducing manual effort and improving efficiency in recruitment.

---

## 🎯 Objective
- Automatically classify resumes into job categories
- Reduce manual HR screening effort
- Improve speed and accuracy of resume filtering
- Apply NLP techniques for text processing
- Build a reliable ML classification model

---

## 🧠 Approach

### 1. Data Preprocessing
- Removed punctuation, numbers, URLs
- Converted text to lowercase
- Removed stopwords
- Applied lemmatization

### 2. Feature Extraction
- Used **TF-IDF Vectorizer** to convert text into numerical format

### 3. Model Building
- Trained multiple models:
  - Support Vector Machine (SVM) ✅ (Best)
  - Random Forest
  - KNN Classifier

### 4. Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Dataset
The dataset consists of resumes labeled into categories such as:

- Data Science  
- HR  
- Mechanical Engineer  
- Web Developer  
- Python Developer  
- Java Developer  
- Business Analyst  
- Civil Engineer  
- And more...

Each entry contains:
- Resume Text
- Category (Target Label)

---

## 🛠️ Tech Stack

### 💻 Language
- Python

### 📚 Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- re (Regex)

---

## ⚙️ Model Performance

| Model            | Accuracy |
|------------------|---------|
| SVM              | 1.000 ✅ |
| Random Forest    | 1.000 |
| KNN              | 0.9989 |

👉 SVM performed best with highest stability and accuracy.

---

## 📈 Results
- High classification accuracy
- Clear distinction between categories
- Strong precision and recall
- Effective for real-world resume screening

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/Resume-Category-Predictor.git
