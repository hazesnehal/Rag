# Rag
# 🔍 RAG-Powered PDF Question Answering using Fireworks AI

This project demonstrates a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows users to ask natural language questions about the contents of a PDF. It uses **LangChain**, **FAISS**, and **Fireworks AI** for embedding and language generation.

---

## 📌 Features

- Upload any PDF document
- Automatically split it into manageable chunks
- Create vector embeddings using Fireworks AI
- Store and search using FAISS vector store
- Ask questions and get clean, point-wise answers from the PDF content

---

## 🚀 Tech Stack

- Python 3
- Google Colab
- [LangChain](https://python.langchain.com/)
- [FAISS (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)
- [Fireworks AI](https://fireworks.ai/)

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/hazesnehal/Rag.git
   cd Rag
2.Install all required dependencies in Colab when prompted (includes LangChain, FAISS, and Fireworks-related packages).
3.Add your Fireworks API key securely using the Colab Secrets feature.
4.Upload your PDF file using the upload widget in the notebook.
5.Run the notebook cells step-by-step to load, chunk, embed the PDF, and query it using Fireworks AI.
