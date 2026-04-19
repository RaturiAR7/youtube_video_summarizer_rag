# 🎥 YouTube RAG Chatbot

A Retrieval-Augmented Generation (RAG) based chatbot that allows users to ask questions about a YouTube video and receive context-aware answers generated directly from the video transcript.

---

## 🚀 Overview

This project builds an end-to-end RAG pipeline that:

- Extracts transcript data from a YouTube video
- Splits the transcript into smaller chunks
- Converts text into embeddings
- Stores embeddings in a vector database (FAISS)
- Retrieves relevant context based on user queries
- Uses a Large Language Model (LLM) to generate answers

---

## 🧠 How It Works

```text
YouTube Video
     ↓
Transcript Extraction
     ↓
Text Splitting
     ↓
Embeddings (HuggingFace)
     ↓
FAISS Vector Store
     ↓
Retriever
     ↓
Prompt + Context
     ↓
LLM (Ollama - Llama3)
     ↓
Final Answer
```

---

## 🔧 Setup

```bash
pip install -r requirements.txt
```
