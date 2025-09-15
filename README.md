# 📄 Resume Screening System (AI-Powered)

A professional **AI-driven Resume Screening System** that automatically analyzes candidate resumes, compares them with job descriptions, and highlights matching skills using **NLP and Machine Learning**.

---

## 🚀 Features
✅ **Resume Parsing** – Extracts text from PDF resumes.  
✅ **Semantic Matching** – Uses Sentence-Transformers (`all-MiniLM-L6-v2`) for embeddings & cosine similarity.  
✅ **Skill Extraction** – Identifies relevant skills using spaCy NLP pipeline.  
✅ **Skill Gap Analysis** – Shows matched vs. missing skills for each candidate.  
✅ **Visual Report** – Generates a pie chart showing skill coverage.  
✅ **Interactive Interface** – Upload a resume & get results instantly via Gradio UI.  

---

## 🧠 Tech Stack
- **Language:** Python 3.8+
- **Libraries:**
  - [Sentence-Transformers](https://www.sbert.net/)
  - [spaCy](https://spacy.io/)
  - [Gradio](https://gradio.app/)
  - [Matplotlib](https://matplotlib.org/)
  - [PyMuPDF](https://pymupdf.readthedocs.io/)

---

## 📊 Example Output

```text
Match Score: 87%
Matched Skills: ['python', 'sql', 'data analysis']
Missing Skills: ['tableau', 'machine learning']
