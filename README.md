# 📄 AI-Powered PDF Chatbot using RAG

An AI-powered PDF question-answering application built using **Retrieval-Augmented Generation (RAG)**. The application allows users to upload PDF documents and ask questions about their content using a conversational AI interface.

---

## 🚀 Project Overview

This project demonstrates an end-to-end **RAG (Retrieval-Augmented Generation)** pipeline for interacting with PDF documents.

Instead of providing the complete document directly to the Large Language Model (LLM), the application first retrieves the most relevant information from the uploaded document and then uses that context to generate an accurate and context-aware response.

### The overall workflow is:

```text
PDF Document
     ↓
Text Extraction
     ↓
Text Chunking
     ↓
Text Embeddings
     ↓
FAISS Vector Database
     ↓
User Query
     ↓
Similarity Search
     ↓
Relevant Document Chunks
     ↓
Large Language Model
     ↓
Generated Answer
