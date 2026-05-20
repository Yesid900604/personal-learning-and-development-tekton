# Documentation

This folder contains all documentation, notes, and learning materials for this project.

## Contents

### 🧠 Concepts
*Core concepts and theoretical foundations derived from O'Reilly readings and AI fundamentals:*
- **Embeddings & Vector Spaces:** Mathematical representation of text and semantic similarity.
- **Chunking Strategies:** Semantic, fixed-size, and sliding window document splitting techniques for long texts (PDFs, Markdown).
- **LLM Architectures:** Internal mechanics of Large Language Models and the shift toward local deployment (Ollama, Hugging Face).

### 🗺️ Guides
*How-to guides and tutorials based on DataCamp practical tracks and local labs:*
- **Environment Setup:** Step-by-step guide to configuring Python virtual environments with `langchain`, `chromadb`, and API clients.
- **Vector Database Integration:** How to initialize, index, and query collections in ChromaDB or Pinecone.
- **Advanced Prompt Engineering:** Practical patterns (Few-shot, Chain-of-Thought) optimized for RAG system generation.

### 📐 Architecture
*Architecture decisions and system diagrams:*
- **Naïve RAG Pipeline:** Visual flow from user query, vector retrieval, context injection, to LLM generation.
- **Advanced Retrieval Flow:** Implementation of pre-retrieval (query rewriting) and post-retrieval (cohere re-ranking) mechanisms.

### 🔗 References
*Useful references, official documentations, and external resources:*
- **DataCamp Tracks:** Quick access to Python Data Science, Introduction to LLMs, and LangChain course syllabi.
- **O'Reilly Media Reading List:** Learning summaries for *"Generative AI"* (Anaya Multimedia) and *"Transformers"*.
- **Framework Docs:** Links to LangChain, LlamaIndex, and MCP (Model Context Protocol) specifications.

### ✍️ Notes
*Personal learning notes, daily logs, and reflections:*
- Weekly journals capturing theoretical breakthroughs, dynamic concepts (like the attention mechanism), and hands-on experimentation.

---

## Adding Documentation
As you learn and implement, document:
- **Key concepts you discover:** Definitions and intuitive explanations of complex terms (e.g., Cosine Similarity).
- **Decisions you make and why:** Structural choices like selecting *LangChain* over *LlamaIndex* for specific integration tasks.
- **Patterns and best practices:** Production-ready architectures for token optimization and system memory.
- **Challenges and solutions:** Troubleshooting code bugs (e.g., rate limits, context window truncation, embedding dimensions mismatch).
- **Code examples and explanations:** Snippets of clean Python code implementing specific components of the RAG pipeline.
