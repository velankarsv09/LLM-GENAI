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

## Phase 3 — Agentic RAG App
A hybrid AI agent combining RAG with tool-calling. The agent autonomously decides which tools to use, chains multiple tools in sequence, and maintains memory across conversation turns.

### What it does
- Creates custom tools using the `@tool` decorator
- Builds an agent that chooses between tools autonomously
- Wraps the full RAG pipeline as an agent tool
- Chains multiple tools in sequence to complete complex goals
- Maintains conversation memory across multiple turns
- Interactive CLI agent — ask anything, the agent figures out the steps

### Stack
- Python
- LangChain + LangGraph
- ChromaDB
- HuggingFace Embeddings (all-MiniLM-L6-v2)
- Groq API (Qwen3-32B)

### Tools built
- `calculate` — math evaluation
- `get_ai_info` — knowledge lookup
- `word_count` — string analysis
- `search_documents` — RAG retrieval tool
- `summarize_text` — LLM summarization tool
- `answer_from_document` — full RAG pipeline as a single tool

### Skills covered
- Custom tool creation and docstring engineering
- Agent reasoning and autonomous tool selection
- Multi-tool chaining
- RAG + Agent hybrid architecture
- Conversation memory management
- Interactive agentic CLI application

---

## Author
Shruti Sameer
