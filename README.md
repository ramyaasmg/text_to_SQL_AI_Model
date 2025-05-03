# 🧠 Text-to-SQL Converter using LangChain, Groq, and Chroma

This project converts natural language questions into SQL queries using an LLM (Groq API), LangChain framework, and a Chroma vector database created from PDF SQL schema files.

---

## 🚀 Features

- 🗂 Ingests SQL schema and example queries from PDF files
- 🔍 Vector search using Chroma DB and HuggingFace embeddings
- 💬 Converts user questions to SQL using Groq's LLM
- ⚠️ Detects potentially harmful queries like DROP/DELETE/ALTER
- 📖 Explains the generated SQL queries in simple terms (optional)

---

## 🧩 Technologies Used

- `LangChain`
- `Groq` LLM API
- `Chroma` Vector Store
- `HuggingFace` Sentence Transformers
- `PyPDFLoader` for document ingestion

---


