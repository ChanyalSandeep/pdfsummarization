# PDF Summarization using LangChain and RAG with Open-Source LLMs

This project demonstrates how to build a **PDF document summarizer** using the **Retrieval-Augmented Generation (RAG)** approach with **LangChain** and **open-source large language models (LLMs)**, without relying on OpenAI APIs.

## Features

- Extract text from PDF documents
- Use open-source LLMs (e.g., Hugging Face models like GPT-J, LLaMA, or others) for natural language understanding and generation
- Implement RAG to combine document retrieval with generation for more accurate and context-aware summaries
- Build modular pipelines with LangChain for easy extensibility and integration

## Motivation

While OpenAI provides powerful APIs, they can have usage limits or cost constraints. This project shows how to build scalable and cost-effective summarization tools using **fully open-source components**.

## Getting Started

### Prerequisites

- Python 3.8+
- [LangChain](https://github.com/hwchase17/langchain)
- PDF processing libraries like `PyMuPDF` (`fitz`) or `pdfplumber`
- Transformers and Hugging Face `transformers` library for open-source LLMs
- FAISS or other vector store for retrieval
