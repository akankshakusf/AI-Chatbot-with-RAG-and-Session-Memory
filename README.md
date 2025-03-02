# 🧠Conversational AI Chatbot with RAG and Session Memory

## 📌 Project Overview
This project implements an **advanced AI-powered chatbot** that leverages **Retrieval-Augmented Generation (RAG)** to provide contextual responses with memory retention across conversations. Unlike standard chatbots, this implementation dynamically **remembers chat history**, **retrieves relevant information from uploaded PDFs**, and uses **state-of-the-art open-source models** for natural language understanding and response generation.

The chatbot is built using **LangChain**, **FAISS**, **Hugging Face Transformers**, and the **Gemma 3B model**, with an option to utilize **Groq API-powered LLMs** for enhanced response generation.

---

## 🚀 Features & Capabilities
- ✅ **Retrieval-Augmented Generation (RAG)**: Enhances chatbot responses by retrieving context from uploaded documents (PDFs)  
- ✅ **Persistent Session Memory**: Maintains user conversation history for contextual understanding  
- ✅ **Multi-LLM Support**: Uses **Gemma 3B (Ollama)** as the primary model with an option for **Groq API LLMs**  
- ✅ **Embeddings with Hugging Face**: Uses **Hugging Face sentence embeddings** for document vectorization  
- ✅ **Vector Store with FAISS**: Efficiently indexes and retrieves document chunks  
- ✅ **Dynamic Query Reformulation**: Improves response accuracy by adapting queries based on past interactions  
- ✅ **Interactive UI with Streamlit**: Provides a user-friendly web interface for chatbot interactions  
- ✅ **Configurable Parameters**: Allows users to adjust model temperature, max tokens, and response tuning  

---

## 🔧 **Tech Stack & Toolkit**
### **Generative AI & NLP**
- **LLMs**: Gemma 3B (Ollama), Groq API models  
- **Vector Embeddings**: Hugging Face Transformers (sentence embeddings)  
- **Retrieval Mechanism**: FAISS (Facebook AI Similarity Search) for efficient similarity-based retrieval  
- **Query Understanding**: LangChain’s conversational memory and prompt engineering  

### **Frameworks & Libraries**
- **LangChain**: Manages LLM interactions, document processing, and retrieval  
- **FAISS**: Vector store for fast similarity search  
- **Hugging Face Transformers**: Used for embeddings and model fine-tuning  
- **Ollama**: Runs **Gemma 3B** locally for efficient inferencing  
- **Streamlit**: Builds the chatbot UI for seamless user interaction  

### **Backend & Data Processing**
- **PDF Processing**: LangChain’s document loaders and chunking techniques  
- **Chat History Management**: Tracks past interactions for long-term memory  
- **Dynamic Query Reformulation**: Improves response relevance using LangChain’s pipeline

## 🎯 Why This Project?

This chatbot bridges the gap between **traditional retrieval systems** and **generative AI** by implementing **context-aware, document-grounded conversation** with a memory component. 

It is ideal for:
- 🧠 **Knowledge-based AI assistants**
- 💬 **Customer support chatbots**
- 📚 **Research Q&A systems**


