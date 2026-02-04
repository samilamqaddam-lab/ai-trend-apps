# 🤖 Task Decomposer — Desktop Automation Planner

**Date:** February 4, 2026  
**Trend:** UI-TARS by ByteDance — Local Desktop Automation Agent

## The Trend

ByteDance released [UI-TARS-Desktop](https://github.com/bytedance/UI-TARS-desktop), an open-source desktop automation agent that runs 100% locally. The viral tweet gained **2,700+ likes** and **380+ retweets**:

> "China just released a desktop automation agent that runs 100% locally. It can run any desktop app, open files, browse websites, and automate tasks without needing an internet connection. 100% Open-Source."
> — [@hasantoxr](https://twitter.com/hasantoxr)

Key highlights:
- Uses vision-language models for GUI understanding
- No cloud calls, no internet dependency
- Outperformed OpenAI on OSWorld benchmark (42.5% vs 36.4%)
- Completely open-source

## The App

**Task Decomposer** visualizes how AI agents like UI-TARS break down natural language instructions into concrete desktop automation steps.

### Features

- **Natural Language Input**: Describe what you want to automate in plain English
- **Step-by-Step Breakdown**: See the exact sequence of operations (click, type, drag, wait, find, check)
- **Visual Timeline**: Animated step visualization with action types
- **Risk Assessment**: Identifies potentially destructive operations
- **Time Estimation**: Rough estimate of execution time
- **Example Tasks**: Pre-built examples for common automation scenarios

### Supported Task Types

| Category | Example | Operations |
|----------|---------|------------|
| **File Organization** | "Organize Downloads by file type" | open, find, click, drag, check |
| **Screenshots** | "Screenshot all open tabs" | find, click, wait, drag, type |
| **App Management** | "Close all apps except Chrome" | find, check, click, wait |
| **Disk Cleanup** | "Delete files larger than 100MB" | open, find, check, wait, drag |
| **Backups** | "Backup Documents to external drive" | find, check, drag, verify |

## How It Works

1. User enters a task in natural language
2. App matches task against pattern templates
3. Generates appropriate sequence of desktop operations
4. Visualizes with timeline, risk level, and warnings
5. Shows which operations are "destructive" (could lose data)

## Technical Notes

- Pure HTML/CSS/JS — no dependencies
- Pattern matching for task classification
- Extensible template system for new task types
- Mobile-responsive design

## Try the Real Thing

This is a visualization/educational tool. For actual desktop automation:

- **UI-TARS Desktop**: [github.com/bytedance/UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop)
- **OpenClaw**: For personal AI automation with tool access
- **Midscene.js**: For web automation specifically

## Run Locally

```bash
# Just open in browser
open index.html

# Or serve locally
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

*Built as part of [AI Trend Apps](../index.html) — daily micro-apps inspired by what's trending in AI.*
