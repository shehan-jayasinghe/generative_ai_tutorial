# Generative AI Tutorial

A hands-on notebook collection covering LLM application development with LangChain, OpenAI, RAG, document processing, conversational retrieval, and LangGraph.

## Learning Path

The notebooks progress from basic chatbot development toward retrieval-augmented and graph-based AI workflows.

### 1. Chatbot

`01_chatbot_langchain_openai_ipynb.ipynb`

Introduces a chatbot workflow using LangChain and OpenAI.

### 2. Simple RAG

`02_simple_rag_langchain_openai.ipynb`

Introduces retrieval-augmented generation: retrieve relevant context and provide it to an LLM when answering a query.

### 3. Document Loaders

`03_document_loaders_langchain.ipynb`

Explores loading external documents into an LLM application pipeline.

### 4. Text Splitters

`04_text_splitters_langchain.ipynb`

Covers splitting documents into smaller chunks suitable for retrieval and downstream processing.

### 5. Conversational RAG

`05_conversational_rag_langchain_openai.ipynb`

Extends RAG into a conversational workflow where previous conversation context can influence retrieval and generation.

### 6. LangGraph

The `langgraph_stage_*.ipynb` notebooks introduce graph-oriented LLM application workflows in multiple stages.

## Concepts Covered

```text
Documents
   |
   v
Loaders
   |
   v
Text Splitting
   |
   v
Retrieval / RAG
   |
   v
LLM Generation
   |
   v
Conversation

LangGraph adds explicit graph/state-based workflow orchestration.
```

## Technologies

- Python / Jupyter notebooks
- LangChain
- OpenAI
- Retrieval-Augmented Generation (RAG)
- LangGraph
- Document loaders and text splitters

## Getting Started

Open the notebooks with Jupyter Notebook, JupyterLab, or another compatible notebook environment. Configure the required LLM credentials as environment variables rather than placing secrets directly in notebooks.

Example pattern:

```bash
export OPENAI_API_KEY="your-key"
```

Do not commit real API keys to GitHub.

## Recommended Order

Follow the numbered notebooks first, then continue through the LangGraph stages. This provides a progression from basic LLM calls to retrieval, conversational memory/context, and stateful graph workflows.

## Project Status

This repository is a learning/tutorial collection rather than a single deployable application. Each notebook demonstrates a focused generative-AI concept or workflow.
