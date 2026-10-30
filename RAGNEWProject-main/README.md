# RAGNEWProject
# RAG College Knowledge Assistant

A Streamlit-based chatbot that answers questions about fictional college policies using Retrieval-Augmented Generation (RAG) with a local LLM.

## Features

- Ask natural language questions about college policies
- Answers grounded in retrieved documents from the knowledge base
- Local LLM via Ollama (no API keys required)
- Sidebar shows indexed chunks and document sources
- Rebuild knowledge base button for quick updates

## Tech Stack

| Component | Tool |
|-----------|------|
| Frontend | Streamlit |
| LLM | Ollama (gemma:2b) |
| Embeddings | Ollama embedding model |
| Language | Python 3.10+ |

## Prerequisites

- Python 3.10 or higher
- [Ollama](https://ollama.ai) installed locally
- At least one embedding model pulled in Ollama

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/INTROVERCY-coder/rag-college-assistant.git
cd rag-college-assistant

```bash
git clone https://github.com/INTROVERCY-coder/rag-college-assistant.git
cd rag-college-assistant
