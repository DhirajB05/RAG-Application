📄 PDF-based RAG Application (Gemini + LangChain)

This project implements a Retrieval-Augmented Generation (RAG) pipeline that allows users to ask questions from a PDF document and get accurate answers strictly grounded in the document content.

It uses Google Gemini, LangChain, and FAISS to perform semantic search and response generation.

🚀 Features

📘 Load and process PDF documents

✂️ Recursive text chunking for better retrieval

🧠 Vector embeddings using Google Generative AI

🔍 Semantic similarity search with FAISS

🤖 Answer generation using Gemini 1.5 Flash

🧵 Full pipeline tracing using LangSmith

❌ Prevents hallucinations (answers only from context)

🛠️ Tech Stack

Python

LangChain

Google Generative AI (Gemini)

FAISS Vector Store

LangSmith (Tracing & Debugging)

dotenv (Environment variables)

📂 Project Structure

Traditional_RAG/
│
├── islr.pdf              # Input PDF file
├── main.py               # RAG pipeline code
├── README.md             # Project documentation
├── .env                  # API keys (not committed)

WORKFLOW :

<img width="2752" height="1536" alt="rag im" src="https://github.com/user-attachments/assets/44e01ede-ef07-4845-ae86-2faade629da3" />

