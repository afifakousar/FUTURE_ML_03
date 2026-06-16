# FUTURE_ML_03
Resume Screening &amp; Candidate Ranking System using Machine Learning  This project builds an NLP-based resume screening system that automatically analyzes resumes, extracts key skills, and ranks candidates based on their relevance to a given job description. 
# 📄 Resume Screening & Ranking System (ML Task 3)

## 🚀 Overview

This project is a **Machine Learning-based Resume Screening System** that automatically analyzes resumes, extracts skills, matches them with job descriptions, and ranks candidates based on suitability.

It is designed to simulate real-world HR-tech systems used in recruitment platforms.

---

## 🎯 Objective

The system performs the following:

- Reads resume text data
- Cleans and preprocesses text using NLP
- Extracts relevant skills from resumes
- Compares resumes with job descriptions
- Generates a **match score**
- Ranks candidates based on job fit
- Identifies missing or required skills

---

## 🧠 Problem Statement

Recruiters face challenges such as:
- Large volume of resumes
- Time-consuming manual screening
- Inconsistent candidate evaluation
- Difficulty in identifying skill gaps

This project solves these issues using **NLP + Machine Learning**.

---

## 🛠️ Technologies Used

- Python 🐍  
- Pandas  
- Scikit-learn  
- spaCy  
- NLP (Natural Language Processing)  
- TF-IDF Vectorization  
- Cosine Similarity  
- Jupyter Notebook  

---

## 📁 Project Structure
FUTURE_ML_03/
│
├── data/
│ └── resumes.csv
│
├── notebooks/
│ └── task3_resume_screening.ipynb
│
├── outputs/
│ └── (plots, rankings, results)
│
└── README.md

---

## ⚙️ Workflow

### 1️⃣ Data Preparation
- Created dataset of resumes and job roles
- Structured unstructured text data

### 2️⃣ Text Preprocessing
- Lowercasing
- Removing punctuation
- Cleaning text

### 3️⃣ Skill Extraction
- Defined skill keywords
- Extracted relevant skills from resumes

### 4️⃣ Feature Engineering
- Applied TF-IDF Vectorization
- Converted text into numerical format

### 5️⃣ Similarity Matching
- Used Cosine Similarity
- Compared resumes with job descriptions

### 6️⃣ Ranking System
- Sorted candidates based on match score
- Higher score = better job fit

### 7️⃣ Skill Gap Analysis
- Identified missing skills per candidate

---

## 📊 Sample Output

| Resume | Job Role | Match Score |
|--------|----------|-------------|
| Resume A | ML Engineer | 0.92 |
| Resume B | Data Scientist | 0.85 |
| Resume C | Backend Developer | 0.70 |

---

## 💡 Key Features

✔ Resume text cleaning & preprocessing  
✔ Skill extraction using NLP  
✔ Job description matching  
✔ Candidate ranking system  
✔ Skill gap identification  

---

## 📈 Results

- Successfully ranked candidates based on job relevance  
- Extracted meaningful skills from resumes  
- Improved resume evaluation efficiency  
- Demonstrated real-world HR automation use case  

---

## 🚀 Conclusion

This project demonstrates how **NLP and Machine Learning** can be applied in HR-tech systems to automate resume screening, improve hiring efficiency, and support better recruitment decisions.

---

## 👩‍💻 Author

**Future Interns — Machine Learning Internship (Task 3)**

---

## 📌 How to Run

```bash
pip install pandas scikit-learn nltk spacy
python -m spacy download en_core_web_sm
```

Then open:

```
notebooks/task3_resume_screening.ipynb
```

Run all cells sequentially.

---

## ⭐ Outcome
✔ Fully working resume ranking system  
✔ NLP-based skill extraction  
✔ ML-based candidate scoring  
