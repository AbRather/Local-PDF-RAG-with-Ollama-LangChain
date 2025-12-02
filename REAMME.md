# 🦙 Local PDF RAG with Ollama & LangChain

A secure, private, and local **Retrieval-Augmented Generation (RAG)** application. This tool allows you to chat with your PDF documents using local LLMs via Ollama, ensuring that your data never leaves your machine.



[Image of Retrieval Augmented Generation architecture diagram]


## 🚀 Features

* **100% Local:** Uses Ollama to run LLMs and embeddings locally. No API keys or internet connection required after setup.
* **Privacy First:** Your documents are processed and stored on your own machine.
* **RAG Architecture:**
    * **Ingestion:** Loads and cleans PDF text using `pypdf`.
    * **Chunking:** Splits text into manageable chunks.
    * **Embeddings:** Uses `nomic-embed-text` for high-quality vector representations.
    * **Vector Store:** Stores embeddings in a local ChromaDB instance.
* **Interactive UI:** Built with Streamlit for a clean chat interface.
* **Multi-Query Retrieval:** Uses AI to generate different versions of your question to find the best answers in the text.

## 🛠️ Tech Stack

* **Python 3.9+**
* **[Ollama](https://ollama.com/):** Model runner.
* **[LangChain](https://www.langchain.com/):** Framework for LLM applications.
* **[ChromaDB](https://www.trychroma.com/):** Vector database.
* **[Streamlit](https://streamlit.io/):** Frontend UI.

## 📋 Prerequisites

1.  **Python 3.9** or higher installed.
2.  **Ollama** installed and running. [Download here](https://ollama.com/download).

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
cd your-repo-name