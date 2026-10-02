# 📚 RAG Documents Research

A **Retrieval-Augmented Generation (RAG)** application that allows users to interact with documents using natural-language queries. The system retrieves relevant information from the uploaded documents and uses an LLM to generate context-aware responses.

## 🚀 Features

* 📄 Document-based question answering
* 🔍 Semantic search using vector embeddings
* 🧠 Retrieval-Augmented Generation (RAG)
* 🤖 LLM-powered responses
* 📚 Context-aware answers based on document content
* ⚡ Fast document retrieval
* 🔐 Environment-based API key management
* 🖥️ Interactive application interface

## 🏗️ Architecture

```text
                ┌─────────────────────┐
                │   User Query        │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Query Processing    │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Embedding Model     │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Vector Retrieval    │
                │ / Semantic Search   │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Relevant Context    │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ LLM / Generator     │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ Final Answer        │
                └─────────────────────┘
```

## 🔄 RAG Workflow

1. **Document ingestion** – Documents are loaded into the application.
2. **Text processing** – Documents are split into smaller chunks.
3. **Embedding generation** – Text chunks are converted into vector representations.
4. **Vector storage** – Embeddings are stored for efficien
