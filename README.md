<div align="center">

# Lo Anh Viet

**AI Engineer** · Final-year AI & Data Science student at Thuy Loi University · Hanoi, Vietnam

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=1500&color=2F81F7&center=true&vCenter=true&width=520&height=40&lines=LLM+Applications+%26+AI+Agents;RAG+%26+Retrieval+Pipelines;On-device+AI+Inference;End-to-end+AI+Engineering" alt="LLM Applications & AI Agents · RAG & Retrieval Pipelines · On-device AI Inference · End-to-end AI Engineering" />

<p>
  <a href="https://loanhviet.dev"><img src="https://img.shields.io/badge/Portfolio-loanhviet.dev-2F81F7?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/loanhviet"><img src="https://img.shields.io/badge/LinkedIn-loanhviet-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:loanhvietfw@gmail.com"><img src="https://img.shields.io/badge/Email-loanhvietfw%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

## About Me

I build practical AI applications end to end: from model inference and LLM pipelines to backend services, deployment, and the product people actually use.

- **Focus:** LLM applications, RAG systems, AI inference, and AI model deployment.
- **Experience:** AI Engineer Intern at **Apal Tech** (Aug – Oct 2026), analyzing and debugging RAGFlow's retrieval pipeline (chunking, embedding, vector storage, retrieval, reranking) and studying OpenViking's retrieval and memory architecture.
- **Open to:** AI Engineer internship and entry-level opportunities.

---

## Featured Projects

### 🎙️ [OpenDubber](https://dubber.loanhviet.dev/) — Live Vietnamese AI Dubbing for Chrome

A published Chrome extension that translates English video subtitles with an LLM and speaks them in Vietnamese, synchronized with playback on YouTube, Udemy, and Coursera.

- Runs Kokoro TTS **on-device** with ONNX Runtime Web (WebGPU, WASM fallback) — **4× faster than real time** on a laptop GPU.
- FastAPI translation backend with structured output, caching, provider fallback, and rate limiting; picked the production model by comparing 4 LLMs on blind LLM-as-judge scores, latency, and load tests.
- Speech synced to the video clock, with pitch-preserving speed-up and a catch-up mode for slow CPUs.

`TypeScript` `Chrome MV3` `ONNX Runtime Web` `WebGPU` `Web Audio API` `Python` `FastAPI` `Gemini`

**[Website](https://dubber.loanhviet.dev/)** · **[Chrome Web Store](https://chromewebstore.google.com/detail/dlbebalamknjefgmpibopjogdhdclpdi)**

### 🛰️ [Crop Mapping](https://crop.loanhviet.dev/) — Satellite Crop-Type Mapping Web App

A geospatial web app for crop-type segmentation from Sentinel-2 satellite time series. Reproduced TSViT (CVPR 2023) by retraining the original implementation on the PASTIS24 benchmark.

- Draw an area on the map; the backend prepares the time series, runs inference, and returns crop maps (GeoTIFF/GeoJSON) with area statistics.
- Dockerized deployment on Oracle Cloud ARM64.
- GitHub Actions pipeline that tests, builds, and deploys, rolling back automatically if health checks fail.

`Python` `PyTorch` `TSViT` `FastAPI` `Leaflet` `Docker` `GitHub Actions` `Oracle Cloud`

**[Live Demo](https://crop.loanhviet.dev/)** · **[GitHub](https://github.com/loanhviet/crop-mapping)**

### 🤖 [Drive Agent](https://github.com/loanhviet/drive-agent) — LLM Assistant with Google Drive Integration

An LLM assistant combining controlled tool calling, semantic memory, and authenticated backend APIs.

- Read-only Google Drive integration with guarded tool execution.
- JWT-authenticated chat APIs with SSE streaming.
- Qdrant semantic memory, SQLite conversation history, and Docker deployment.

`Python` `FastAPI` `Qdrant` `SQLite` `Docker`

**[GitHub](https://github.com/loanhviet/drive-agent)**

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,cpp,pytorch,sklearn,fastapi,sqlite,docker,githubactions,git,linux&perline=11" alt="Python, TypeScript, C++, PyTorch, Scikit-learn, FastAPI, SQLite, Docker, GitHub Actions, Git, Linux" />
</p>

- **AI & LLM:** RAG · Hybrid Retrieval · Tool Calling · Prompt Engineering · LLM-as-Judge Evaluation
- **ML & Inference:** PyTorch · Vision Transformer (TSViT) · Scikit-learn · XGBoost · ONNX Runtime Web · WebGPU · Neural TTS
- **Backend & Engineering:** FastAPI · Qdrant · SQLite · Docker · GitHub Actions · Git · Linux

---

## Current Focus

- Building reliable LLM applications and AI agents.
- Improving retrieval pipelines and RAG systems.
- Optimizing AI model inference and deployment.

---

<div align="center">

**Let's connect** — [loanhviet.dev](https://loanhviet.dev) · [LinkedIn](https://www.linkedin.com/in/loanhviet) · [loanhvietfw@gmail.com](mailto:loanhvietfw@gmail.com)

</div>
