# 🧠 Agentic Systems Lab (`agentic-systems-lab`)

> **From Core Python Systems to Production-Grade Agentic AI Architectures.**  
> Practical implementations of LangGraph state graphs, Model Context Protocol (MCP) servers, RAG pipelines, FastAPI backends, and containerized deployments.

---

## 🚀 Overview

This repository documents the progressive journey from foundational Python internals to stateful multi-agent systems, following a rigorous 90-day learning and practice roadmap.

### 🛠️ Tech Stack & Tooling
* **Core Language:** Python 3.12+ (Generators, Decorators, Typing, Asyncio)
* **Agentic Frameworks:** LangGraph (State Graphs, Cycles, Checkpointers), LangChain
* **Protocols & Standards:** Model Context Protocol (MCP)
* **Data & Schema:** Pydantic v2, ChromaDB, Qdrant
* **Backend & Serving:** FastAPI, Uvicorn, WebSockets
* **Infrastructure:** Docker, Dev Containers, Ollama (Local LLMs)

---

## 📂 Repository Architecture

```text
agentic-systems-lab/
├── 01-python-foundations/         # Environment setup, namespaces, scopes & style
├── 02-data-structures-and-ops/    # Mutability, strings, lists, sets, dicts, collections
├── 03-control-flow-and-functions/ # Conditionals, loops, walrus op, pure functions, LEGB
├── 04-generators-and-decorators/  # Yield, coroutines, yield from, custom decorators
├── 05-oop-and-system-design/      # Classes, polymorphism, encapsulation, custom errors
├── 06-llm-and-prompt-engineering/ # OpenAI / Gemini APIs, structured outputs, Pydantic
├── 07-rag-and-vector-databases/   # Chunking, embeddings, ChromaDB, retrieval pipelines
├── 08-agentic-workflows-langgraph/# State graphs, ReAct loops, memory & multi-agent systems
├── 09-mcp-servers-and-tools/      # Model Context Protocol servers and client tools
└── 10-production-deployment/      # FastAPI REST/streaming endpoints, Dockerfiles
```

---

## 📈 Learning & Practice Progress

- [ ] **Phase 1: Python Systems & Internals** (Sections 1–8)
- [ ] **Phase 2: OOP, Tooling & Containerization** (Sections 9–12)
- [ ] **Phase 3: LLMs, Pydantic & Prompt Engineering** (Sections 13–17)
- [ ] **Phase 4: RAG Pipelines & Semantic Search** (Sections 18–22)
- [ ] **Phase 5: Stateful Agents with LangGraph** (Sections 23–28)
- [ ] **Phase 6: MCP Servers & Production Deployment** (Sections 29–33)

---

## 💻 Quickstart

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/agentic-systems-lab.git
   cd agentic-systems-lab
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   # Windows:
   .\.venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
