📄 Q&A with PDF Documents Using FAISS and Mistral 7B Instruct Model

📝 Overview

This project enables question-answering on PDF documents using FAISS for retrieval and Mistral 7B Instruct Model for response generation.

✨ Features

📖 PDF Processing: Extracts text from PDF files using PyMuPDF.

🔍 Vector Search: Utilizes FAISS to index and retrieve relevant text segments.

🤖 AI-powered Answers: Uses Mistral 7B Instruct Model to generate accurate responses to user queries.

🛠️ Technologies Used

🐍 Python

⚡ FAISS (Facebook AI Similarity Search)

🤗 Mistral 7B

📄 PyMuPDF (for PDF text extraction)

🚀 Usage

Install dependencies:

pip install faiss-cpu transformers pymupdf torch

Open the Jupyter Notebook and run the cells to:

Load and preprocess PDF documents

Index document embeddings using FAISS

Perform Q&A on the documents

