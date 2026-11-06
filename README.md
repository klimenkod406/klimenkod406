# Denis Klimenko

**Backend & AI Engineer** — Python / FastAPI / RAG · TypeScript / React · Rust / Tauri

Building low-latency AI backends and the clients that talk to them.

---

### Open-source modules

Each of these is an independent, tested implementation extracted from
commercial work — the algorithm, not the product.

| Repository | What it is |
|---|---|
| [`transcript-segmenter`](https://github.com/klimenkod406/transcript-segmenter) | Group a flat ASR transcript into logical paragraphs by silence, speaker change and sentence boundaries. CJK-aware. **Rust** |
| [`whisper-vtt-parser`](https://github.com/klimenkod406/whisper-vtt-parser) | Parse both output formats of `whisper.cpp` — the `.vtt` file and the stdout progress stream — into timed segments. **Rust** |
| [`recsys-core`](https://github.com/klimenkod406/recsys-core) | Recommendation core as pure functions: item-item collaborative filtering, MMR diversity re-ranking, trending score, time-decayed taste profiles. **Python** |
| [`canvas-audio-visualizer`](https://github.com/klimenkod406/canvas-audio-visualizer) | Canvas 2D visualiser core: FFT band splitting, bass-spike beat detection with tempo tracking, palette interpolation, ring geometry. **TypeScript** |
| [`express-security-middleware`](https://github.com/klimenkod406/express-security-middleware) | Tiered rate limiting with four independent budgets, plus upload validation with allowlist and blocklist. **Node.js** |
| [`winston-audit-logger`](https://github.com/klimenkod406/winston-audit-logger) | Structured audit logging with a dedicated security stream, separated from the general log. **Node.js** |

### Projects

- [`sofia`](https://github.com/klimenkod406/sofia) — local-first desktop workspace: Tauri 2 + Rust + React, Whisper transcription, SQLite FTS5, in-app calendar.
- [`llmborn`](https://github.com/klimenkod406/llmborn) — a browser game about how AI models learn, from tokens to real training.

### Stack

**Backend & AI** — Python 3.11+, FastAPI, Asyncio, Pydantic, PostgreSQL, pgvector, Redis, Celery, RAG pipelines, hybrid retrieval, MCP / agentic workflows, Whisper, llama.cpp, hnswlib

**Frontend** — TypeScript, React 18/19, Next.js, Tailwind CSS, Zustand, WebSocket / SSE, Canvas 2D, Web Audio API

**Systems** — Rust, Tokio, Tauri v2, native OS APIs, IPC bridges, cross-platform CI/CD

**Platform** — Docker, PostgreSQL, Redis, SQLite, Linux administration, GitHub Actions

### Contact

- GitHub — [@klimenkod406](https://github.com/klimenkod406)
- Portfolio — [klimenkod406.github.io/portfolio](https://klimenkod406.github.io/portfolio/)
