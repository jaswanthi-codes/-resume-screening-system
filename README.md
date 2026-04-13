# 📄 Automatic Resume Screening System (NLP)

## 📌 Overview
This project is an Automated Resume Screening System built using Natural Language Processing (NLP). It helps recruiters filter and rank resumes based on their relevance to a given job description.

The system processes resume text, extracts meaningful information, and compares it with job requirements to identify the best candidates efficiently.

---

## 🛠️ Tech Stack
- Python  
- Natural Language Processing (NLP)  
- Scikit-learn  
- Pandas  
- NumPy  

---

## 🚀 Features
- Resume text preprocessing (cleaning, tokenization)  
- Keyword extraction from resumes  
- Job description matching  
- Candidate ranking using cosine similarity  
- Fast and efficient screening process  

---

## ⚙️ How It Works
1. User enters a job description  
2. System preprocesses resumes and job description  
3. Converts text into vectors using TF-IDF  
4. Calculates similarity using cosine similarity  
5. Ranks resumes based on matching score  

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/resume-screening-system.git
cd resume-screening-system
pip install -r requirements.txt
