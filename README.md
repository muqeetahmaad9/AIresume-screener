# 📄 AI Resume Screener Web App

A smart, AI-powered resume screener that compares a candidate's resume with a job description to generate a score based on skill match, education, and experience. Built using **Python**, **Streamlit**, and **NLP techniques**.

![Streamlit App Screenshot]![image](https://github.com/user-attachments/assets/2b622a48-d9bd-44b7-b4d7-0a60f0f555ac)
) <!-- Replace with real image later -->

---

## 🚀 Features

✅ Upload Resume (PDF or DOCX)  
✅ Paste or Upload Job Description (TXT)  
✅ Extract Skills, Education, and Experience  
✅ Match Resume with JD using NLP (TF-IDF + Cosine Similarity)  
✅ Calculate & Display Candidate Match Score  

---

## 🛠 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Libraries**: 
  - `pdfminer.six`, `docx2txt` (for resume parsing)
  - `scikit-learn` (for TF-IDF and similarity)
  - `re` and `NLP` for keyword extraction

---

## 🧪 How It Works

1. **Resume is parsed** to extract raw text.
2. Text is analyzed to extract:
   - Skills (e.g., Python, Flask)
   - Education (Bachelor, MSc, etc.)
   - Years of Experience
3. Job Description (JD) is compared with resume using **TF-IDF vectorization**.
4. A **similarity score** is generated.
5. Candidate is **ranked** based on score + skill match.

---

## 📦 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/ai-resume-screener.git
cd ai-resume-screener
