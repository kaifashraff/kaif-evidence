# PROJECT INVENTORY — VERIFIED FROM DISK

**Legend:** ✅ VERIFIED (artifact on disk / live URL) · ◐ PARTIAL (docs exist, outcome unconfirmed) · ○ UNVERIFIED (idea only)
**Paths are absolute. Nothing here is inferred from a project name alone.**

---

## TIER 1 — Strongest portfolio projects

### 1. marketing-os — evidence-gated business OS ✅
- **Path:** `C:\Users\ADMIN\marketing-os\` (Rust, 23 source files, 0.7 MB release binary at `target/release/marketing-os.exe`)
- **Problem:** AI agent platforms let agents self-declare "done"; measured reality is ~6% of created companies ever earn a dollar.
- **Built:** 6 roles (strategist, copywriter, outreach, analyst, verifier, operator), 7 deterministic claim checks (`file_exists`, `file_contains`, `count_at_least`, `json_pointer_equals`, `url_status`, `command_exit`, `command_stdout_contains`), a gate in `gate::transition` that refuses `Done` without verified evidence, staleness detection, self-test module.
- **Status:** builds and runs; demo state in `demo/.mktos/state.json`; proof screenshot `demo/out/desktop-proof.png` (1.5 MB).
- **Why it matters:** original engineering with a defensible thesis. Best single portfolio piece.

### 2. MathQuest AI — adaptive learning platform ✅
- **Path:** `C:\Users\ADMIN\Desktop\mathquest\` (9,643 files incl. node_modules; TS + Express + SQLite)
- **Built:** Socratic tutoring engine, mastery/adaptive algorithm (`src/adaptive.ts`), multimodal explanations (Hindi/English text, SVG, video scripts), learner profile persistence, product spec + API spec + demo harness.
- **Evidence:** `README.md`, `PRODUCT_SPEC.md`, `API.md`, `mathquest.db`, `test-demo.ts`, `dist/`.
- **Status:** complete local build, runs at `localhost:8788`.

### 3. Hermes agent fleet + 100-worker swarm ✅
- **Paths:** `C:\Users\ADMIN\AppData\Local\hermes\` (gateway, config.yaml, 9 profiles), `...\hermes\swarm\` (100 identities, board.py, usage.py, roles.md, incident.md)
- **Built:** multi-profile Telegram gateway, cron scheduler, per-provider rate buckets (75 rpm aggregate), evidence-gated task board with `--accept` commands, model fallback chain with live verification, session-0 → session-1 escalation workaround.
- **Evidence:** running system, `gateway_state.json`, swarm docs, incident logs.

### 4. R Company production OS ✅
- **Path:** `C:\JobHunt-Profile\R-Company\r-company-production-os-projects\` (19,991 files) + `-desktop` (31,148 files)
- **Built:** Next.js app-router platform — orders, admin, worker assignment, kanban, quote/invoice panel, analytics charts, auth, PWA manifest + service worker, Supabase schema + seed SQL.
- **Evidence:** full `app/`, `components/`, `supabase/schema.sql`, `.next/` production build output.
- **Note:** partly scaffolded (some components 0 KB); a working prototype, not a live product.

### 5. finance-tracker — full-stack fintech app ✅
- **Path:** `C:\Users\ADMIN\Desktop\finance-tracker\` (18,178 files)
- **Built:** React + TypeScript + Tailwind frontend, Python FastAPI backend, Docker compose, auth service, portfolio, goals, analytics, AI chat, Monte Carlo simulation, a "Subway Surfers-inspired" financial-health mini-game.
- **Evidence:** `README.md` with mermaid architecture, `backend/`, `frontend/`, `docker-compose.yml`, `.github/`, `docs/`.

### 6. Documentary production — Big Bang + RSI + CJP ✅
- **Path:** `C:\JobHunt-Profile\Film-Documentaries\` (416 files)
- **Built:** 10-minute and 20-minute Big Bang documentary (raw/compressed/ultra/telegram renders, 213 MB raw), RSI documentary (script 29 KB, 24 clips, synced scenes, 3 narration mixes), CJP protest film (18 themed clips + concat + final 32 MB), NEET-2026 research brief + Hinglish voiceover script, storyboard + key visuals + image generation scripts.
- **Evidence:** rendered MP4s with real byte sizes, audio stems, scripts.

### 7. quran-ir — retrieval engine ✅
- **Path:** `C:\Users\ADMIN\quran-ir\` (`app/`, `bm25/`, `vec/`)
- **Built:** hybrid BM25 + vector retrieval over Quran text, app layer with run scripts for Windows and POSIX.
- **Evidence:** source + index JSON files.

### 8. perf-marketing-eval — honest marketing evaluation ✅
- **Path:** `C:\Users\ADMIN\perf-marketing-eval\` (17 files)
- **Built:** end-to-end 12-phase marketing eval for a fictional product (Cadence), with market research, positioning, channel/budget/funnel architecture, creative, landing page HTML, measurement plan, launch readiness, scorecard, **independent judge critique**, funnel model in Python, email copy (13 KB), market sizing (16 KB).
- **Why it matters:** the README publishes its own failure — 55/100 completeness, 42/100 veracity, "the plan optimizes a funnel that doesn't exist". This is evidence of intellectual honesty and evaluation design.

### 9. kaif-ai — live portfolio ✅
- **URL:** https://kaifashraff.github.io/kaif-ai/ — **HTTP 200 verified 2026-11-16**
- **Path:** `C:\JobHunt-Profile\_OUT\kaif-portfolio-next\` (Next.js 14, static export in `out/`)
- **Built:** hero with system-status widget, AI layer, work/research/lab/about/contact sections, typed data layer (`lib/data/projects.ts`), robots + sitemap routes.

### 10. omniroute — provider routing layer ✅
- **Path:** `C:\Users\ADMIN\omniroute\`
- **Built:** audit of providers (13 KB), models (433 KB), health checks, benchmark results CSV, a 23 KB integration protocol.
- **Status:** audit + benchmark complete; full integration partial.

---

## TIER 2 — Solid supporting work

| # | Project | Path | What exists | Status |
|---|---|---|---|---|
| 11 | VM Design Studio client package | `Desktop\VM-Client-Deliverables\` | 7-page growth-partner proposal (PDF), 11-slide research deck (PDF), research pack zip, Agnes provider manager | ✅ Real client-facing deliverable |
| 12 | KALKI performance war room | `C:\JobHunt-Profile\KALKI\` (24 files) | Brand/market analysis, personas, funnel + media strategy, Google/Meta/X ad plans + copy banks, CRO audit, UTM/tracking, budget + 30/60-day roadmaps, reporting template, case study, interview prep | ◐ Spec portfolio (no live spend) |
| 13 | Dental PPC demo campaigns | `JobHunt-Profile\Dental-PPC\` | 2 full Google Ads builds: campaign plan, build CSV, negative keywords, launch checklist (US + India variants) | ◐ Demo, not live |
| 14 | CropeAI (crof.ai) brand work | `JobHunt-Profile\CropeAI\` | Landing pages (HTML), 6 brand images, X-ads configuration walkthrough (MD + DOCX), 9 landing screenshots incl. Vercel-live capture | ✅ Assets exist |
| 15 | zari-zardozi B2B growth system | `JobHunt-Profile\R-Company\zari-zardozi-b2b-growth-system\` | 10 modules: ICP, offer/pricing, portfolio structure, email/WhatsApp/IG DM scripts, follow-up system, **CRM workbook (.xlsx) with rendered previews**, landing copy, partnership proposal, 90-day plan | ✅ Complete system |
| 16 | LAQAB business system | `JobHunt-Profile\LAQAB\`, `laqab-master/` | Strategy, pricing tiers, order pipeline, lead export (25+ leads), 15 investor KPIs + tracker CLI, 90-day plan, lookbooks (PDF), golden-thread 60s film brief | ✅ Docs + assets |
| 17 | UpI expense tracker (Android) | `C:\Users\ADMIN\upi-expense-tracker\` | Kotlin/Gradle Android app, 262 jar artifacts, Python tooling, DB | ✅ Build artifacts |
| 18 | upi-expense-tracker UX research | `C:\Users\ADMIN\rural-india-expense-tracker-ux-report.md` | UX report for rural India segment | ✅ Doc |
| 19 | OpenMontage pipelines | `C:\Users\ADMIN\OpenMontage\` (git) | 13 video pipeline definitions (documentary-montage, clip-factory, cinematic, talking-head, avatar-spokesperson…), Remotion composer, 58 MP4 / 56 MP3 outputs | ✅ Framework + outputs |
| 20 | buzz-src | `C:\Users\ADMIN\buzz-src\` (git) | Block's Buzz monorepo: 1,192 Rust files, 1,264 TS, 1,171 Dart, 743 TSX | ◐ Vendored source, not authored |
| 21 | ComfyUI local pipeline | `C:\Users\ADMIN\ComfyUI\` (git) | 712 Python files, custom nodes, workflows | ◐ Installed + configured |
| 22 | kimi_k3_gen media batch | `C:\Users\ADMIN\kimi_k3_gen\` | 103 MP4, 84 PNG, 84 MP3 across 84 subfolders | ✅ Rendered |
| 23 | Agnes output library | `C:\Users\ADMIN\agnes-output\` | 25 MP4 + 94 PNG across 30 dated campaign folders + theme folders | ✅ Rendered |
| 24 | Ganesh-Zari shoot footage | `JobHunt-Profile\Ganesh-Zari\` | 62 raw iPhone MOV files (embroidery/zari) | ✅ Raw footage |
| 25 | 3D browser games | `C:\Users\ADMIN\` root | `racing-game-final.html` (589 KB), `racing-game-standalone.html` (605 KB), `game-3d.html`, `cricket-3d.html`, `chromaclash.html`, `blackhole-simulator.html`, `big-bang.html` | ✅ Playable single-file builds |
| 26 | COD KIDS game | `Desktop\cod-game\` | Self-contained canvas shooter + SPEC + smoke test | ✅ |
| 27 | delivero | `C:\Users\ADMIN\delivero\` | 60 HTML pages + Python generator | ◐ Prototype |
| 28 | mumbai-site / mumbai-map | `C:\Users\ADMIN\` | 11 HTML pages + GeoJSON map + PDF | ◐ Prototype |
| 29 | model-evals | `C:\Users\ADMIN\model-evals\` | Free-model landscape study (13 queries, ~30 sources), live test harness | ✅ Research artifact |
| 30 | Agent research corpus | `C:\Users\ADMIN\research\` | 18 papers: loop engineering, multi-agent orchestration, memory, self-improvement, routing, context management, desktop automation, scheduling, fleets, verification, cost/caching, Windows ops, security, task mgmt | ✅ Original synthesis |

---

## TIER 3 — Present but lower portfolio value

- **Forked/upstream repos** (not authored): owl (CAMEL), langchain, suna, smolagents, meetily, opencut, browser-use web-ui, hermes-webui, hermes-workspace, Inflect-Micro-v2 (HF), needle, deep-research, node-DeepResearch, ii-researcher, ollama-deep-researcher, dia (NARI), bark, grok-build, codex-router, hallm, oh-my-hermes, scrapybara-mcp.
- **Empty or near-empty stubs:** `Perplexica/` (0 files), `wiki/` (0), `media/` (0), `workspace/` (0), `JobHunt\Portfolio\Media\` (0), `artifacts/` (2 files — the R Company constitution referenced in JobHunt docs is **not there**), `Desktop\galactic-growth-labs\` (1 JSON — the "deployed 3D site" is **not on disk**), `kleverish\` (1 markdown).
- **Learning/experiment folders:** `19 & 7\dia`, `smolagents`, `owl`, `agent-zero`, `ii-researcher`, `ComfyUI`, `bark`, `tts-lab` — hands-on experiments with upstream code, useful as learning evidence, weak as portfolio.
- **Dead claims to drop:** "Galactic Growth Labs — deployed live", "artifacts/rcompany constitution", "C:\LAQAB IMAGES (~150 photos)" — all three paths are missing or empty on this machine.

---

## Deduplication notes
- `owl` exists in 3 locations (`~\owl`, `~\Documents\owl`, `~\jarvis\work\owl`) — same repo.
- `hermes-webui` exists in 3 locations — same repo (7,921 commits).
- `langchain` exists in 2 locations — same fork.
- `web-ui` exists in 2 locations — same fork.
- KALKI war room is duplicated inside `Kleverish\kleverish-master\final bykaif\`.
- R Company production OS exists in Desktop + Projects copies.
- `startup-machine` appears twice in scan output (same folder, case-insensitive listing).
