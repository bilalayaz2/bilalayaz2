<h1 align="center">Muhammad Bilal Ayaz</h1>
<h3 align="center">Senior AI Engineer | RAG, AI Agents & LLM Evaluation | Python, FastAPI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/bilalayaz2">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mbilalayaz02@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I am a Pakistan-based **Senior AI Engineer** focused on building production-oriented LLM applications, RAG pipelines, and agentic workflows using Python. My strongest differentiator is the combination of **building real-world AI systems** and **rigorously testing their reliability** under realistic and adversarial conditions.

### 🎯 Core Focus Areas
- **LLM Applications:** Deterministic orchestration, structured outputs, prompt chaining.
- **RAG & Semantic Retrieval:** Dense/sparse retrieval, semantic chunking, ontology mapping.
- **AI Agents & Tool Calling:** ReAct workflows, Model Context Protocol (MCP), state mutation.
- **Evaluation & Reliability:** LLM-as-a-Judge, golden trajectories, adversarial testing, SQL/state verification.
- **Backend Architecture:** Event-driven Python microservices (FastAPI, Celery, Kafka), asynchronous processing, Docker.

---

### 🚀 Selected Engineering Work

| Project | What it demonstrates |
|---------|----------------------|
| **[AST-PARSER](https://github.com/bilalayaz2/AST-PARSER)** | Production LLM PR code review system utilizing **LangGraph parallel evaluators**, AST-based semantic chunking, Qdrant RAG, and FastAPI/Celery workers with deterministic retry loops. |
| **ClinicoMap Architecture** | Event-driven hybrid ingestion for 200+ page clinical protocols. Demonstrates boundary-aware semantic chunking and ontology mapping with Bio_ClinicalBERT. |
| **Multimodal Content Summarizer** | Tiered fallback pipelines (Newspaper3k → yt-dlp → Whisper ASR). Demonstrates long-context batching and Sentence-BERT timestamp navigation. |
| **Agent Evaluation Harness** | *In development:* Golden trajectories, tool-call validation, and deterministic state checks for evaluating LLM agent reliability. |

---

### 🛠️ Technical Stack

**AI / Machine Learning**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?style=for-the-badge&logo=OpenAI&logoColor=white) ![LangChain](https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
*ReAct, RAG, Tool Calling, Semantic Search, BERT, LoRA, QLoRA*

**Backend / Distributed Systems**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Celery](https://img.shields.io/badge/celery-%2337814A.svg?style=for-the-badge&logo=celery&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
*Microservices, Async Processing, Qdrant, REST APIs*

**Evaluation & Quality**
*Adversarial Testing, LLM Evaluation, Structured Output Validation, RLHF/RLAIF*

---

### 💡 Engineering Principles
- **Measure everything:** Make model behavior measurable; prefer deterministic checks over LLM-as-a-judge where possible.
- **Version control:** Treat prompts, schemas, and evaluation datasets as first-class versioned software assets.
- **Transparency:** Document limitations, failures, and threat models instead of hiding them.
