# RAG Document Assistant

A Retrieval-Augmented Generation (RAG) application built using LangChain, Vector Databases, Embeddings, and Large Language Models.

The system allows users to ask questions about documents and receive context-aware answers generated from retrieved information.

---

## Overview

Traditional LLMs rely only on training data.

RAG improves responses by:

1. Retrieving relevant information from external documents
2. Providing retrieved context to the LLM
3. Generating accurate, document-grounded answers

---

## Features

- PDF document loading
- Text chunking
- Embedding generation
- Vector database storage
- Semantic similarity search
- Context-aware question answering
- Retrieval-Augmented Generation pipeline

---

## Architecture

```text
Document
    │
    ▼
Text Splitter
    │
    ▼
Embeddings
    │
    ▼
Vector Database
    │
    ▼
Retriever
    │
    ▼
LLM
    │
    ▼
Answer
```

---

## Technologies Used

- Python
- LangChain
- FAISS / Chroma
- Embeddings
- Gemini / OpenAI
- Retrieval-Augmented Generation

---

## Workflow

### 1. Load Documents

Load PDF or text documents.

### 2. Split Documents

Create smaller chunks for retrieval.

### 3. Generate Embeddings

Convert text into vector representations.

### 4. Store in Vector Database

Store embeddings for efficient search.

### 5. Retrieve Relevant Chunks

Find information related to the user query.

### 6. Generate Final Answer

Provide the retrieved context to the LLM.

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openrouter_api_key
OPENAI_BASE_URL=https://openrouter.ai/api/v1
MODEL_NAME=openai/gpt-4o-mini
```

---

## Run

Open:

```bash
RAG.ipynb
```

Run all notebook cells.

---

## Learning Outcomes

Through this project I learned:

- Retrieval-Augmented Generation
- Embedding models
- Vector databases
- Semantic search
- Context-aware LLM applications
- LangChain pipelines
- Prompt engineering with retrieved context

---

## Future Improvements

- Multi-document support
- Conversational memory
- Hybrid search
- Metadata filtering
- Web-based interface
- Citation generation

---

## Author

Meghana Ravalkol