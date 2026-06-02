# Context-Aware Chatbot using RAG (FAISS + SentenceTransformers)

## Project Overview
This project implements a simple yet advanced Retrieval-Augmented Generation (RAG) chatbot that can understand user queries and retrieve relevant contextual information from a custom knowledge base using semantic search.

---

## Key Features
- FAISS vector database used for semantic search
- SentenceTransformer embeddings used for text representation
- Retrieval-Augmented Generation (RAG) implemented
- Context-aware chatbot built using similarity search

---

## Methodology

### 1. Knowledge Base
A custom set of AI/ML-related documents is used as the knowledge base for the chatbot.

### 2. Text Embeddings
Text data is converted into dense vector representations using SentenceTransformer (all-MiniLM-L6-v2).

### 3. Vector Database
FAISS (Facebook AI Similarity Search) is used to store embeddings and perform fast nearest-neighbor search.

### 4. Query Processing
User queries are embedded and matched with the most relevant documents using cosine similarity.

### 5. Response Generation
The chatbot retrieves relevant context and generates a structured response based on retrieved information.

---

## Technologies Used
- Python
- FAISS
- SentenceTransformers
- NumPy

---

## Skills Demonstrated
- Retrieval-Augmented Generation (RAG)
- Vector similarity search
- Embedding-based NLP
- Context-aware chatbot development
- Information retrieval systems

---

## How It Works
1. User enters a query
2. Query is converted into embedding
3. FAISS retrieves most similar documents
4. Relevant context is extracted
5. Final response is generated using retrieved knowledge

---

## Author
Developed as part of AI/ML Engineering Internship Task.

---

## Note
This project demonstrates a lightweight RAG-based chatbot suitable for educational and internship purposes, focusing on semantic search and context-aware responses.
