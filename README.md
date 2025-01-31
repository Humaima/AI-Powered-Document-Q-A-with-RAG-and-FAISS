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

## Install Dependencies
pip install -r requirements.txt

## Set Up API Keys
Create a .env file in the root directory and add your API keys:

GROQ_API_KEY=your_groq_api_key
LANGCHAIN_API_KEY=your_langchain_api_key

## Usage
Run the Streamlit app with:
  streamlit run app.py
1. Upload a .txt document.
2. The app will automatically analyze the document and generate an AI-powered response.
3. View the extracted insights and relevant document sources.

## Tech Stack
- Python (Streamlit, LangChain, FAISS, dotenv)
- NLP Models (Groq’s LLaMA, Ollama Embeddings)
- Vector Storage (FAISS)

### Clone the Repository  
```bash
git clone https://github.com/your-username/rag-document-analyzer.git
cd rag-document-analyzer

