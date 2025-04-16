# 🤖 Hireis-AI-Powered-Resume-Ranker-using-GenAI

## 🔍 About the Project

**Resume Comparer** is a GenAI-driven system designed to help HR professionals streamline the candidate shortlisting process. It uses LLMs to extract structured data from resumes, stores that data in a vector database, and intelligently ranks candidates based on how well they match a given job description.

This project showcases the power of modern AI workflows in real-world use cases like recruitment, using embeddings, prompt engineering, and semantic search.

---

## 🚀 Features

- 📄 **PDF Resume Parsing** – Extracts resume content, even from scanned PDFs (with OCR fallback).
- 🧠 **LLM-based Information Extraction** – Pulls `name`, `skills`, `experience`, `email`, `project links`, and more using prompt-based instructions.
- 🔎 **Semantic Embeddings** – Transforms extracted data into embeddings for similarity comparison.
- 🗃️ **Vector Database Storage** – Stores candidates in a ChromaDB collection for efficient querying.
- 📝 **Job Description Matching** – Summarizes job roles and compares them with stored vectors to find top candidates.
- 📬 **Top Candidate Results** – Outputs names, email addresses, and project links of the best-fit applicants.

---

## 🧰 Tech Stack

- **Python**
- **LangChain** – LLM prompt chaining
- **Hugging Face Transformers / Sentence Transformers** – Embedding generation
- **ChromaDB** – Vector storage and search
- **PyMuPDF / PdfReader** – PDF content extraction

---
