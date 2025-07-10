# 🧠 Resume Screening Assistant

An AI-powered project that automates the classification of resumes into job categories (e.g., **Data Science**, **Software Development**, **HR**, etc.) using natural language understanding, foundation models, and prompt engineering.

---

## 📌 Project Overview

Recruiters often face the challenge of manually shortlisting hundreds of resumes for each role. This Resume Screening Assistant leverages **IBM watsonx.ai**, **Prompt Lab**, and **Foundation Models** to intelligently classify resumes into predefined job roles using resume content (skills, experience, keywords, etc.).

---

## 🎯 Goals

- ✅ Automate resume role classification using AI
- ✅ Reduce manual screening effort for recruiters
- ✅ Group resumes by job roles with high accuracy
- ✅ Support resumes in PDF and CSV formats

---

## ⚙️ Tools & Technologies

| Component          | Description                                  |
|-------------------|----------------------------------------------|
| `IBM watsonx.ai`  | Foundation model inference and prompt design |
| `Prompt Lab`      | No-code prompt interface for model testing   |
| `Python`          | Resume text extraction and preprocessing     |
| `PyPDF2 / pandas` | For handling PDF and CSV resume inputs       |
| `Granite-13b / FLAN` | Foundation models used for classification |

---

## 📂 Project Structure

📁 Resume-Screening-Assistant/
│
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 app.py or notebook.ipynb
├── 📁 data/
│ ├── All_Resumes.pdf
│ └── classified_resumes.csv
├── 📁 outputs/
│ └── categorized_resumes.csv
