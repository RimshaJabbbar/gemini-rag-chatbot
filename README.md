# gemini-rag-chatbot
A Streamlit-based RAG Chatbot powered by Google Gemini API, with support for uploading PDF/TXT files as a knowledge base, semantic search, and interactive Q&amp;A

This project is a Retrieval-Augmented Generation (RAG) chatbot built using Streamlit and Google’s Gemini API.

✨ Key Features:

Gemini API Integration – Uses google.generativeai for intelligent text generation.

Custom Knowledge Base – Upload multiple PDF or TXT files that the chatbot can reference.

Semantic Search – Implements a simple keyword-based search to fetch relevant knowledge base chunks for context.

RAG Pipeline – Combines retrieved context with the user’s query to generate accurate, context-aware answers.

Interactive UI – Clean chat interface with support for chat history, clearing KB, and customizable AI settings.

Configurable Parameters – Adjust model type, temperature, and max tokens from the sidebar.

Dark-Themed Styling – Custom CSS applied for a polished, minimal UI.

🔧 Tech Stack:

Streamlit – Interactive web UI

Google Generative AI (Gemini API) – Text generation

PyPDF (pypdf) – PDF text extraction

Tempfile & OS – Secure file handling

Python typing – Type annotations for cleaner code

💡 This project demonstrates how to combine document retrieval with generative AI to build intelligent assistants that can reason over custom knowledge bases.
