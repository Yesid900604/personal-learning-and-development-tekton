# Milestones

Project milestones define key achievements and progress checkpoints in my Artificial Intelligence and RAG learning path.

## Milestone Structure

Each milestone includes:
- **Goal**: What I want to accomplish.
- **Learning Objectives**: Specific skills or knowledge to gain from DataCamp and O'Reilly.
- **Deliverables**: Concrete artifacts, code repositories, or implementations.
- **Success Criteria**: How I'll know the milestone is complete.
- **Timeline**: Expected duration.

---

## Planned Milestones

## Milestone 1: Data Science & AI Foundations

**Goal**: Master Python fundamentals, data manipulation, and the core concepts of Large Language Models (LLMs).

**Learning Objectives**:
- Core Python programming and data handling using `pandas` and `numpy` (via DataCamp).
- Understanding LLM architectures, tokenization, and basic API consumption (via DataCamp & O'Reilly).
- Mastering basic Prompt Engineering techniques (Few-shot, Chain-of-Thought).

**Deliverables**:
- [x] Complete DataCamp track: *Científico de Datos con Python*.
- [ ] Complete DataCamp course: *Introduction to LLMs in Python*.
- [ ] Repository folder `/labs/01_prompt_engineering` with scripts testing different prompt templates.

**Success Criteria**:
- Successfully calling OpenAI/Ollama APIs using Python scripts.
- DataCamp certificates generated for the foundational blocks.

**Timeline**: Month 1 - Month 2

**Status**: In Progress

---

## Milestone 2: The Core RAG Ecosystem

**Goal**: Learn how to chunk documents, generate vector embeddings, and connect an LLM to a local Vector Database.

**Learning Objectives**:
- Understand text splitting (chunking) strategies without losing semantic context (O'Reilly *RAG in Action*).
- Master Vector Databases by learning how to index and query collections (ChromaDB/Pinecone).
- Learn the basics of LangChain and LlamaIndex for orchestration.

**Deliverables**:
- [ ] Complete DataCamp course: *Developing LLM Applications with LangChain*.
- [ ] Read Chapters 1-5 of O'Reilly's *"Inteligencia Artificial Generativa: Guía para desarrolladores"*.
- [ ] A working Python script that vectorizes a local Markdown folder and saves it into ChromaDB.

**Success Criteria**:
- Performing a semantic search query against the vector database and retrieving the most relevant document chunks.

**Timeline**: Month 3 - Month 4

**Status**: Not Started

---

## Milestone 3: First Local RAG Project & Advanced Retrieval

**Goal**: Build a fully functional, local Chatbot capable of answering questions based on personal PDFs or Markdown notes.

**Learning Objectives**:
- Connect the retrieval pipeline with the generation pipeline (RAG complete flow).
- Implement advanced retrieval techniques like Re-ranking to optimize context quality.
- Handle chat memory and context window limitations.

**Deliverables**:
- [ ] Read O'Reilly's *"Procesamiento del Lenguaje Natural con Transformers"*.
- [ ] **[Project 1]** Create a functional local application (`/projects/local_doc_chat`) using Streamlit/Gradio, LangChain, and Ollama.
- [ ] Document the system architecture in the `/documentation/architecture` folder.

**Success Criteria**:
- The application answers user questions based strictly on the uploaded PDFs, accurately citing the source chunks without hallucinations.

**Timeline**: Month 5 - Month 6

**Status**: Not Started

---

## Progress Overview
- **Total Milestones**: 3
- **Completed**: 0
- **In Progress**: 1
- **Upcoming**: 2
