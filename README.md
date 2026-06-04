# Generative AI & Agentic AI Frameworks

Welcome to the **GenerativeAIandAgenticAI** repository. This project serves as a comprehensive, hands-on development playground and production reference for building next-generation intelligent applications. It spans the spectrum from core Generative AI primitives—such as custom tokenizers, text embeddings, and advanced vector search mechanics—to fully autonomous Multi-Agent Systems (MAS) and complex Orchestration Frameworks.

---

## 🚀 Repository Architecture & Roadmap

This repository is organized logically into modules progressing from fundamental natural language processing to high-level multi-agent reasoning loops.

### 1. Primitives & Foundations
* **Tokenization & Vocabularies:** Custom Byte-Pair Encoding (BPE) implementations, merge trackers, and custom vocabulary logic (`vocab_train.py`, `my_bpe-vocab.json`).
* **Embeddings Processing:** Chunking strategies for complex unstructured data (e.g., PDFs, financial reports) and converting text into dense mathematical vectors using local text-transformers or commercial APIs.

### 2. High-Performance Knowledge Retrieval (RAG)
* **Vector Execution Engines:** Ingestion pipelines targeting low-latency, real-time vector search. Optimized for parallel data processing to scale retrieval queries effectively.
* **Hybrid Semantic Retrieval:** Dual-retrieval architectures pairing dense vector similarity with traditional deterministic metadata filtering to minimize model hallucinations.

### 3. Agentic AI & Orchestration
* **Autonomous Reasoning Loops:** Integration of advanced planning patterns (e.g., ReAct, Plan-and-Solve) allowing LLMs to independently invoke external APIs and execution environments.
* **Multi-Agent Systems (MAS):** Dedicated agent registries routing specific execution steps—such as file parsing, web searching, or mathematical calculations—across independent, collaborating AI personas.

---

## 🛠️ Technology Stack

* **Core Frameworks:** [LangChain](https://github.com/langchain-ai/langchain) / [LangGraph](https://github.com/langchain-ai/langgraph), [FastAPI](https://fastapi.tiangolo.com/) (Async High-Performance AI API Development)
* **Vector Engines & Search:** Optimized Vector Storage engines utilizing high-dimensional geometric indexing (HNSW/IVF).
* **Compute & Execution:** SIMD-accelerated execution pipelines handling columnar batches of embedded metrics and semantic profiles.
* **Tokenizers & Modeling:** HuggingFace `transformers`, `tiktoken`, OpenAI API backend wrappers.

---

## 🏃 Getting Started

### Prerequisites
* Python 3.10 or higher
* Docker (Optional, for containerized vector execution backends)

### 1. Clone the Repository
```bash
git clone [https://github.com/raisharad/GenerativeAIandAgenticAI.git](https://github.com/raisharad/GenerativeAIandAgenticAI.git)
cd GenerativeAIandAgenticAI
