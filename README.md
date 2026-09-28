# Hi, I'm Abin Oommen Thomas 👋

**AI Engineer · MSc Artificial Intelligence (Dublin Business School) · Dublin, Ireland**

I build and ship LLM-powered applications end to end, from retrieval pipelines and evaluation to tested APIs, CI/CD and deployment.
Right now I'm focused on **Retrieval-Augmented Generation (RAG)**: making answers grounded, measurable and fast.

- 🎯 Looking for **Graduate AI Engineer / ML Engineer / Data Science** roles in Ireland (Stamp 1G, full work authorisation)
- 🔭 Currently improving retrieval quality in **Study RAG Tutor** with hybrid search (BM25 + vectors) and cross-encoder reranking
- 🌱 Learning: AI agents (LangGraph, tool calling, MCP), fine-tuning (LoRA) and MLOps
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/abinoommenthomas) or at abinoommen6@gmail.com

---

## 🚀 Featured projects

### [Study RAG Tutor](https://github.com/abinthomas9322/study-rag-tutor) · [Live demo](https://study-rag-tutor.vercel.app)
A full-stack, multi-user AI tutoring platform. Students upload course material into "course spaces" and get grounded, cited answers plus auto-generated quizzes.

- RAG pipeline end to end: chunking → ONNX embeddings (fastembed, CPU only) → vector search (sqlite-vec) → answers from the Groq LLM API
- Retrieval evaluation harness with a 50-question golden set that measures Hit@k and MRR
- Hybrid retrieval (BM25 + vectors, Reciprocal Rank Fusion) with cross-encoder reranking
- **100% backend test coverage** enforced in CI: ruff, mypy, bandit, CodeQL
- FastAPI backend on Render, React + Vite + shadcn/ui frontend on Vercel

`Python` `FastAPI` `React` `sqlite-vec` `fastembed` `Groq` `GitHub Actions`

### [RAG Document Assistant](https://github.com/abinthomas9322/-rag-document-assistant)
A Streamlit app that answers questions about your PDFs, retrieving relevant passages with Sentence-Transformers embeddings before generating grounded answers.

- Clean split between pure RAG logic and UI, with a test suite
- Production-style quality and security pipeline: ruff, mypy, bandit, pip-audit, pytest, gitleaks, Trivy, CodeQL

`Python` `Sentence-Transformers` `Groq` `Streamlit`

---

## 🛠️ Tech stack

**Languages:** Python · SQL · JavaScript/TypeScript

**GenAI & LLMs:** RAG · Prompt Engineering · Embeddings · Vector Search · Rerankers · Hugging Face · Sentence-Transformers · fastembed · Groq API

**ML & Data:** scikit-learn · Pandas · NumPy · Feature Engineering · Model Evaluation · Power BI

**Backend & Web:** FastAPI · REST APIs · React · Vite · Streamlit · SQLite / sqlite-vec

**Cloud & DevOps:** AWS · Azure · Vercel · Render · Git · GitHub Actions · CI/CD · pytest · CodeQL · Trivy

---

## 🎓 Background

- **MSc Artificial Intelligence**, Dublin Business School (2025–2026)
- **BCA, Mobile Application & Cloud Computing**, Sacred Heart College, Thevara (2024)
- Graduate Research Assistant (AI/ML) at DBS · Freelance Data Analyst · previously a Data Science with GenAI intern and a Cloud Technology intern

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=abinthomas9322&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abinthomas9322&layout=compact&hide_border=true" alt="Top languages" height="160" />
</p>
