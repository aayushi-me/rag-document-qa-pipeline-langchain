# RAG Document QA Pipeline with LangChain

A Retrieval-Augmented Generation pipeline that enables natural language question answering over custom documents using LangChain and vector search.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

## Overview

This pipeline ingests documents, splits them into chunks, embeds them into a vector store, and uses a retrieval chain to answer user questions with contextually relevant responses grounded in the source documents.

## Architecture

- Document ingestion and text splitting
- Vector embedding and storage using FAISS or Chroma
- Retrieval chain with LangChain for context-aware QA
- End-to-end pipeline demonstrated in a Jupyter notebook

## Getting Started

### Prerequisites

- Python 3.9+
- OpenAI API key

### Installation

```bash
pip install langchain openai faiss-cpu tiktoken
```

### Run

Open the notebook and run all cells:

```bash
jupyter notebook rag-document-qa-pipeline-langchain.ipynb
```

## License

MIT License
