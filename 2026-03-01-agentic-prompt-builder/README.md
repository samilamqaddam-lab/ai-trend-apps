# ⚡ Agentic Prompt Builder

**Built:** March 1, 2026  
**Trend:** Vibe Coding → Agentic Engineering (viral Simon Willison guide)

## The Trend

On March 1, 2026, Simon Willison's "Agentic Engineering Patterns" guide went viral on X/Twitter. The core insight:

> "Writing code is cheap now. Delivering *good* code is still expensive."

Key viral tweet:
> `@simonw: I've published the first two chapters of a new guide to Agentic Engineering Patterns — coding practices to help get the best results out of agents like Claude Code and OpenAI Codex`

The shift from **Vibe Coding** (casual, informal prompts) to **Agentic Engineering** (structured prompts with TDD, validation criteria, constraints) was declared the meta-shift of 2026:

> `Feb 2025: "vibe coding"` → `Feb 2026: "agentic engineering"` — 12 months, one paradigm shift.

The most viral specific pattern: **Red/Green TDD** — simply telling your AI agent `"Use red/green TDD"` dramatically improves output quality by forcing it to write failing tests first before implementing.

## What I Built

An interactive **Agentic Prompt Builder** that helps developers transform vague "vibe prompts" into structured, production-quality agentic engineering prompts.

### Features

**🔨 Build Prompt Mode:**
- Input your coding task (or pick from examples)
- Select from 10 agentic engineering patterns:
  - 🔴🟢 Red/Green TDD
  - ✅ Explicit Validation criteria
  - 🔒 Security First
  - 🔥 Error Handling
  - 🎯 YAGNI Constraint
  - 📖 Self-Documenting Code
  - ⚡ Async/Parallel
  - 📊 Observability
  - 🧩 Atomic Commits
  - ⏱️ Completion Gate
- Real-time generated prompt with quality score
- Copy-to-clipboard

**⚡ Vibe vs Agentic Comparison Mode:**
- Side-by-side examples for Auth System, REST API, CLI Tool
- See exactly how vague vibe prompts become precise agentic prompts
- Explains *why* each pattern improves quality

## How to Use

1. Open `index.html` in any browser — no server needed
2. Enter your coding task in the text box
3. Select the patterns you want to apply
4. Copy the generated prompt and paste into Claude Code, Codex, or Cursor

## Pattern Philosophy

The key insight from the Agentic Engineering movement:

| Vibe Coding | Agentic Engineering |
|-------------|---------------------|
| "build me a login system" | Explicit validation criteria |
| Hope the tests pass | Red/Green TDD first |
| Trust the agent | Completion gates |
| Add everything | YAGNI constraints |
| Find bugs later | Security requirements upfront |

## Tech Stack

- Pure HTML/CSS/JavaScript (no dependencies)
- Works offline, no server required
- Single file app

## Run It

```bash
open index.html
# or
python3 -m http.server 8080
# then visit http://localhost:8080
```
