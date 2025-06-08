# MedQuery: Biomedical Reasoning Agent using GraphRAG + Qdrant

MedQuery is an intelligent biomedical assistant that performs reasoning over structured knowledge graphs and retrieves relevant community summaries using vector search with Qdrant. It is powered by a Graph-RAG architecture, integrates LlamaIndex, and uses Chainlit to provide an interactive chat UI.

---

## Features

- Graph-based retrieval using biomedical entity triplets
- Community detection for topic clustering
- Qdrant vector database for semantic search
- Meditron or OpenAI-compatible LLM for clinical reasoning
- Chainlit-powered conversational UI
- Ready for deployment on Colab, GPU/CPU environments

---

## Components

- `engine.py`: GraphRAG pipeline with Qdrant integration
- `agent.py`: Stateful MedQuery agent that manages chat history
- `app.py`: Chainlit app for UI-based interaction
- `GraphRAG_Qdrant.ipynb`: Notebook version for quick experimentation

---
