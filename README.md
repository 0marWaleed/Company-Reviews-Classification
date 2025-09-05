# 📝 Company Reviews Sentiment Analysis

## 🔍 Introduction
Understanding how customers feel about a company is essential for improving services and building trust.  
This project tackles the problem of analyzing **Arabic company reviews**, which are often written in **mixed styles** such as Franco-Arabic, dialects, or noisy text.  

By combining **custom preprocessing techniques** with **deep learning models**, the system can clean raw reviews, normalize them, and predict their sentiment (positive/negative/neutral) or rating.  
The outcome is a **data-driven view of customer opinions** that businesses can act upon.

---

## 🎯 Objectives
- Transform unstructured Arabic text into clean, usable data.  
- Handle challenges like Franco-Arabic numbers (`7 → ح`, `3 → ع`) and inconsistent spelling.  
- Build models to classify sentiment / ratings from customer reviews.  
- Provide insights that help companies **improve decision-making**.  

---

## 📁 Data Overview
The dataset consists of company reviews stored in a CSV file.  
Each record includes:  
- **Company name**  
- **Review description** (Arabic text, sometimes mixed with Franco-Arabic)  
- **Rating score** (numerical, used as sentiment label)  

---

## ⚙️ Approach

### 🧹 Text Preprocessing
- Removed non-Arabic reviews.  
- Normalized Arabic script (unified different forms of the same letter).  
- Converted Franco-Arabic numerals into proper Arabic characters.  
- Removed diacritics, repeated letters, punctuation, and stopwords.  

### 🤖 Modeling
- Transformed text into numerical features (TF-IDF, embeddings).  
- Trained classification models to predict sentiment from reviews.  
- Evaluated models using accuracy, precision, recall, and F1-score.  

---

## 📊 Key Insights
- Proper **normalization and cleaning** significantly boosted performance compared to raw text.  
- Machine learning models were able to **capture sentiment patterns** across different companies.  
- The pipeline can be adapted to other **Arabic text datasets** with minimal changes.  

*(Insert performance metrics, graphs, or confusion matrices here.)*

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/0marWalled/Company-Reviews-Classification.git
   cd Company-Reviews-Classification
