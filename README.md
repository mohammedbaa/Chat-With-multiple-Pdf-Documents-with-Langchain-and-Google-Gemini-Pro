About

This project is an end-to-end PDF Question Answering (QA) system that enables users to upload multiple PDF documents and interact with them using natural language queries.

The application extracts text from uploaded PDFs, splits the content into manageable chunks, and converts them into vector embeddings using free Hugging Face sentence-transformer models. These embeddings are stored locally using FAISS for efficient semantic search. When a user asks a question, the system retrieves the most relevant document chunks and generates accurate, context-aware answers using Google Gemini (Gemini 2.5 Pro).

Key features include:

Support for multiple PDF uploads

Semantic search using FAISS vector database

Free, open-source Hugging Face embeddings

Context-aware question answering powered by Gemini LLM

Secure environment variable management for API keys

Interactive and user-friendly Streamlit interface

This project is well-suited for document intelligence, knowledge retrieval systems, enterprise search, and AI-powered assistants, making it an excellent portfolio example of Retrieval-Augmented Generation (RAG).
