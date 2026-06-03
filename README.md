# ⚖️ AI Legal Document Simplifier

An end-to-end NLP application that converts complex legal and formal documents into plain English using **LLaMA 3** via **Groq API**, with red flag detection, executive summary generation, and a downloadable Word report.

---

## 🚀 Live Demo

> Upload any PDF (legal contracts, government reports, terms & conditions) and get an instant simplified version.

---

## ✨ Features

- 📄 **PDF Text Extraction** — Extracts and processes text from any PDF document
- ✂️ **Smart Chunking** — Splits large documents into context-aware chunks using LangChain
- 🤖 **LLM Simplification** — Converts complex legal jargon into plain English using LLaMA 3
- 🚩 **Red Flag Detector** — Automatically identifies risky clauses (penalties, auto-renewal, data sharing, etc.)
- 📊 **Executive Summary** — Generates a structured high-level summary of the entire document
- 💾 **Download Report** — Export the full simplified document as a `.docx` Word file
- 🌐 **Streamlit Web App** — Clean, interactive UI with live progress tracking

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| LLM | LLaMA 3.1 8B via Groq API |
| Orchestration | LangChain |
| PDF Parsing | PyMuPDF (fitz) |
| Frontend | Streamlit |
| Export | python-docx |
| Language | Python 3.10+ |

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/legal-doc-simplifier.git
cd legal-doc-simplifier
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Get a free Groq API key
- Go to [console.groq.com](https://console.groq.com)
- Sign up → API Keys → Create new key

### 4. Run the app
```bash
streamlit run app.py
```

---

## 📖 How to Use

1. Enter your **Groq API key** in the sidebar
2. Select your preferred **LLaMA model**
3. Upload any **PDF document**
4. Click **Analyze Document**
5. View the **Executive Summary**, **Red Flags**, and **Simplified Sections**
6. Download the full **Simplified Report as .docx**

---

## 📁 Project Structure

```
legal-doc-simplifier/
│
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🖼️ App Preview

```
┌─────────────────────────────────────────────┐
│  ⚖️ AI Legal Document Simplifier            │
│  ─────────────────────────────────────────  │
│  📊 Executive Summary                        │
│  🚩 Red Flags Detected                       │
│  📄 Simplified Sections (expandable)         │
│  💾 Download Report (.docx)                  │
└─────────────────────────────────────────────┘
```

---

## ⚠️ Disclaimer

This tool is for **reference purposes only** and does not constitute legal advice. Always consult a qualified legal professional for legal matters.

---

## 👨‍💻 Author

**Deepak**
B.E. Electronics & Communication Engineering
Jeppiaar Engineering College, Anna University, Chennai

[![GitHub](https://img.shields.io/badge/GitHub-your--username-black?logo=github)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/your-profile)

---

## 📄 License

MIT License — free to use and modify.