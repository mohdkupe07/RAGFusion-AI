# 🚀 RAGFusion-AI

## Hybrid RAG-Powered AI Chatbot (Cloud + Offline)

RAGFusion-AI is an AI chatbot that allows users to chat with their PDF documents using Retrieval-Augmented Generation (RAG).

It supports both:

☁️ **Cloud Mode** using Groq API  
🖥️ **Offline Mode** using Ollama Local LLM  

The project demonstrates the complete RAG pipeline:

PDF → Text Extraction → Chunking → Embeddings → Vector Search → AI Response

---

## ✨ Features

### ☁️ Online Mode (Groq API)
- Multi-PDF document ingestion
- Text chunking
- Semantic search using embeddings
- ChromaDB vector storage
- Fast LLM responses using Groq API
- Chat-based interaction

### 🖥️ Offline Mode (Ollama)
- Fully local AI chatbot
- No API keys required
- No internet dependency
- Privacy-focused architecture
- Data stays on your machine

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- ChromaDB
- Ollama
- Groq API
- HuggingFace Embeddings

---

## 📂 Project Structure

```text
RAGFusion-AI/
│
├── .devcontainer/
│   └── Development environment configuration
│
├── .git/
│   └── Git repository files
│
├── app.py
│   └── Offline RAG chatbot using Ollama
│
├── app_online.py
│   └── Cloud RAG chatbot using Groq API
│
└── requirements.txt
    └── Required Python dependencies
```


---

## ⚙️ Installation

Clone repository:

```bash
git clone <repository-url>

cd RAGFusion-AI

Create virtual environment:
python -m venv venv

Activate:

Windows:

venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt

---

🔄 RAG Workflow
PDF Upload
     ↓
Text Extraction
     ↓
Chunking
     ↓
Embedding Generation
     ↓
ChromaDB Vector Search
     ↓
Relevant Context Retrieval
     ↓
LLM Response

---
🎯 Purpose

This project was built to understand how modern AI assistants work internally using Retrieval-Augmented Generation and how LLM backends can be switched between cloud and local environments.

---
👨‍💻 Author

Mohammed Kupe
