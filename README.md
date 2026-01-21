# Hanuman God RAG - Web UI (FastAPI)

This project is a **Retrieval-Augmented Generation (RAG)** web application built using **FastAPI**.  
It allows you to upload/keep PDF files, convert them into embeddings, store them in a **vector database**, and ask questions through a simple Web UI.

---

## 🚀 How it Works (Flow)

1. Install dependencies from `requirements.txt`
2. Put your PDF files inside the `data/` folder
3. Run `ingest.py` to create embeddings + store them in vector DB
4. Run the FastAPI application using `uvicorn`
5. Open the web UI and ask questions

---

## ✅ Installation & Setup

### 1) Install requirements
Install all required dependencies using:

```bash
pip install -r requirements.txt
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn app:app --reload
