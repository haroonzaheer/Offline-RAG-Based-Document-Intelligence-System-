**Document Processing & Embedding with Streamlit, Ollama, and ChromaDB**

This project demonstrates how to build a document processing and embedding pipeline using Streamlit, Ollama, LangChain, ChromaDB, and Sentence Transformers.

Features

Upload PDFs via Streamlit.

Load and split documents using LangChain.

Generate embeddings with Ollama or CrossEncoder.

Store and query embeddings in ChromaDB.

# installation 
# Clone the repo
git clone https://github.com/haroonzaheer/Offline-RAG-Based-Document-Intelligence-System-.git
cd your-repo

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Install dependencies
pip install streamlit ollama langchain langchain-community chromadb sentence-transformers pymupdf
