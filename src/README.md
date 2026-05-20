# Source Code (💻 src/)

Source code and implementation directory following industry best practices for AI development.

## Project Structure & Organization

The codebase is organized into logical modules to maintain a clean separation of concerns throughout the data engineering and AI generation lifecycle:

```text
src/
├── app/                        # Main application package (Production ready)
│   ├── config.py               # API keys (OpenAI/Ollama) and Vector DB configurations
│   ├── main.py                 # Application entry point (FastAPI / Streamlit interface)
│   ├── controllers.py          # API endpoints handling user questions and chat sessions
│   ├── models.py               # Pydantic schemas for structured data inputs and outputs
│   └── services/               # Core AI logic layers
│       ├── ingestion.py        # Document loading, parsing, and custom text chunking
│       ├── embeddings.py       # Interfacing with embedding models (OpenAI, HuggingFace)
│       └── retrieval.py        # Querying Vector Databases and implementing Re-ranking
├── notebooks/                  # Jupyter Notebooks for raw experimentation and O'Reilly labs
└── tests/                      # Test suites using pytest
