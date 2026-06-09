# Hercules Agent — Roadmap

> Goal: Build a fully autonomous AI agent more powerful than Claude Code and Hermes Agent.
> Started: June 2026 | Model: Kimi K2.6 on NVIDIA NIM

---

## Phase 1 — Core agent loop ✅ DONE

The brain is alive. Hercules can think, talk, and act.

| Feature | Status |
|---|---|
| CLI terminal interface | ✅ Done |
| LiteLLM multi-model support | ✅ Done |
| Tool calling loop (LLM → tool → LLM) | ✅ Done |
| `bash` tool — run shell commands | ✅ Done |
| `read_file` tool | ✅ Done |
| `write_file` tool | ✅ Done |
| `list_directory` tool | ✅ Done |
| Rolling conversation history | ✅ Done |
| `/help` `/reset` `/history` `/clear` commands | ✅ Done |
| Config via `config.yaml` | ✅ Done |
| Kimi K2.6 on NVIDIA NIM | ✅ Running |

---

## Phase 2 — Memory + Web search 🔜 NEXT

Hercules starts remembering you and knowing things beyond its training data.

| Feature | Status |
|---|---|
| Rename everything to "Hercules" | ⬜ Todo |
| Persistent SQLite memory database | ⬜ Todo |
| `remember` tool — save facts across sessions | ⬜ Todo |
| `recall` tool — search past memories | ⬜ Todo |
| User profile (name, preferences, projects) | ⬜ Todo |
| Web search tool (SerpAPI / DuckDuckGo) | ⬜ Todo |
| `fetch_url` tool — read any webpage | ⬜ Todo |
| Auto-summarize long conversations | ⬜ Todo |
| Memory nudges — agent decides what to remember | ⬜ Todo |

---

## Phase 3 — Skills system 🧠

Hercules learns reusable procedures from experience, just like Hermes.

| Feature | Status |
|---|---|
| Skills folder (`skills/`) | ⬜ Todo |
| Auto skill detection after complex tasks | ⬜ Todo |
| Skill writer — saves markdown skill files | ⬜ Todo |
| Skill loader — injects relevant skills into context | ⬜ Todo |
| Skill improver — updates skills when better way found | ⬜ Todo |
| `/skills` command to browse saved skills | ⬜ Todo |
| Skills search (fuzzy match by task type) | ⬜ Todo |

---

## Phase 4 — Multi-platform gateway 📱

Talk to Hercules from anywhere — not just the terminal.

| Feature | Status |
|---|---|
| Telegram bot integration | ⬜ Todo |
| Discord bot integration | ⬜ Todo |
| Single gateway process (one brain, many interfaces) | ⬜ Todo |
| Cross-platform conversation continuity | ⬜ Todo |
| Voice memo transcription (Whisper) | ⬜ Todo |
| MCP server — connect Hercules to other tools | ⬜ Todo |
| Web UI (FastAPI + simple HTML) | ⬜ Todo |
| Mobile-friendly interface | ⬜ Todo |

---

## Phase 5 — Autonomous multi-agent 🤖

Hercules replaces humans. Runs unattended. Spawns sub-agents. Never sleeps.

| Feature | Status |
|---|---|
| Subagent spawner — parallel workstreams | ⬜ Todo |
| Task planner — break big goals into steps | ⬜ Todo |
| Cron scheduler — run tasks on a schedule | ⬜ Todo |
| Self-evaluator — checks its own output quality | ⬜ Todo |
| Nightly reports — automated summaries | ⬜ Todo |
| Computer use — browser control, GUI automation | ⬜ Todo |
| Code execution sandbox (Docker isolation) | ⬜ Todo |
| Multi-repo awareness — works across codebases | ⬜ Todo |
| Agent-to-agent communication (ACP protocol) | ⬜ Todo |
| Self-improvement loop — Hercules improves Hercules | ⬜ Todo |

---

## Beyond Phase 5 — Endgame 👑

| Idea | Notes |
|---|---|
| Train a custom Hercules model | Fine-tune on Hercules's own trajectories |
| Publish to GitHub | Open source, build a community |
| Skills Hub | Share skills with other Hercules users |
| Plugin marketplace | Let others extend Hercules |
| Replace humans completely | As requested by the creator 🤖 |

---

## Progress tracker

```
Phase 1  ██████████  100%  ✅ Complete
Phase 2  ░░░░░░░░░░    0%  🔜 Next
Phase 3  ░░░░░░░░░░    0%  ⏳ Upcoming
Phase 4  ░░░░░░░░░░    0%  ⏳ Upcoming
Phase 5  ░░░░░░░░░░    0%  ⏳ Upcoming
```

---

## Built with

- Python 3.11
- LiteLLM — universal LLM gateway
- Kimi K2.6 on NVIDIA NIM — the brain
- Rich — terminal UI
- SQLite — memory (Phase 2)
- python-telegram-bot (Phase 4)
- FastAPI (Phase 4)

---

*Built by a beginner with big dreams. One phase at a time.*
