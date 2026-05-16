# LLM & GenAI Practice
Hands-on LLM engineering projects built from scratch — covering pipelines, RAG systems, and agents.

---

## Phase 1 — Document-Aware LLM Pipeline
A production-ready LLM pipeline built using Python and Groq API.

### What it does
- Reads a knowledge base from a text file
- Loads structured data from CSV using pandas
- Matches each topic to relevant context from the knowledge base
- Calls an LLM with context-aware prompts
- Handles errors and retries automatically
- Saves all results to JSON

### Stack
- Python
- Groq API (LLaMA 3.1)
- Pandas

### Skills covered
- JSON file handling
- Prompt engineering
- File reading and text splitting
- CSV pipelines with pandas
- Error handling and retry logic
- Context-aware LLM prompting

---

## Phase 2 — RAG Q&A App
An interactive Q&A system that answers questions about any document using Retrieval-Augmented Generation.

### What it does
- Loads and chunks any text document
- Converts chunks into embeddings using HuggingFace sentence-transformers
- Stores embeddings in ChromaDB for fast semantic search
- Retrieves the most relevant chunks for any question
- Passes retrieved context to an LLM for accurate, grounded answers
- Interactive loop — ask as many questions as you like

### Stack
- Python
- LangChain
- ChromaDB
- HuggingFace Embeddings (all-MiniLM-L6-v2)
- Groq API (LLaMA 3.1)

### Skills covered
- Text splitting and chunking strategies
- Vector embeddings and semantic search
- ChromaDB vector database
- LangChain RAG pipeline
- Context-aware LLM prompting
- Interactive CLI application

---

## Phase 3 — Agents & Tool Use (coming soon)
Agentic workflows using LangChain agents and tool use.

---

## Author
Shruti Sameer
