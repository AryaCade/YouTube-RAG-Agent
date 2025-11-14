# YouTube-RAG-Agent

### 🚀 YouTube RAG Agent

A lightweight Retrieval-Augmented Generation (RAG) system that turns any YouTube video into an AI-answerable knowledge base.

Built with LangChain, FAISS, HuggingFace Embeddings, and Google Gemini.

### 🌟 Why This Project Matters

Employers want to see practical GenAI apps, not just toy projects.
This project demonstrates:

🔹 End-to-end RAG pipeline

🔹 Working with real-world unstructured data (YouTube transcripts)

🔹 Embeddings & vector search

🔹 LLM reasoning with controlled context

🔹 LangChain Runnables for agentic workflows

It shows you understand both GenAI concepts and software engineering structure.

### 🧠 What This App Does

Extracts YouTube video transcripts

Cleans, splits, and processes text

Converts transcript into high-quality embeddings

Stores embeddings inside FAISS vector DB

Retrieves the most relevant segments

Uses Gemini to generate accurate, context-bound answers

Ask any question about the video — the AI answers using only its transcript.

### 🛠️ Tech Stack

Python

LangChain (Runnables, Text Splitters, Community Loaders)

HuggingFace Sentence Transformers

FAISS Vector Store

Gemini 2.5 Flash (Google Generative AI)

youtube-transcript-api

dotenv for environment management

### ⚙️ Installation
pip install -r requirements.txt


### Create .env:
GOOGLE_API_KEY=your_key_here

### ▶️ Quick Usage
retriever.invoke("What is DeepMind?")
main_chain.invoke("Summarize the entire video")


### The system automatically:

Loads transcript

Splits into chunks

Embeds

Retrieves

Generates answer using RAG

🌱 Future Add-ons

Streamlit UI for video chat

Multi-video knowledge merging

Ranking + metadata-based search

LangGraph agentic pipeline

⭐ If This Project Inspires You

Consider giving it a star — it helps and motivates further improvements.
