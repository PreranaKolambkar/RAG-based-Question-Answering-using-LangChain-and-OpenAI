# RAG-based-Question-Answering-using-LangChain-and-OpenAI
# RAG Question Answering System

This repository contains a simple Retrieval-Augmented Generation (RAG) demo built using:
- LangChain
- SentenceTransformer embeddings
- Chroma vector database
- PDF/DOCX document loaders
- A small LLM for answering questions based on retrieved context

The notebook walks through:
1. Loading documents  
2. Splitting them into chunks  
3. Creating embeddings  
4. Storing them in Chroma  
5. Running a retriever  
6. Building a basic RAG pipeline  
7. Optional: using an LLM provider (OpenAI or alternatives)

## How to Use
1. Clone the repository  
2. Install required packages from the notebook  
3. Place your documents inside a folder (example: `data/`)  
4. Run the notebook step-by-step  

## LLM Options
If OpenAI is not available, you can use:
- Hugging Face models  
- SentenceTransformer for embeddings (already included)  
- Local LLMs via ollama or text-generation-webui  

## Contents
- `RAG_Notebook.ipynb` – main project notebook  
- `data/` – folder for your PDF/DOCX files  
- `chroma_db/` – vector store directory (auto-created)

Feel free to modify and extend the pipeline.
