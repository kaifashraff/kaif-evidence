# AI RESEARCH PORTFOLIO
**Nature of this work:** independent engineering research and synthesis. No peer review, no lab affiliation, no publications. Every item below has a document or a working system behind it.

---

## 1. The research corpus — `C:\Users\ADMIN\research\` (18 papers, ~230 KB)

| # | Paper | Core question | Size |
|---|---|---|---|
| 01 | Loop engineering | How do you design an agent loop that terminates correctly? | 12 KB |
| 02 | Multi-agent orchestration | When does splitting work across agents beat one agent? | 15 KB |
| 03 | Memory systems | What should an agent remember, and where? | 13 KB |
| 04 | Self-improvement | Can an agent safely modify its own procedures? | 17 KB |
| 05 | Model routing | How do you pick a model per task without guessing? | 21 KB |
| 06 | Context management | Budgeting context as a first-class resource | 10 KB |
| 07 | Desktop automation | Driving a GUI reliably from an agent | 10 KB |
| 08 | Hermes docs | Architecture notes on the Hermes agent runtime | 9 KB |
| 09 | Teacher–learning | Agent-as-teacher patterns | 22 KB |
| 10 | Autonomous scheduling | Cron, watchdogs, and unattended operation | 20 KB |
| 11 | Large agent fleets | Coordination at 100 workers | 14 KB |
| 12 | Verification | Why self-reports are not evidence | 9 KB |
| 13 | Cost & caching | Free-tier economics, caching, rate budgets | 10 KB |
| 14 | Windows ops | Session-0, scheduled tasks, service constraints | 9 KB |
| 15 | Security | Secrets, scope, and blast radius | 15 KB |
| 16 | Task management | Boards, acceptance commands, closure rules | 14 KB |
| 17 | Personal AI architecture | One operator, many agents | 11 KB |
| 19 | Persistent agents | Long-lived state across sessions | 10 KB |

**Status:** ✅ VERIFIED as documents. ◐ Synthesis of practice + reading, not original experiments with control groups.

---

## 2. Original engineering contribution — the verification thesis

**Claim:** the dominant failure mode of agentic business systems is not capability, it is *reporting*. An agent that can declare itself finished will.

**Evidence built for it** (`C:\Users\ADMIN\marketing-os\README.md`):
- Researched Polsia (a $250M "AI runs your company" product): its own live feed showed **29,132 active companies out of 484,592 created (6%)**; month-one churn ~50%; one logged audit showed **47 tasks, 41 marked complete, 21.3% actually worked, $0 income**.
- Built the counter-design: a task transitions to `Done` only through `gate::transition`, which requires (1) at least one claim, (2) evidence for every claim, (3) latest evidence `Verified`, (4) `Unverifiable` also blocks, (5) stale evidence does not count.
- Seven deterministic check types, no model opinion, no `--force`.

**This is the strongest research artifact in the profile.** It is a falsifiable position, an implemented system, and a documented failure it responds to.

---

## 3. Evaluation design — `perf-marketing-eval\`

An end-to-end 12-phase marketing evaluation where the agent does **not** score itself; an independent judge + human grade it.

- Self-scored version was **rejected as slop** (92% self-score).
- Independent verdict: completeness 55/100, quality/veracity 42/100, executability 35/100.
- Published worst problem: *"the plan optimizes a funnel that doesn't exist (no trial/activation event), using benchmarks it couldn't prove, and originally graded itself 92%."*

**Why it counts as research:** it is an experiment about *evaluation*, with a negative result reported honestly. Most portfolios have no negative results at all.

---

## 4. Model landscape study — `model-evals\EVAL-2026-08-01.md`

- Method: 13 queries, ~30 cross-checked sources (DuckDuckGo HTML via reader proxy after direct scraping was bot-blocked).
- Output: model-by-model free-tier status, provider table, cost analysis, plus a live test harness (`live_test.py`) and a second run (`LIVE-TEST-2026-08-01.md`).
- Also operationalised: `config.yaml` fallback chain with `hermes fallback check --live`, and a documented known-dead provider list.

**Status:** ✅ VERIFIED document + working routing config. Point-in-time; free tiers rot.

---

## 5. Systems research embedded in the fleet

| Area | What was actually solved | Artifact |
|---|---|---|
| Session-0 wall | Gateway launched from a non-interactive session kills computer-use; solved via scheduled task with interactive logon | Memory + scheduled tasks |
| Provider starvation | A broken first fallback entry 400s and starves the whole chain — diagnosed and fixed | `config.yaml` fallback chain |
| Subagent truncation | Iteration-budget truncation returns "completed" with partial work; solved with disk-authoritative verification | delegation protocol notes |
| Rate-bucket integrity | Reserve-before-send across 75 rpm aggregate + per-provider caps + FREEZE switch | `swarm/usage.py`, `swarm/usage.md` |
| Media pipeline reliability | Circuit-breaker on MCP; direct client fallback when the MCP server dies | `tools/agnes/agnes_client.py` |

---

## 6. What this research is NOT

- Not peer-reviewed. Not published. Not cited.
- No controlled experiments with baselines.
- No novel model architecture, no training runs with reported metrics.
- Claims about industry products (Polsia etc.) are sourced from public reporting, not independent audit.

**Honest framing for a CV:** *"Independent research and engineering notes on agent reliability, routing, and verification — 18 papers, one implemented verification system, one published negative-result evaluation."* Do not call it "AI research" without the qualifier.
