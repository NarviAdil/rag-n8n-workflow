📊 AI-Powered Financial Insight Chatbot with Pinecone RAG & OpenAI (n8n Workflow)
This project leverages n8n, OpenAI, Pinecone, and OneDrive to build a Retrieval-Augmented Generation (RAG)-based chatbot that can analyze and respond to financial documents or queries in real-time. It provides a powerful backend workflow capable of answering user questions based on financial data stored in the cloud.

🧠 What This Project Does
This project enables:

Intelligent Q&A on financial documents

Document ingestion and vector embedding using Pinecone and OpenAI

Chat-based interactions with memory and tool integration

RAG implementation for accurate, context-rich responses



🔍 AI-Powered RAG Workflow with Pinecone and n8n

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** system using [n8n](https://n8n.io/), [OpenAI](https://platform.openai.com/), and [Pinecone](https://www.pinecone.io/) with support for document-based search and conversational chat analysis.

## ✨ Features

- 🧠 AI-powered analysis using OpenAI's LLM (e.g., GPT)
- 📁 Document ingestion from Microsoft OneDrive
- 📚 Vector search with Pinecone for fast retrieval
- 🧩 Memory storage and context management
- 🗂 Recursive character text splitting for optimal chunking
- 💬 Chat interface with dynamic response generation based on uploaded content
hub.com/user-attachments/assets/3d57d537-181d-441f-a0ca-f968764270ef)

⚙️ How It Works
🔁 Workflow 1: RAG-Enabled Chatbot (Chat Triggered)

Trigger: Chat message received

Chat Model: Uses OpenAI GPT

Memory: Maintains conversation context using Simple Memory

Tool Agent: Handles RAG logic and connects to Pinecone Vector Store

Vector Retrieval: Embeddings generated and queried against Pinecone for context

Response: Final response generated with embedded context and returned to user
![n8nchatbot png2](https://github.com/user-attachments/assets/7f42f01e-39cd-4129-82e4-3f9a518db9ea)


🔁 Workflow 2: Document Upload and Embedding (Triggered by File Upload)

Trigger: Workflow started manually or via UI button

Document Source: Downloads files from Microsoft OneDrive

Text Splitting: Uses Recursive Character Text Splitter to chunk documents

Embedding: Each chunk is embedded using OpenAI Embeddings API

Storage: Embeddings stored in Pinecone Vector Store

![n8nchatbot](https://github.com/user-attachments/assets/17b446b1-284b-4341-bfae-bfb2f98f94dc)



![n8n](https://github.com/user-attachments/assets/3716a86e-a4a6-4dfc-ac66-506cc24f0bbe)



