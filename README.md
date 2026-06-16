# Resume Screening & Candidate Ranking System

## 📌 Project Overview
This project focuses on building a **Machine Learning–based Resume Screening and Candidate Ranking System** using Natural Language Processing (NLP).

Hiring teams receive hundreds of resumes for a single role, making manual screening time-consuming and inefficient. This system automates the process by:

- Extracting resume text
- Matching resumes with a job description
- Ranking candidates based on relevance
- Identifying missing skills

The goal is to help recruiters shortlist candidates faster and improve hiring efficiency.

---

## 🎯 Objectives
The project aims to:

✔ Extract resume text from PDF files  
✔ Clean and preprocess resume data  
✔ Compare resumes with job descriptions  
✔ Rank candidates based on similarity score  
✔ Identify missing and matched skills

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Development Environment
- Google Colab / Jupyter Notebook

### Libraries Used
- Pandas
- NumPy
- PyPDF2
- Scikit-learn
- NLTK
- Matplotlib

---

## 📂 Dataset
Dataset used:

**Resume Dataset (Kaggle)**

The dataset contains resumes from different professional domains in PDF format.

Sample categories include:
- Advocate
- Accountant
- BPO
- Engineering
- HR
- Data Science

For this project, sample resume PDFs were uploaded and analyzed.

---

## ⚙️ Project Workflow

### 1. Resume Upload & Text Extraction
- Uploaded resume PDF files
- Extracted resume text using **PyPDF2**

### 2. Text Preprocessing
Performed preprocessing tasks:

- Lowercasing
- Text cleaning
- Removing unnecessary symbols

### 3. Job Description Matching
Created a sample job description and compared resumes against it.

Example role:
**Advocate / Legal Professional**

Required skills included:
- Legal knowledge
- Communication
- Research
- Documentation
- Client handling
- Drafting

### 4. Feature Extraction
Used **TF-IDF Vectorization** to convert resume text into numerical features.

### 5. Resume Similarity Scoring
Applied **Cosine Similarity** to compare resumes with the job description and calculate match scores.

### 6. Candidate Ranking
Candidates were ranked based on job relevance scores.

### 7. Skill Gap Analysis
Identified:
- Matched skills
- Missing skills

to explain why certain resumes ranked higher.

---

## 📊 Results
### Candidate Ranking
- Resume similarity scores generated
- Candidates ranked successfully

### Skill Gap Analysis
- Missing skills identified
- Matched skills highlighted

The system successfully demonstrated how recruiters can automate candidate shortlisting.

---

## 📈 Business Impact
This system helps organizations:

- Reduce recruiter workload
- Speed up resume screening
- Improve hiring decisions
- Identify skill gaps
- Shortlist relevant candidates faster

---

## 🚀 Future Improvements
Possible enhancements include:

- Using spaCy for advanced NLP
- Extracting skills automatically
- Supporting multiple job descriptions
- Adding weighted skill scoring
- Using BERT/transformer models for better matching

---

## 📌 Repository Structure

```bash
├── Resume_Screening_System.ipynb
├── README.md
└── sample_resume_pdfs/
```

---

## Author
**Niharika Reddem**

Machine Learning Internship Project – Future Interns (2026)
