# 🔐 Vibe Code Scanner

**Security checker for AI-generated code — because vibe coding forgot about security.**

## The Trend

Vibe coding turned 1 year old on February 2nd, 2026! Andrej Karpathy coined the term, and it's been a wild ride. But as @ejae_dev pointed out:

> "vibe coding turned 1 year old yesterday. karpathy's tweet that started it all... what didn't change: • security is still an afterthought • moltbook proved it (500k fake users, zero rate limiting) • most vibe coded apps have the same vulnerabilities. the next year of vibe coding needs to be about vibes + validation. ship fast, but don't ship auth tokens in the frontend."

## What This App Does

Paste any code and instantly scan for common security issues found in vibe-coded apps:

### Critical Issues Detected
- 🔑 **Exposed API Keys** - Hardcoded secrets that should be in env vars
- 🔐 **Hardcoded Passwords** - Never commit credentials
- 🗝️ **Private Keys** - RSA/SSH keys in source code
- ☁️ **AWS Credentials** - IAM keys exposed in code
- 💉 **SQL Injection** - String concatenation in queries
- ⚠️ **eval() Usage** - Arbitrary code execution risks
- 🐚 **Shell Execution** - Command injection vulnerabilities

### Warnings
- 📝 **innerHTML XSS** - Unsafe DOM manipulation
- 🌐 **CORS Wildcard** - Overly permissive CORS settings
- 🔓 **JWT in localStorage** - Token storage vulnerable to XSS
- 🚫 **Disabled HTTPS** - SSL verification turned off
- 📡 **No Rate Limiting** - API calls without throttling

### Info
- 🖥️ **Hardcoded localhost** - Development URLs in code
- 📋 **console.log** - Debug logs that might leak data

## How to Use

1. Open `index.html` in a browser
2. Paste your code (JavaScript, Python, or any language)
3. Click "Scan for Issues"
4. Fix the problems before shipping!

## Try the Examples

The app includes 4 example code snippets:
- **Exposed API Key** - Classic vibe coding mistake
- **SQL Injection** - Query building gone wrong
- **Frontend Auth** - Multiple auth mistakes in one
- **Clean Code** - How it should be done

## Tech Stack

- Pure HTML/CSS/JS (no dependencies)
- Client-side regex scanning
- GitHub-dark themed UI

## Limitations

This is a basic static analyzer. It catches common patterns but:
- Won't find all vulnerabilities
- May have false positives
- Doesn't understand code context deeply
- No AST parsing (regex-based)

For production security, use proper tools like:
- GitHub Advanced Security
- Snyk
- SonarQube
- CodeQL

## Screenshots

The app features a split-panel design with code input on the left and real-time security findings on the right, complete with severity indicators and line numbers.

---

**Built on:** February 3, 2026
**Inspired by:** Vibe coding's 1st anniversary discussions on X
**Part of:** [AI Trend Apps](../index.html)
