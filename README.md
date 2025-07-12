# 🤖 CollabGPT: A Multi-PDF RAG Chatbot using Cohere

CollabGPT is an intelligent chatbot system that lets you **upload multiple PDFs** (research papers, reports, books) and **ask questions in natural language**. It uses **Cohere’s embedding model** and **LLM generation** to retrieve the most relevant context and generate accurate, informative responses.

---

## 🚀 Features

- 📄 Upload and read multiple PDF files
- ✂️ Cleanly extract and chunk text using PyMuPDF
- 🧠 Create semantic embeddings with Cohere's `embed-english-v3.0`
- 🔍 Retrieve relevant chunks using cosine similarity
- 💬 Generate smart answers using Cohere's `generate()` or `chat()` APIs
- 💻 Interactive Q&A in Colab (console-based or Gradio UI)
- 📝 Save entire Q&A history to a `.txt` file

---

## 🖼️ Example Chat Interaction (Colab UI)

Here’s a real screenshot showing CollabGPT working inside Google Colab:

![CollabGPT Chat Screenshot](screenshot.png)

---

## 🧪 Tech Stack

- `Python`
- `Cohere API`
- `PyMuPDF`
- `NumPy`
- `Gradio` (optional UI)
- `Google Colab`

---

## 🔧 How It Works

1. Upload one or more PDF files.
2. Extract and chunk text into overlapping segments.
3. Generate embeddings using Cohere’s `embed-english-v3.0` model.
4. Search the top-k most similar chunks using cosine similarity.
5. Use the matched context to answer user queries using Cohere’s `generate()` or `chat()`.

---

