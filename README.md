
# 🧠 Resume Parser using Transformer-based Named Entity Recognition

## 🎯 Objective

This project is an **AI-powered resume parser** that uses Transformer-based Named Entity Recognition (NER) to extract structured information from unstructured resumes (.pdf/.txt). It automates the resume screening process for HR, recruitment, and talent acquisition workflows.

---

## 🚀 Use Case

✅ Parse resumes  
✅ Extract key fields: **Name, Skills, Degree, Institution, Work Experience**  
✅ Format the data for HR dashboards, ATS systems, or ML pipelines  
✅ Simulate real-world hiring automation

---

## ⚙️ Technologies Used

| Tool/Library        | Purpose                                |
|---------------------|----------------------------------------|
| 🐍 Python           | Core programming language              |
| 🤗 Hugging Face     | Pretrained BERT NER model               |
| `pdfminer.six`      | Extract text from PDF resumes          |
| `re` (regex)        | Extract emails, phone numbers, etc.    |
| Google Colab        | Interactive development & testing      |

---

## 🧪 Approach

1. 📂 **Upload** resume files (`.txt` or `.pdf`)
2. 📄 **Extract raw text** using `pdfminer` or file read
3. 🤖 **Run BERT-based NER** using Hugging Face Transformers pipeline
4. 🧠 **Post-process** entities:
   - Classify into: `Name`, `Skills`, `Degree`, `Institution`, `Experience`
   - Match skills using keyword/enhanced list (optional)
5. 📊 **Display structured results**

---

## 🧰 Sample Output

```json
{
  "Name": "John Doe",
  "Skills": ["Python", "Machine Learning", "TensorFlow"],
  "Degree": "B.Tech in Computer Science",
  "Institution": "ABC University",
  "Work Experience": "2 years as Data Scientist at XYZ Corp"
}
````

---

## 📈 Possible Enhancements

* [ ] 🔁 **Batch processing** for multiple resumes
* [ ] 🌐 **Streamlit or Gradio interface**
* [ ] 🧠 **Fine-tune the NER model** on domain-specific resumes
* [ ] 📥 Export results to **CSV / Excel / JSON**
* [ ] 📂 Upload via drag & drop in UI

---

## 🧩 Folder Structure

```
.
├── NER_NLP.py          # Core parsing logic
├── sample_resume.pdf         # Input test resume
├── README.md                 # This file
```

---


