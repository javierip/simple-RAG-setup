# Simple RAG Setup

Easy to use RAG (Retrieval Augmented Generation) setup.

## Install

1. Download and install [Anaconda](https://docs.anaconda.com/anaconda/install/). Add Anaconda to your PATH environment. Yes, do it ;)
2. Install [Ollama](https://ollama.com/download)
3. Download this repo as zip [link](https://github.com/javierip/simple-RAG-setup/archive/refs/heads/main.zip)
4. Decompress the repository to your desired directory.
5. Open a terminal.

```bash
(base) ollama pull nomic-embed-text
(base) ollama pull llama3.1
(base) conda create --name simple-rag-env python=3.11 -y
(base) conda activate simple-rag-env
(simple-rag-env) pip install -r requirements.txt
(simple-rag-env) streamlit run simple_rag_app.py
```

## References

* LangChain: [Build a Local RAG Application](https://python.langchain.com/v0.2/docs/tutorials/local_rag/)
* Blog post [github](https://github.com/tonykipkemboi/ollama_pdf_rag/tree/main)
