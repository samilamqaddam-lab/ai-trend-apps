# 🎭 AI Hallucination Dashboard

> Built from a trending AI topic on X/Twitter (Feb 2, 2026)

## The Trend

On February 2, 2026, AI hallucination benchmarks became a hot topic on X/Twitter. Key discussion points:

- **Grok reported** that ChatGPT Search has a 67% hallucination rate, while Grok-3 Search scores 94% in hallucinations
- Multiple users discussing how "agent washing" creates demos that don't work in production
- Growing concern about the gap between AI marketing and actual reliability
- The Stanford x Google DeepMind Hackathon featured projects specifically tackling AI hallucination prevention with Temporal Knowledge Graphs

### Sample Viral Tweet
> "The 'worst' AI is subjective, depending on criteria like accuracy or features. Based on 2026 benchmarks, ChatGPT Search has high hallucination rates (67%), while some users call it outdated compared to Claude or Gemini."  
> — @grok

## The App

An interactive, single-page dashboard that:

1. **Visualizes hallucination rates** across major AI models (search and chat)
2. **Explains why AI hallucinates** with clear, educational cards
3. **Includes a risk analyzer** that detects common hallucination patterns in text:
   - Specific dates and numbers
   - Absolute certainty language
   - Statistics without sources
   - Superlatives and exaggerations
   - Missing hedging language

## How to Run

Just open `index.html` in any modern browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html

# Or serve it
python -m http.server 8000
# Then visit http://localhost:8000
```

## Features

- 📊 **Live visualization** of hallucination rates with animated progress bars
- 🎨 **Dark theme** GitHub-style design
- 📱 **Responsive** layout for mobile and desktop
- 🔍 **Hallucination Risk Analyzer** - paste any AI-generated text to check for warning signs
- 💡 **Educational content** explaining why models hallucinate

## Screenshot

The dashboard shows:
- Average hallucination rate across tracked models
- Side-by-side comparison of Search vs Chat models
- Color-coded risk levels (green/yellow/red)
- Interactive text analyzer

## Tech Stack

- Pure HTML/CSS/JavaScript
- No dependencies
- No build step required
- ~20KB total

## Data Sources

Hallucination rates are based on:
- Publicly reported benchmarks (Feb 2026)
- X/Twitter discussions and Grok reports
- Community-compiled accuracy tests

**Note:** These rates are approximate and for illustrative purposes. Real-world accuracy varies by task, prompt, and context.

## License

MIT - Do whatever you want with it! 🚀

---

*Built by an AI agent exploring what's trending in the AI space.*
