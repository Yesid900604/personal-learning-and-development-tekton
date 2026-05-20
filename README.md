# 📁 Repository Folder Structure & Blueprint

This document provides a deep dive into how this AI & RAG development repository is organized, the purpose of each directory, and the step-by-step onboarding process to advance through the learning phases.

---

## 🏗️ Detailed Folder Architecture

### 📚 [documentation/](./documentation/)
*Central repository for all learning materials, notes, and architectural patterns discovered during the O'Reilly readings and DataCamp practices.*
- **Concepts & Explanations:** Deep-dives into semantic vector spaces, cosine similarity, and chunking boundaries.
- **Architecture Diagrams:** Visual workflows of Naïve RAG and Agentic pipelines (data ingestion vs. user query runtime).
- **Best Practices & Patterns:** Documentation on token window optimization, prompt template constraints, and systemic evaluation.
- **Learning Notes & Summaries:** Chapter-by-chapter summaries of text-mining and generative AI manuals.

### 🛠️ [tech-stack/](./tech-stack/)
*Detailed specifications of technologies, tools, and dependencies required to build and execute the RAG system pipelines.*
- **Technology Selections & Versions:** Freezing runtime environments (e.g., Python 3.11+, ChromaDB, LangChain) to guarantee reproducibility.
- **Architectural Decisions (Why):** Documentation explaining why certain tools were chosen over others (e.g., local Ollama instance vs. OpenAI cloud API for privacy testing).
- **Installation & Setup Guides:** Step-by-step commands to build virtual environments (`.venv`), manage `requirements.txt`, and configure local environment variables (`.env`).
- **Configuration Details:** System prompt baselines and operational vector storage indexing parameter blueprints.

### 🎯 [milestones/](./milestones/)
*Project roadmap tracking core achievements, checkpoints, and technical targets.*
- **Milestone Definitions & Goals:** High-level overview of foundational, mid-tier, and production-level system targets.
- **Success Criteria:** Measurable technical indicators (e.g., *"Successfully querying a local vector store with zero hallucinations"*).
- **Timeline & Deliverables:** Deadlines, core target objectives, and expected code artifacts per learning sprint.
- **Progress Tracking:** Interactive markdown checklist updates visualizing active and upcoming execution tasks.

### 💻 [src/](./src/)
*Source code and enterprise implementation directory following production-level industry standards.*
- **All Executable Code & Solutions:** Production Python application folders, operational logic scripts, and localized configuration drivers.
- **Project Structure & Organization:** Decoupled layout segregating core tasks (`app/services/ingestion.py`, `app/services/retrieval.py`) into modular layers.
- **Implementation Examples:** Functional scripts displaying exact implementations of split chunkings and query routing.
- **Solution Artifacts:** Deployed local REST APIs or interactive multi-document user chat interfaces (Streamlit webapps).

---

## 🚀 Getting Started (Onboarding Guide)

Follow this structured protocol to kickstart your environment and follow along with the learning milestones:

1. **Define Your Learning Goal:** Customize the primary target objective located at the top of the root [README.md](./README.md) file.
2. **Document Your Tech Stack:** Navigate to the [tech-stack/](./tech-stack/) folder, build your Python virtual environment, and install the base RAG packages.
3. **Outline Your Milestones:** Customize timelines and deliverables inside the [milestones/](./milestones/) directory based on your personal available study hours.
4. **Document As You Learn:** Every time you finish a **DataCamp** module or an **O'Reilly** chapter, log your theoretical insights inside the [documentation/](./documentation/) directory.
5. **Begin Implementation:** Write clean, modular scripts under [src/app/](./src/) to test your newly acquired knowledge through hands-on coding.

---

## 📈 Progress Verification Checklists

When implementing new iterations inside this repository, ensure you consistently document:
- [ ] Key AI architectural concepts you discover in text-mining books.
- [ ] Technical design decisions you execute (e.g., selecting fixed-size chunking over overlapping tokens) and *why*.
- [ ] Clean code patterns and production-ready enterprise best practices.
- [ ] Active technical challenges, system bugs (such as context truncation), and their respective solutions.
- [ ] Clean Python code snippets accompanied by instructional inline explanations.
