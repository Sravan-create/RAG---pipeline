# 🧠 Simple RAG with LangChain, FAISS/Chroma & LLaMA2 (Ollama)

This project demonstrates a flexible **Retrieval-Augmented Generation (RAG)** pipeline built using **LangChain** and **LLaMA2** via **Ollama**, designed to process and retrieve answers from **text files**, **PDF documents**, and **web pages**.

---

## 🚀 Features

- 📄 Load and process `.txt` and `.pdf` documents
- 🌐 Scrape and parse any webpage (like Wikipedia)
- 🔍 Split content into semantic chunks
- 📦 Embed chunks using `OllamaEmbeddings` (LLaMA2)
- 🧠 Store and retrieve using FAISS or Chroma vector DB
- 💬 Ask questions and get AI-generated answers using LLaMA2 locally

---

## 🛠️ Requirements

- Python 3.10+
- [Ollama](https://ollama.com/) installed locally
- Required Python libraries (install with pip)

```bash
pip install langchain bs4 chromadb faiss-cpu pypdf
