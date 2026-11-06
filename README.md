# Denis Klimenko

**Backend & AI Engineer** — Python / FastAPI · Node.js · PostgreSQL / Redis · Rust / Tauri

Two years of production code: commercial work at **Kastamonu Integrated Wood Industry LLC**
(TvKast digital signage and the kdz internal ticketing system — client code stays closed
under contract) alongside my own open-source projects with public releases.
Six extracted modules are public below — the algorithm, not the product — each with tests and CI.

---

## Open-source modules

| Repository | What it is | Origin |
|---|---|---|
| [`transcript-segmenter`](https://github.com/klimenkod406/transcript-segmenter) | Groups a flat ASR transcript into logical paragraphs by silence, speaker change and sentence boundaries. CJK-aware. **Rust** | my own project (Sofia) |
| [`whisper-vtt-parser`](https://github.com/klimenkod406/whisper-vtt-parser) | Parses both output formats of `whisper.cpp` — the `.vtt` file and the stdout progress stream — into timed segments. **Rust** | my own project (Sofia) |
| [`recsys-core`](https://github.com/klimenkod406/recsys-core) | Recommendation core as pure functions: item-item collaborative filtering, MMR diversity re-ranking, trending score, time-decayed taste profiles. **Python** | my own project (MIYU) |
| [`canvas-audio-visualizer`](https://github.com/klimenkod406/canvas-audio-visualizer) | Canvas 2D visualiser core: FFT band splitting, bass-spike beat detection with tempo tracking, palette interpolation, ring geometry. **TypeScript** | my own project (MIYU) |
| [`express-security-middleware`](https://github.com/klimenkod406/express-security-middleware) | Tiered rate limiting with four independent budgets, plus upload validation with allowlist and blocklist. **Node.js** | client project (signage platform) |
| [`winston-audit-logger`](https://github.com/klimenkod406/winston-audit-logger) | Structured audit logging with a dedicated security stream, separated from the general log. **Node.js** | client project (ticketing system) |

## Projects

- [`sofia`](https://github.com/klimenkod406/sofia) — local-first desktop workspace: Tauri 2 + Rust + React, Whisper transcription via an external process, SQLite FTS5 search, in-app calendar, CI on Linux / Windows / macOS.
- [`llmborn`](https://github.com/klimenkod406/llmborn) — a browser game about how AI models learn, from tokens to real training.

## Stack

**Backend & AI** — Python 3.11+, FastAPI, SQLAlchemy 2, Pydantic, asyncio, httpx, REST API, WebSocket, Node.js, Express

**Data** — PostgreSQL, SQLite (FTS5), Redis with RQ, SQL, migrations, indexes

**AI** — sentence-transformers, embeddings and vector search with hnswlib (HNSW), faster-whisper, whisper.cpp, llama.cpp, GGUF, prompt engineering

**Frontend** — TypeScript, React 18, Vite, Tailwind CSS, Radix UI, Zustand, TanStack Query, Tiptap, Canvas 2D

**Systems** — Rust, Tauri 2, sqlx, serde, Repository pattern, Tauri commands, GitHub Actions matrix builds

**Platform** — Docker Compose, Nginx, Prometheus metrics, cron, Linux, Git

**Quality** — pytest, vitest, ESLint, Prettier, mypy strict, ruff, cargo test, clippy

## Contact

- GitHub — [@klimenkod406](https://github.com/klimenkod406)
- Telegram — [@Klim82938](https://t.me/Klim82938)
- Email — [klimenkod406@gmail.com](mailto:klimenkod406@gmail.com)
- LinkedIn — [denis-klimenko-734341441](https://www.linkedin.com/in/denis-klimenko-734341441)
- Portfolio — [klimenkod406.github.io/portfolio](https://klimenkod406.github.io/portfolio/)
