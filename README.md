# AI-Semantic-Skill-Matching-and-Gap-Analyzer
# 📊 AI Semantic Skill Matching and Gap Analyzer

## 🚀 Project Overview
This project is an AI-powered Resume vs Job Description matching system.  
It compares resume text with job description text using Sentence Embeddings and Cosine Similarity to measure semantic similarity between them.

The system identifies:
- ✅ Matching Skills
- ❌ Missing Skills
- 📈 Match Percentage

The results are displayed in an interactive dashboard using Gradio.

---

# 🧠 Objective
The main objective of this project is to automate resume screening and skill gap analysis using AI and Natural Language Processing (NLP).

---

# 🤖 Technologies Used
- Python
- Gradio
- SentenceTransformers
- NumPy
- NLP (Natural Language Processing)

---

# ⚙️ How It Works

## Step 1: User Input
The user enters:
- Resume
- Job Description

## Step 2: Text Embeddings
The SentenceTransformer model converts both texts into numerical embeddings.

## Step 3: Similarity Calculation
Cosine similarity is used to calculate semantic similarity between the resume and job description.

## Step 4: Skill Gap Analysis
The system identifies:
- Matching skills
- Missing skills

## Step 5: Dashboard Output
Results are displayed in an interactive dashboard.

---

# 📊 Features
- AI-powered semantic matching
- Resume vs Job comparison
- Skill gap analysis
- Match score calculation
- Interactive dashboard UI
- Easy to use

---

# 🖥️ Dashboard Output
The dashboard displays:
- 📈 Match Score
- 🧠 Matching Skills
- 🔍 Missing Skills
- 💡 AI-based insights

---

# ▶️ How to Run the Project

## Install Required Libraries
```python
pip install gradio sentence-transformers numpy
