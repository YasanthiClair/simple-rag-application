# Simple RAG Application

A lightweight, hands-on implementation of a Retrieval-Augmented Generation (RAG) system built using Jupyter Notebooks. This repository demonstrates how to build a Knowledge Management System (KMS) bot capable of ingestion, chunking, embedding generation, vector storage, and querying a Large Language Model (LLM) using relevant context.

---

## 🚀 Overview

Retrieval-Augmented Generation (RAG) optimizes the output of a Large Language Model by referencing an authoritative knowledge base outside of its training data before generating a response. 

This project serves as a step-by-step guide to setting up a functional RAG pipeline, ideal for document-based question-answering, customer support automation, or personal knowledge retrieval.

### Key Features
* **Document Ingestion & Chunking:** Parses source documents into optimized text chunks.
* **Vector Embeddings:** Converts text data into dense vector representations.
* **Semantic Search:** Queries a vector database to find the most contextually relevant information.
* **Context-Aware Synthesis:** Passes retrieved documents alongside the user query to an LLM for highly accurate answers.

---

## 📁 Repository Structure

* `RAG_bot_KMS (1).ipynb` / `RAG_bot_KMS (2).ipynb`: Core notebooks showcasing the Knowledge Management System (KMS) bot implementation, experimenting with different prompt structures or retrieval tweaks.
* `simple_rag_application_6.ipynb`: Baseline exploration notebook detailing the initial setup of the RAG pipeline.

---

## 🛠️ Tech Stack (Suggested)

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook
* **LLM & Embeddings:** OpenAI API (GPT / `text-embedding-3-small`) or HuggingFace / Ollama (for local deployment).
* **Vector Database:** ChromaDB, FAISS, or Pinecone.
* **Frameworks:** LangChain or LlamaIndex (if applicable).

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/YasanthiClair/simple-rag-application.git](https://github.com/YasanthiClair/simple-rag-application.git)
cd simple-rag-application
