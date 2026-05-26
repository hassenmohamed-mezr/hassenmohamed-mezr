# Hassen Mohamed Hassen

**Generative AI Engineer · RAG Systems · LLM Engineering · Arabic NLP**

Minya, Egypt &nbsp;|&nbsp; [hassen.Mohamed3338@compit.aun.edu.eg](mailto:Hassen.Mohamed3338@compit.aun.edu.eg) &nbsp;|&nbsp; [LinkedIn](https://linkedin.com/in/hassen-mohamed-91539835b)

---

AI engineer focused on building end-to-end retrieval-augmented generation (RAG) systems, LLM orchestration pipelines, and AI-integrated backends. Work spans embedding generation, hybrid retrieval, cross-encoder reranking, Arabic NLP engineering, and FastAPI microservice design. Approach is experimentation-driven — building, benchmarking, and optimizing rather than assembling off-the-shelf components.

---

## Engineering Focus

- **RAG Pipeline Architecture** — hybrid retrieval, fusion scoring, reranking, context assembly
- **Vector & Sparse Retrieval** — FAISS, BM25, dense-sparse fusion, retrieval evaluation
- **Arabic NLP Engineering** — morphological preprocessing, tokenization normalization, legal domain adaptation
- **LLM Orchestration** — LangChain, Ollama, prompt engineering, hallucination reduction
- **AI Backend Integration** — FastAPI AI microservices, REST API design, retrieval/generation decoupling

---

## Technical Stack

| Category | Technologies |
|---|---|
| **Languages** | Python, SQL, C++, C#, Java |
| **Generative AI & LLMs** | LangChain, Ollama, Qwen 2.5, Prompt Engineering, RAG Pipelines |
| **NLP & Retrieval** | Sentence Transformers, Cross-Encoders, FAISS, BM25, Hybrid Search, Retrieval Fusion, Reranking |
| **AI/ML Frameworks** | Hugging Face Transformers, PyTorch, TensorFlow, Scikit-learn |
| **Backend & APIs** | FastAPI, ASP.NET MVC, REST APIs, JWT Auth, RBAC |
| **Data Engineering** | Pandas, NumPy, Text Preprocessing, Dataset Cleaning |
| **Tools & Platforms** | Git, Streamlit, SQLite |

---

## Flagship Project

### [Egyptian Legal AI System — Arabic Labor Law QA Engine](https://github.com/hassenmohamed-mezr/Egyptian_legal_ai_agent)

> End-to-end RAG system for Arabic legal question answering over Egyptian labor law. Every layer is custom-designed — from document ingestion through retrieval fusion, reranking, and LLM response generation.

**Architecture highlights:**

- Hybrid retrieval combining dense vector search (FAISS + Sentence Transformers) with sparse keyword retrieval (BM25), fused via a weighted scoring mechanism to maximize recall and precision across retrieval modalities
- Domain-specific chunking strategy for Arabic legal documents — handles clause boundaries, article hierarchies, and formal Arabic morphological ambiguities that break standard tokenization
- Cross-encoder reranking as a second-stage refinement layer, improving candidate relevance before context passes to the LLM
- Full query pipeline: natural language input → embedding generation → parallel BM25 + FAISS retrieval → weighted fusion → cross-encoder reranking → context assembly → Qwen 2.5 via Ollama
- Addressed Arabic NLP challenges: morphological ambiguity, dialectal variation, inconsistent tokenization, noisy legal dataset preprocessing
- Query expansion and dynamic chunk selection to improve LLM grounding accuracy on ambiguous legal queries
- Exposed as a FastAPI service with structured endpoints, decoupling retrieval and generation from any frontend or integration layer
- Iterative benchmarking over embedding model selection, chunk sizes, retrieval weights, and reranker thresholds against manual evaluation benchmarks

`Python` `FAISS` `BM25` `Sentence Transformers` `Cross-Encoders` `LangChain` `FastAPI` `Qwen 2.5` `Ollama` `Arabic NLP`

---

## Selected Projects

### [Hospital Management System with Integrated AI Assistant](https://github.com/hassenmohamed-mezr/HospitalInformationSystem)

Full-stack hospital management platform with a FastAPI-based RAG microservice integrated via REST API — demonstrating multi-service AI/backend architecture in a real operational context.

- Standalone AI microservice decoupled from the main backend, integrated cleanly via REST
- ASP.NET MVC backend with layered controller-service architecture handling multi-role workflows
- JWT authentication and RBAC securing patient records and operations across user roles
- RAG assistant retrieves contextually relevant medical records and operational data, reducing staff query overhead

`C#` `ASP.NET MVC` `FastAPI` `Python` `SQLite` `RAG` `REST API`

---

### [Breast Cancer Image Classification](https://github.com/hassenmohamed-mezr/Breast-Cancer-Image-Classification)

Multi-model benchmarking pipeline for medical image classification, comparing classical ML approaches against CNN architectures with full custom training infrastructure.

- Built a preprocessing pipeline from scratch — augmentation, normalization, noise reduction — without high-level wrappers
- Custom training loop with manual backpropagation control and optimizer tuning
- Achieved ~85% accuracy with classical baselines; improved generalization through CNN experimentation

`Python` `TensorFlow` `Scikit-learn` `NumPy` `Medical Imaging`

---

### [Linear Programming Solver](https://github.com/hassenmohamed-mezr/Linear-Programming-Solver)

Constraint-based LP solver implementing optimization algorithms for multi-variable mathematical problems. Focused on algorithmic correctness, numerical stability, and clean computational design.

`Python` `Mathematical Optimization` `Algorithmic Engineering`

---

### [Virtual File System Emulator](https://github.com/hassenmohamed-mezr/Virtual-File-System-Emulator)

Low-level file system simulation covering file allocation, directory management, and storage modeling. Built to develop systems-level thinking beyond typical application development.

`C` `Operating Systems` `File Allocation` `Memory Simulation`

---

## Current Technical Interests

- Retrieval evaluation methodologies and benchmarking pipelines for RAG systems
- Advanced Arabic NLP preprocessing and domain adaptation for legal and formal text
- Multi-stage reranking architectures and retrieval quality optimization
- Agentic LLM workflows and tool-augmented reasoning systems
- AI backend design patterns — retrieval/generation decoupling, microservice integration

---

## Engineering Philosophy

Build systems that can be evaluated, not just demonstrated. Retrieval quality, grounding accuracy, and latency behavior matter more than getting an LLM to respond. Every architectural decision should be driven by what breaks at scale or under adversarial inputs — not what works in the tutorial.

---

## Contact

- **Email:** [Hassen.Mohamed3338@compit.aun.edu.eg](mailto:Hassen.Mohamed3338@compit.aun.edu.eg)
- **LinkedIn:** [linkedin.com/in/hassen-mohamed-91539835b](https://linkedin.com/in/hassen-mohamed-91539835b)
- **GitHub:** [github.com/hassenmohamed-mezr](https://github.com/hassenmohamed-mezr)
