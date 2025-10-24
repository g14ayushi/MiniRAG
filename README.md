# MiniRAG

A lightweight **Retrieval-Augmented Generation (RAG)** pipeline built to explore how external document knowledge can enhance LLM responses.  
This project demonstrates an end-to-end setup using **PDF data**, **ChromaDB**, and **ChatGroq** with **MiniLM embeddings**.

---

## Set Up Guide
```bash
git clone https://github.com/g14ayushi/GroqRAG.git
cd GroqRAG
pip install -r requirements.txt
jupyter notebook ./notebook/pdfLoader.ipynb
```

## What It Does

1. Loads PDFs. 
2. Splits documents into **semantic chunks**.  
3. Generates **embeddings** using `all-MiniLM-L6-v2`.  
4. Stores embeddings in a **ChromaDB vector store**. 
5. Uses **ChatGroq** for conversations with contextual retrieval.  

---

## 🔄 RAG Pipeline Flow

Below is the high-level flow of the project showing how PDFs are processed and used for contextual responses:

<p align="left">
  <img src="./images/rag_pipeline_flow.png" alt="MiniRAG Flow Diagram" width="700"/>
</p>

---

## Tech Stack
**Python**, **LangChain**, **ChromaDB**, **SentenceTransformers**, **Groq**, **LLMs**, **Jupyter Notebook**

---

