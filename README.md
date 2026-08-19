# RAG-Pipeline

A simple **Retrieval-Augmented Generation (RAG)** project built using Python, LangChain, and Groq.

## What is RAG?

RAG retrieves relevant information from documents and provides it to an AI model to generate better and more context-based answers.

## Tech Stack

- Python
- LangChain
- Groq
- Embeddings
- Vector Store
- Jupyter Notebook

## Project Workflow

**Documents → Text Splitting → Embeddings → Vector Store → Retrieval → LLM → Answer**

## 🔹 Code Summary

- **Document Loading:** Loads PDF files from the `data/pdfs` folder.
- **Text Splitting:** Splits documents into smaller chunks using `RecursiveCharacterTextSplitter`.
- **Embeddings:** Converts text into numerical vectors using `all-MiniLM-L6-v2`.
- **Vector Database:** Stores document embeddings in **ChromaDB**.
- **Retrieval:** Finds the most relevant documents using semantic similarity.
- **LLM Integration:** Uses **Groq** to generate answers based on the retrieved context.
- **RAG Pipeline:** Combines retrieval and generation to answer user queries.

## How to Run

1. Install the required libraries.
2. Add your Groq API key.
3. Open `RAG_pipeline.ipynb`.
4. Run the notebook cells step by step.

