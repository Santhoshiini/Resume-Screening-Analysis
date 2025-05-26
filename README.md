# 📂 Resume Screening Analysis using NLP & ML

This project uses **Natural Language Processing (NLP)** and **Machine Learning** to automatically classify resumes into job categories such as **Data Scientist**, **Software Engineer**, **Product Manager**, and **Other**.

---

## 🎯 Project Objective

Automate the resume shortlisting process by:

✅ Cleaning and preprocessing raw resume data  
✅ Extracting features using TF-IDF  
✅ Training a model to predict job categories based on resume content  

---

## 📊 Dataset

📌 **Source:** [Kaggle - AI Resume Screening Dataset](https://www.kaggle.com/datasets/sohrabbahari/ai-resume-screening-dataset)  
📦 **Records:** 2,484 resumes  
📄 **Columns:**
- `ID`: Resume ID
- `Resume_str`: Raw resume text
- `Resume_html`: HTML-formatted resume
- `Category`: Job label
- `Cleaned_Resume`: Preprocessed resume text (optional)

> ⚠️ **Note:** Download the dataset manually and place it in the `/data` folder.

---

## 🛠️ Technologies Used

- 🐍 Python
- 📊 Pandas, NumPy
- 🤖 Scikit-learn
- 🧹 NLTK
- 📈 Matplotlib, Seaborn
- ☁️ WordCloud
- 📚 Logistic Regression

---

## 📌 Key Features

🔹 Resume text cleaning and preprocessing  
🔹 TF-IDF feature extraction  
🔹 WordCloud visualizations per category  
🔹 ML model for job classification  
🔹 Model evaluation with accuracy, F1-score, and confusion matrix  

---

## 📈 Results

✅ Achieved approximately **80–85% accuracy** with Logistic Regression.

---

## 📁 Folder Structure

