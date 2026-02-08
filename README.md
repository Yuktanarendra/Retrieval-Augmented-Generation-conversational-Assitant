# 🧠 Conversational RAG Assistant

A **Conversational Retrieval-Augmented Generation (RAG) Assistant** built using **LangChain**, **Groq (Llama 3)**, **ChromaDB**, and **Hugging Face embeddings**.  
The system supports **multi-turn conversations**, **context-aware responses**, and **real-time tracing** using LangSmith.

---

## 🚀 Features

- 🔍 **Retrieval-Augmented Generation (RAG)**  
  Combines document retrieval with LLM reasoning for accurate, grounded answers.

- 💬 **Multi-Turn Conversational Memory**  
  Maintains chat history using `ChatMessageHistory` and `RunnableWithMessageHistory`.

- 🧠 **Contextual Question Reformulation**  
  Automatically rewrites follow-up questions using conversation history.

- 📚 **Semantic Search with ChromaDB**  
  Stores and retrieves document embeddings efficiently.

- ⚡ **Fast LLM Inference with Groq (Llama 3)**  
  Enables low-latency, high-quality responses.

- 🧪 **LangSmith Tracing & Monitoring**  
  Tracks prompts, retrieval steps, and LLM outputs for debugging and evaluation.

- 🌐 **Web-Based Knowledge Loading**  
  Scrapes online content dynamically using `WebBaseLoader`.

---

## 🧰 Tech Stack

| Component | Technology |
|---------|-----------|
| Framework | LangChain |
| LLM | Groq (Llama 3) |
| Embeddings | Hugging Face – `all-MiniLM-L6-v2` |
| Vector Store | ChromaDB |
| Memory | ChatMessageHistory |
| Prompting | ChatPromptTemplate |
| Data Loader | WebBaseLoader |
| Tracing | LangSmith |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository


