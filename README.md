
# 📚 RAG-based Question Answering App

This is a **Retrieval-Augmented Generation (RAG)** powered Question Answering (QA) application. It enhances traditional language model capabilities by incorporating context-aware document retrieval, allowing users to upload PDFs and ask questions based on the uploaded content. The app uses Groq's `gemma2-9b-it` model for response generation and `SentenceTransformers` for embedding-based retrieval.

## 🚀 Features

- 🔍 **Contextual Retrieval** using Sentence-BERT embeddings
- 🧠 **RAG Architecture** combining retrieval and generation
- 🗂️ **PDF Upload Support** to dynamically expand the knowledge base
- 💬 **Natural Question Answering** using Groq's LLM
- 🌐 **Interactive UI** built with Streamlit

---

## 🧰 Tech Stack

- `Streamlit` – Web app framework
- `SentenceTransformers` – Embedding-based semantic search
- `Groq` – Fast LLM generation (gemma2-9b-it)
- `PyPDF2` – PDF parsing and text extraction
- `Python` – Core application logic

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/rag-crag-app.git
   cd rag-crag-app
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Groq API Key**
   - Replace `"Your API Key here"` in the script with your actual Groq API key.

4. **Run the Streamlit App**
   ```bash
   streamlit run app.py
   ```

---

## 📄 Example Usage

1. Upload a PDF containing relevant information.
2. Ask a natural language question.
3. Get context-aware, AI-generated answers.

---

## 📜 License

This project is open-source under the MIT License.
