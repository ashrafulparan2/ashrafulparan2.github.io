---
title: 'ChatWithPDF-Rag-App'
excerpt: 'A PDF chatbot application using RAG (Retrieval-Augmented Generation) for intelligent document interaction'
author_profile: true
permalink: /projects/chatwithpdf-rag-app/
---

<head>
<title>Font Awesome Icons</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>

# ChatWithPDF-Rag-App

[<i class="fa fa-github" style="color:black;"></i> View on GitHub](https://github.com/ashrafulparan2/ChatWithPDF-Rag-App) | 
[<i class="fa fa-globe" style="color:black;"></i> Live Demo](https://chatwithpdf-rag.streamlit.app)

## Overview
ChatWithPDF-Rag-App is an intelligent document interaction system that allows users to have natural conversations with PDF documents. The application uses RAG (Retrieval-Augmented Generation) technology to provide accurate, context-aware responses to questions about PDF content.

![Application Interface](/assets/images/projects/chatwithpdf-rag-app/image-3.png)

## Key Features
- **PDF Question Answering**: Ask questions about any uploaded PDF document
- **Custom Prompt Engineering**: Uses carefully crafted prompts for accurate and context-aware responses
- **Source Document Tracking**: Displays the source documents used to generate each answer
- **Advanced Language Models**: 
  - Uses `sentence-transformers/all-MiniLM-L6-v2` for embeddings
  - Powered by `mistralai/Mistral-7B-Instruct-v0.3` for language generation

## Technical Details
- **Backend**: Python 3.11+
- **Frontend**: Streamlit
- **Vector Database**: FAISS for efficient similarity search
- **Authentication**: Hugging Face API integration
- **Duration**: Mar 2024 – Present

## Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/ashrafulparan2/ChatWithPDF-Rag-App.git
cd ChatWithPDF-Rag-App
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up Hugging Face authentication:
```bash
huggingface-cli login
```

4. Run the application:
```bash
streamlit run app.py --server.enableCORS false --server.enableXsrfProtection false
```

## Implementation Details

### Vector Store Setup
- The application uses FAISS (Facebook AI Similarity Search) for efficient document retrieval
- Requires pre-generated vectorstore files (`index.faiss` and `index.pkl`) in the `vectorstore/db_faiss/` directory
- Embeddings are generated using the `sentence-transformers/all-MiniLM-L6-v2` model

### Question Answering Pipeline
1. User uploads a PDF document
2. Document is processed and vectorized
3. User questions are embedded and matched against the document vectors
4. Relevant context is retrieved and fed to the Mistral-7B model
5. Model generates natural, context-aware responses

### User Interface
- Clean, intuitive Streamlit interface
- Drag-and-drop PDF upload
- Real-time question answering
- Source document display for transparency
- File size limit of 200MB per PDF 