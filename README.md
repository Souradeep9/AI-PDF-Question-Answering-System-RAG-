# AI-PDF-Question-Answering-System-RAG-
The AI PDF Question Answering System is a Retrieval-Augmented Generation (RAG) application that enables users to ask natural language questions about PDF documents and receive contextually relevant answers. 
# Features
Upload and process PDF documents.
Extract and preprocess text from PDFs.
Split documents into semantic chunks.
Generate text embeddings using Sentence Transformers.
Perform fast semantic search with FAISS vector indexing.
Retrieve relevant document sections based on user queries.
Provide accurate, context-aware answers using semantic similarity.
# Tech Stack
Language: Python
Libraries: PyPDF2, Sentence Transformers, FAISS, NumPy
Concepts: Retrieval-Augmented Generation (RAG), Semantic Search, Vector Embeddings, NLP.
# How it work
Upload a PDF document.
Extract and preprocess the text.
Split the text into smaller chunks.
Generate embeddings for each chunk using Sentence Transformers.
Store embeddings in a FAISS vector database.
Convert the user's query into an embedding.
Retrieve the most similar document chunks.
Return the most relevant answer based on semantic similarity.
# Project Highlight
Built a semantic document retrieval system using vector embeddings.
Implemented efficient similarity search with FAISS.
Improved document search accuracy using embedding-based retrieval instead of keyword matching.
Demonstrates practical implementation of Retrieval-Augmented Generation (RAG) for document question answering.
