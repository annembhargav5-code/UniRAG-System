# UniRAG-System

A semantic document retrieval system using PDF extraction, Sentence Transformers, and FAISS.

## 📌 Project Overview

UniRAG-System is a Retrieval-Augmented Generation (RAG)-based document retrieval project that allows users to retrieve relevant information from PDF documents using natural language queries.

## 🎯 Objectives

* Extract text from PDF documents.
* Split extracted text into smaller chunks.
* Convert text chunks into numerical embeddings.
* Store embeddings using FAISS.
* Retrieve relevant document chunks based on user queries.

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Sentence Transformers
* FAISS
* PDF text extraction libraries

## ⚙️ Project Workflow

1. Upload a PDF document.
2. Extract text from the PDF.
3. Split the text into chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS index.
6. Enter a natural language query.
7. Retrieve the most relevant text chunks using similarity search.

## 📂 Project Structure

```text
UniRAG-System/
│
├── README.md
└── uniragsystem.ipynb
```

## 🚀 How to Run

1. Clone this repository.
2. Open `uniragsystem.ipynb` in Jupyter Notebook or Kaggle.
3. Install the required libraries.
4. Upload your PDF document.
5. Run the notebook cells in order.
6. Enter a query and view the retrieved results.

## 📚 Key Concepts

* Retrieval-Augmented Generation (RAG)
* Text Chunking
* Text Embeddings
* Semantic Search
* FAISS Vector Index
* Cosine Similarity or the similarity metric configured in the project

## 👨‍💻 Author

Bhargav Annem
