# Hoàng Mạnh Cường (Cuong)

**Tools Engineer · Perception Data Tooling** — ADAS / autonomous-driving data

I build the internal tooling that perception-data pipelines depend on: automated QC checks, release gates and CVAT extensions that replace manual, subjective steps (2D / 3D / LiDAR annotation QC). Backend background in Java (exchange-side trading systems) and NestJS (healthcare / EHR), plus applied AI (LLMs, RAG, computer vision).

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [VPT LabelX](https://github.com/cuongherok4/vpt-cvat-extension3D) | Chrome extension (Manifest V3) that runs 3D cuboid QC inside CVAT: ground snapping, heading, point-fit, ghost-box and class-size checks, issue list that jumps to the exact frame and box, report export (.xlsx / CSV / JSON / HTML). Runs fully in the browser, no network calls. | JavaScript, Playwright |
| [Privacy–Utility Release Guard](https://github.com/cuongherok4/privacy-utility-release-guard) | Face and licence-plate anonymisation: detector × redaction sweep, attacker-based re-identification metric, configurable PASS / WARN / FAIL release gate, plus an annotation studio. | Python, OpenCV, Ultralytics |
| [AI Scam Call Detection](https://github.com/cuongherok4/ai-scam-call-detection-backend) | Scam-call detection for Vietnamese using cross-language embedding retrieval over a Chinese scam-call corpus, self-hosted LLM + vector DB. Published in VJAI ([paper](https://vjai.org.vn/vn/vjai/article/view/21/190)). | Python, Ollama (Qwen2.5), ChromaDB, multilingual-e5-base |
| [RAG-Pipeline](https://github.com/cuongherok4/RAG-Pipeline) | Step-by-step RAG toolkit: 9 pipeline stages (chunking, embedding, hybrid retrieval, cross-encoder reranking, citation prompting, generation) with every intermediate result visible. | Python, Streamlit, FAISS, Ollama |
| [VPT Code Arena](https://github.com/cuongherok4/vpt-code-arena) | Online coding platform with automatic code judging (Java backend portfolio project). | Java |

## Tech stack

- **Languages:** Java, JavaScript / Node.js, Python
- **Backend:** REST APIs, NestJS, microservices, Kafka, Redis
- **Databases:** MySQL, PostgreSQL (pgvector), MongoDB; ClickHouse + Superset, Spark
- **DevOps:** Docker, Jenkins, GitLab CI/CD, Git, Linux, Grafana
- **AI:** LLMs, RAG, Ollama, ChromaDB, FAISS, OpenCV, Ultralytics, MCP

## Experience

- **Java Developer, HT Vietnam Group** (12/2025 – 10/2026): backend for the Mercantile Exchange of Vietnam (MXV).
- **Full Stack Developer, Digi Dinos** (08/2025 – 12/2025): NestJS backend for healthcare / EHR modules.
- **VinUni — Vingroup AI20K, Cohort 4A** (2026 – present): applied AI, perception-data annotation and QC.

## Contact

[hmc.it.vn@gmail.com](mailto:hmc.it.vn@gmail.com) · [LinkedIn](https://www.linkedin.com/in/hmcuong/)
