# AI-Powered-Document-Q-A-with-RAG-and-FAISS
## Overview  
This is a Streamlit-powered application that leverages Retrieval-Augmented Generation (RAG) to analyze uploaded `.txt` documents. It employs FAISS for vector search, LangChain for document processing, and Groq's LLaMA model for intelligent Q&A responses.  

## Features  
- Upload and process `.txt` documents  
- Chunk document text using LangChain’s `RecursiveCharacterTextSplitter`  
- Generate embeddings using `OllamaEmbeddings`  
- Store and retrieve document vectors using FAISS  
- Answer user queries with Groq’s LLaMA model  
- Display document sources for responses  

## Installation  
### Prerequisites  
Ensure you have Python 3.8+ installed and set up a virtual environment (optional but recommended).  

### Clone the Repository  
```bash
git clone https://github.com/your-username/rag-document-analyzer.git
cd rag-document-analyzer
