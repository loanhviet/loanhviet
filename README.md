# Hi, I'm Viet 👋

🔍 Interested in Machine Learning, LLM applications, information retrieval, and end-to-end AI systems
🌱 Currently learning and building with multi-agent systems, RAG, FastAPI, and Docker

I enjoy building practical systems that connect data processing, machine learning models, APIs, and user-facing applications.

## Featured Projects

### 🧩 [Multi-Agent Customer Intelligence Assistant](https://github.com/loanhviet/multi-agent-customer-intelligence)
A production-shaped, approval-first multi-agent system that turns an inbound customer email into a cited, evidence-grounded briefing — researched automatically, then reviewed and approved by a human before anything is sent.
- 7-agent LangGraph workflow (email, company resolution, web research, calendar, semantic memory, report generation, human approval)
- Durable PostgreSQL checkpointing that survives restarts and resumes exactly at a pending approval
- Approval-first safety model: every outbound action is bound to a SHA-256 hash of the exact content shown to the reviewer
- 6-gate Tool Harness (schema, auth, scope/approval, rate limit, audit, execute) in front of every external call
- Evidence-grounded report generation separating fact / inference / conflict / unknown per claim, backed by a semantic-memory RAG layer (PostgreSQL + Qdrant)
- 290+ automated tests at 90%+ coverage; deployed via Docker Compose on AWS EC2

### 🤖 [Drive Agent](https://github.com/loanhviet/drive-agent)
An LLM agent that connects to Google Drive through guarded tool calling and user-scoped semantic memory.
- JWT-authenticated chat workflow
- Six-step Tool Registry for validation, authorization, rate limiting, auditing, and execution
- Read-only Google Drive document extraction
- Qdrant semantic memory and SQLite chat history
- SSE chat streaming and persistent audit logs
- End-to-end demo available in the repository

### 🔍 [AI Image Detector](https://github.com/loanhviet/ai-generated-image-detector)
A machine learning system for detecting AI-generated images using handcrafted image features and XGBoost.
- Trained and evaluated on more than 86,000 images
- FFT, GLCM, residual noise, and color-based features
- Achieved ROC-AUC of 0.9356
- Deployed with Streamlit on Hugging Face Spaces
- [Live Demo](https://loanhviet-ai-image-detector.hf.space/)

## Current Focus
- Multi-agent systems and LangGraph orchestration
- Retrieval-Augmented Generation and semantic search
- FastAPI backend development
- Docker-based AI application deployment
- Testing and reliable software workflows

## Technologies
`Python` · `TypeScript` · `FastAPI` · `LangGraph` · `Docker` · `Git` · `SQL` · `PostgreSQL` · `Qdrant` · `Elasticsearch` · `Scikit-learn` · `XGBoost`

## Contact
📧 [loanhviet.mmo@gmail.com](mailto:loanhviet.mmo@gmail.com)
📱 +84 354 712 005
📍 Hanoi, Vietnam
