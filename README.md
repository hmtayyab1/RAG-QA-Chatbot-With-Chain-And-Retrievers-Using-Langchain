# 🧠 PDF QA using LangChain + Ollama + FAISS

This project demonstrates how to build a retrieval-based Question Answering (QA) system over a PDF file using [LangChain](https://github.com/langchain-ai/langchain), [Ollama LLMs](https://ollama.ai), and [FAISS vector search](https://github.com/facebookresearch/faiss).

## 🚀 Features

- Load and process any PDF using `PyPDFLoader`
- Chunk the document using `RecursiveCharacterTextSplitter`
- Embed document chunks using `OllamaEmbeddings`
- Store and search embeddings using `FAISS`
- Interact with a LLaMA2 model using `Ollama`
- Generate answers grounded in context using a retrieval chain

## 📦 Dependencies

- `langchain`
- `langchain-community`
- `ollama` (Make sure you have an Ollama LLM running, e.g., `llama2`)
- `faiss-cpu` or `faiss-gpu`
- `tqdm` (optional for progress)

Install dependencies:

```bash
pip install langchain langchain-community faiss-cpu
