# PDF RAG System

This project is my hands-on implementation of a Retrieval-Augmented Generation (RAG) pipeline using LangChain.

The system:

- Loads PDF and text_file documents
- Splits documents into chunks
- Generates embeddings
- Stores embeddings in a vector database
- Retrieves relevant chunks based on user queries
- Uses an LLM to generate context-aware answers

## Tech Stack

- Python
- LangChain
- PyPDFLoader
- FAISS / ChromaDB
- OpenAI / HuggingFace Embeddings

## Learning Goals

This project was built to understand:

- Document ingestion
- Text chunking strategies
- Embeddings
- Vector databases
- Semantic search
- End-to-end RAG workflows