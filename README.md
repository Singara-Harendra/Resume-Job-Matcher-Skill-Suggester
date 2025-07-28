# 📄 Resume Analyzer & Job Matcher with Skill Suggestions (NLP-based)

This project is an intelligent **Resume to Job Matcher** tool built using **NLP** and **semantic search**. It extracts content from a resume PDF, compares it with job descriptions in a CSV, ranks the best matches, and suggests **skills to learn** based on gaps between your resume and job expectations.

---

## 🚀 Features

- 📌 Extract text from **resume PDFs**
- 🔍 Analyze and **match with job descriptions** using Sentence Transformers
- 🧠 Extract and compare **skills**
- ✅ Display top 5 job matches with relevance scores
- 💡 Suggest **skills you’re missing** across top jobs

---

## 📦 Libraries Used

```bash
pip install sentence-transformers pdfplumber pandas scikit-learn nltk
