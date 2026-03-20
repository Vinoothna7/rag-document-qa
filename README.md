# RAG-Based Document Q&A System

This project explores how Large Language Models can be combined with external data using a Retrieval-Augmented Generation (RAG) pipeline.

## What I did
- Loaded and processed text documents
- Split documents into smaller chunks for better retrieval
- Generated embeddings for semantic search
- Stored embeddings using a vector database (FAISS)
- Retrieved relevant chunks and generated answers using an LLM

## Tech Stack
- Python
- FAISS
- LangChain (basic usage)
- OpenAI / HuggingFace APIs

## Why I built this
I wanted to understand how LLMs can answer questions based on custom data instead of relying only on pre-trained knowledge.

## Current Limitations
- Responses depend heavily on chunk quality
- Basic prompt design (can be improved)

## Next Steps
- Improve retrieval accuracy
- Experiment with better prompting techniques
- Try multi-agent workflows
