# 🤖 Local AI Agent Using RAG (Retrieval-Augmented Generation)

Welcome to **Local_AI_Agent_Using_RAG** – a locally running, privacy-preserving AI agent powered by open-source models using **LangChain**, **Ollama**, **Chroma**, and **RAG (Retrieval-Augmented Generation)**.

> ✅ No API Keys Needed  
> 🧠 Uses Local LLM (Large Language Model)  
> 📁 Private, Fast, and Extendable

---

## 🚀 Features

- 🔍 **RAG-based AI Agent**: Combines retrieval and generation for accurate, context-aware responses.
- 🔗 **LangChain**: Manages prompts, chains, memory, and integration with vector databases.
- 🧠 **Ollama**: Runs open-source LLMs like `llama2`, `mistral`, `gemma`, or `phi` locally.
- 📚 **Chroma**: Lightweight, fast vector database for embedding and retrieval.
- 🗂️ **Document Ingestion**: Supports local files (PDF, TXT, etc.) for contextual Q&A.

---

## 🛠️ Requirements

- Python 3.10+
- [Ollama](https://ollama.com/) (for running LLMs locally)
- pip / virtualenv (recommended)

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/Sirfowahid/Local_AI_Agent_Using_RAG.git
cd Local_AI_Agent_Using_RAG

# Create virtual environment
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
