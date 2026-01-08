# 📄 PDF-based RAG Application (Gemini + LangChain)

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline that allows users to query a PDF document and receive accurate answers strictly grounded in the document's content.

It leverages **Google Gemini**, **LangChain**, and **FAISS** to perform efficient semantic search and response generation.

## 🚀 Features

* **📘 PDF Processing:** Seamlessly loads and extracts text from PDF documents.
* **✂️ Smart Chunking:** Uses recursive text splitting to create context-aware chunks for better retrieval.
* **🧠 Advanced Embeddings:** Generates vector embeddings using Google Generative AI.
* **🔍 Semantic Search:** Utilizes FAISS for fast and accurate similarity search.
* **🤖 AI-Powered Answers:** Generates responses using the **Gemini 1.5 Flash** model.
* **🧵 Observability:** Full pipeline tracing and debugging via **LangSmith**.
* **❌ Hallucination Prevention:** configured to answer questions *only* based on the provided context.

## 🛠️ Tech Stack

* **Language:** Python
* **Orchestration:** LangChain
* **LLM:** Google Generative AI (Gemini 1.5 Flash)
* **Vector Store:** FAISS
* **Tracing:** LangSmith
* **Environment Management:** dotenv

## 📂 Project Structure

```bash
Traditional_RAG/
│
├── islr.pdf              # Input PDF file (Document source)
├── main.py               # Main RAG pipeline script
├── README.md             # Project documentation
└── .env                  # API keys configuration (Excluded from version control)

WORKFLOW:

<img width="2752" height="1536" alt="rag im" src="https://github.com/user-attachments/assets/44e01ede-ef07-4845-ae86-2faade629da3" />
