# 📌 Retrieval-Augmented Generation (RAG) using LangChain

## 🚀 Project Overview  
This project implements a **Retrieval-Augmented Generation (RAG)** system that answers user queries based on YouTube video transcripts.  
It combines **semantic search (FAISS)** with **LLM-based response generation** to provide accurate, context-aware answers.

---

## ⚙️ Features  
- 🎥 Extracts transcripts from YouTube videos  
- ✂️ Splits text into manageable chunks  
- 🔎 Performs semantic search using vector embeddings  
- 🤖 Generates answers using an LLM  
- 📌 Ensures responses are based only on retrieved context  

---

## 🛠️ Tech Stack  
- **LangChain** – Pipeline orchestration  
- **OpenAI API** – Embeddings & LLM  
- **FAISS** – Vector database for similarity search  
- **Python** – Core implementation  

---

## 📂 Project Workflow  

### 1. Data Ingestion  
- Fetch transcript using YouTube API  
- Convert into plain text  

### 2. Text Processing  
- Split text into chunks using RecursiveCharacterTextSplitter  

### 3. Embedding & Storage  
- Generate embeddings using OpenAI  
- Store vectors in FAISS  

### 4. Retrieval  
- Retrieve top relevant chunks based on user query  

### 5. Generation  
- Pass retrieved context to LLM  
- Generate accurate answer using prompt engineering  

---

## 📸 Architecture  
