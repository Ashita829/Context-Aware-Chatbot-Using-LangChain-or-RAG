# Context-Aware Chatbot using LangChain + RAG

## Objective
The objective of this project is to build a context-aware conversational AI chatbot that can retrieve relevant information from documents and generate accurate answers using Retrieval-Augmented Generation (RAG).

---

## Dataset
A custom text dataset was used in the form of a `.txt` file (`sample.txt`) containing unstructured textual information.

---

## Technologies Used
- Python  
- LangChain  
- Hugging Face Transformers  
- FAISS (Vector Database)  
- Sentence Transformers  
- Gradio  

---

## Methodology

The project follows the RAG (Retrieval-Augmented Generation) approach:

1. Load text data from a local file (`sample.txt`)
2. Split text into smaller chunks for better processing
3. Convert text chunks into vector embeddings using HuggingFace models
4. Store embeddings in FAISS vector database for similarity search
5. Retrieve relevant document chunks based on user query
6. Generate responses using FLAN-T5 language model
7. Deploy interactive chatbot using Gradio interface

---

## Features
- Context-aware question answering  
- Document-based retrieval system  
- Semantic search using embeddings  
- Interactive chatbot UI using Gradio  
- Lightweight LLM-based response generation  

---

## How It Works
User enters a question →  
System retrieves relevant text chunks from FAISS →  
Context is passed to LLM →  
Model generates final answer →  
Response is displayed in chatbot UI  

---

## Results
The chatbot successfully retrieves relevant context from the document and generates meaningful responses based on user queries.

---

## Output
- Gradio chatbot interface link (generated after running notebook)
- Screenshot of working chatbot

---

## Conclusion
This project demonstrates a basic implementation of Retrieval-Augmented Generation (RAG), combining document retrieval and language models to create a context-aware chatbot system.

---

## Author
AI/ML Internship Project – DevelopersHub Corporation
