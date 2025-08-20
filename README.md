# LangChain-Chatbot
# AI chatbot using LangChain with file context augmentation.
# LangChain AI Chatbot (with Document Context)

An AI-powered chatbot built using **LangChain** and **OpenAI** that can:
- Hold **conversational memory**
- Answer questions based on **uploaded documents** (PDFs, text files)
- Provide **context-aware, accurate responses**
- Log dialogue for review and analysis

This project demonstrates how to combine **LLMs with Retrieval-Augmented Generation (RAG)** techniques to create useful, real-world AI assistants.

---

## ✨ Features
- 🔹 **Conversation Memory** – maintains chat history using `ConversationBufferMemory`
- 🔹 **Document Ingestion** – load and index PDF/text documents
- 🔹 **Vector Search** – semantic similarity search with FAISS/Chroma
- 🔹 **RAG Pipeline** – chatbot grounds answers in relevant chunks from your documents
- 🔹 **Prompt Engineering** – custom templates for better responses
- 🔹 **Dialogue Logging** – optional conversation logs for auditing or training

---

## 🧱 Tech Stack
- **Python 3.10+**
- [LangChain](https://www.langchain.com/)
- [OpenAI API](https://platform.openai.com/)
- [FAISS](https://github.com/facebookresearch/faiss) or [Chroma](https://www.trychroma.com/)
- [PyPDF2](https://pypi.org/project/pypdf2/) for document parsing
- [tiktoken](https://github.com/openai/tiktoken) for token counting
- [dotenv](https://pypi.org/project/python-dotenv/) for secure API key handling

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/<YourUsername>/LangChain-Chatbot.git
cd LangChain-Chatbot

