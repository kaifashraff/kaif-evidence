# TECHNICAL SKILLS MATRIX
**Rule:** a skill is listed only if a file, build, repo, or running system on this machine proves it. Proficiency = depth of artifact, not self-rating.

| Skill | Level | Evidence (path / artifact) | Confidence |
|---|---|---|---|
| **Python** | Advanced | ~10,229 `.py` files on Desktop alone; 1,677 in `jarvis/`; 1,473 in `hermes-webui`; pipelines in `agnes-output`, `quran-ir`, `finance-tracker/backend`, `perf-marketing-eval/funnel_model.py` | HIGH |
| **TypeScript / JavaScript** | Advanced | MathQuest (`Desktop/mathquest/src`), R Company OS (`JobHunt-Profile/R-Company/r-company-production-os-projects/app`), Next.js portfolio (`_OUT/kaif-portfolio-next`), 1,230 `.ts` on Desktop | HIGH |
| **React / Next.js 14** | Advanced | 3 Next.js codebases with app-router, components, static export; `out/index.html` 86 KB built | HIGH |
| **Rust** | Intermediate–Advanced | `marketing-os/src/` — 10 modules, 33 KB `main.rs`, compiles to 0.7 MB release binary; `buzz-src` 1,192 `.rs` (vendored) | HIGH (own code) |
| **Node.js / Express** | Advanced | MathQuest server, `youtube-handler`, `delivero` generators, 26 repos with `package.json` | HIGH |
| **FastAPI / Python web** | Intermediate | `finance-tracker/backend`, `hermes-webui` (1473 py), `sitepulse` app (18 KB `main.py`) | HIGH |
| **SQLite** | Advanced | `mathquest.db`, `sitepulse.db`, Hermes `state.db`, `opencode.db` (11.4 GB) | HIGH |
| **PostgreSQL / MySQL** | Intermediate | MySQL 9.6 installed and running; Supabase schema + seed SQL in R Company OS | MEDIUM |
| **Docker** | Intermediate | `finance-tracker/docker-compose.yml`, `sitepulse/Dockerfile` + compose, `.dockerignore` | MEDIUM |
| **Git / GitHub** | Advanced | 45 repos on disk; 13 owned repos under `kaifashraff`; GitHub MCP wired; CI workflow in `sitepulse/.github/workflows/ci.yml` | HIGH |
| **Linux / WSL2** | Intermediate | WSL Ubuntu-24.04 in use; POSIX shell scripts; `/mnt/c` cross-boundary work in `omniroute` | MEDIUM |
| **Windows systems / ops** | Advanced | Scheduled-task escalation, Session-0 diagnosis, PowerShell automation, cua-driver manifests, service management | HIGH |
| **Agentic AI / multi-agent** | Advanced | 9-profile fleet, 100-worker swarm (`swarm/board.py`, `usage.py`), MCP servers, delegation protocol | HIGH |
| **LLM API integration** | Advanced | 15+ providers in `config.yaml`; `omniroute/audit/models.json` (433 KB); pooled client `tools/agnes/agnes_client.py` | HIGH |
| **Prompt engineering** | Advanced | Production prompt systems in `hermes` skills, `perf-marketing-eval`, `kimi_k3` scripts, video direction briefs | HIGH |
| **RAG / retrieval** | Intermediate | `quran-ir` (BM25 + vector), knowledge-base tooling in `data/scripts` | MEDIUM |
| **AI image generation** | Advanced | 94 PNG in `agnes-output`, 84 in `kimi_k3_gen`, 1,859 images on Desktop; ComfyUI installed | HIGH |
| **AI video generation** | Advanced | 25 MP4 in `agnes-output`, 103 in `kimi_k3_gen`, 140 on Desktop, 58 in OpenMontage; ffmpeg 9.0.1 pipelines | HIGH |
| **TTS / voice cloning** | Advanced | `tts-lab` (29 py, ONNX models), Bark, Qwen3-TTS, edge-tts Hindi, `kaif-voice-ref-0-12.mp3` reference | HIGH |
| **ffmpeg / media assembly** | Advanced | Concat pipelines, zoompan, compression ladders, 10m/20m documentary renders | HIGH |
| **Three.js / WebGL** | Intermediate | `racing-game-final.html` (589 KB), `blackhole-simulator.html`, `game-3d.html`, `cricket-3d.html`, `embed-three.js` | MEDIUM |
| **REST API design** | Intermediate | MathQuest `API.md`; FastAPI services; 15+ provider clients | MEDIUM |
| **Android / Kotlin** | Beginner–Intermediate | `upi-expense-tracker/` Gradle project + build artifacts | LOW–MEDIUM |
| **Web scraping** | Intermediate | `tariq-transcripts` (4,314 files), `Desktop/laqab-research/*.py` (trends, autocomplete, marketplace), DDG HTML scraping in `ddg/` | MEDIUM |
| **Data analysis** | Intermediate | `data/scripts/kb_inventory.py`, `kb_broken_refs.py`, `model-evals/live_test.py`, funnel models | MEDIUM |
| **Marketing analytics (GA4/GTM)** | Beginner (documented, not executed) | Plans in KALKI war room and `perf-marketing-eval/06-measurement-plan.md`; **no property export found** | LOW |
| **Google Ads** | Beginner–Intermediate (build-level) | 2 complete campaign builds with CSVs (`Dental-PPC`); **no live account, no spend** | LOW–MEDIUM |
| **Meta Ads** | Beginner–Intermediate (build-level) | Campaign structures + copy banks in KALKI; **no Ads Manager export** | LOW–MEDIUM |
| **SEO** | Intermediate (research-level) | Keyword/intent research, competitor ladders, blog timelines (VM Design Studio research pack, LAQAB zari market research) | MEDIUM |
| **CRO** | Beginner–Intermediate | Landing page HTML + CRO audit in KALKI; no A/B test results | LOW |
| **Video editing** | Intermediate–Advanced | Premiere/CapCut/DaVinci claimed; ffmpeg + Remotion evidence is real; GUI NLE project files not found | MEDIUM |
| **Graphic design** | Intermediate | 1,859 images incl. ad creatives, thumbnails, carousels; Canva/Figma claimed but no `.fig`/`.canva` project files | MEDIUM |

---

## Deliberately excluded (no evidence found)

- **SQL at production depth** — only basic query evidence.
- **Kubernetes / cloud infra (AWS/Azure/GCP)** — `.aws`/`.azure` config dirs exist, no deployments.
- **Mobile app store releases** — Android project exists, no signed release or Play listing.
- **Team leadership / people management** — no hiring, review, or team artifacts.
- **Formal ML training / fine-tuning results** — `agent-finetune` and `tinker-atropos` folders exist but no completed training run logs with metrics.
- **Certifications beyond Google Digital Garage** — no certificate files for any other claim.

---

## How to talk about proficiency in an interview

Say: *"I build and ship solo — Python, TypeScript, Rust, and enough ops to keep it running 24/7. My depth is in agent systems and media pipelines; my marketing knowledge is practical but campaign-level, not agency-scale."*
That sentence is fully defensible from this disk. Anything stronger is not.
