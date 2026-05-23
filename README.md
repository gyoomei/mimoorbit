<div align="center">

# 🚀 MimoOrbit

### Submit to Xiaomi MiMo 100T Grant · Free Chatbox · Agent Setup Guide

Complete guide to apply for the Xiaomi MiMo Orbit 100 trillion token grant program. Step-by-step submission flow, free MiMo V2.5 chatbox you can try without any API key, and copy-paste agent configuration for Hermes Agent, OpenClaw, Claude Code, Python SDK, and curl.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-22c55e?style=for-the-badge&logo=githubpages&logoColor=white)](https://gyoomei.github.io/mimoorbit/)
[![Apply Now](https://img.shields.io/badge/⚡_Apply_100T_Grant-ff6b35?style=for-the-badge)](https://100t.xiaomimimo.com/)
[![License](https://img.shields.io/badge/License-MIT-3b82f6?style=for-the-badge)](LICENSE)

[![Single HTML](https://img.shields.io/badge/Single_File-No_Dependencies-c084fc?style=flat-square)](#)
[![No API Key](https://img.shields.io/badge/Chatbox-No_API_Key-22c55e?style=flat-square)](#)
[![Bilingual](https://img.shields.io/badge/EN_/_ID-bilingual-fbbf24?style=flat-square)](#)

</div>

---

## 📖 The Problem

The Xiaomi MiMo Orbit 100 trillion token creator grant program is live, but the application flow is split across the landing page (form), the API platform (registration), and the docs (agent integration). New builders waste hours stitching together (1) how to apply, (2) what they actually get, and (3) how to plug the grant into their existing tools.

**Three friction points compound:**

The application page lists steps but no concrete examples. The API docs assume you already have a key. The agent integration docs are hidden three clicks deep into platform.xiaomimimo.com. By the time a builder figures out the chain, they've already missed the deadline or filled the form too vaguely.

## ✨ The Solution

**MimoOrbit closes the gap.** Single zero-dependency HTML page that walks you through the full application-to-agent pipeline: visual countdown to the grant deadline, four-step submission flow, free MiMo chatbox you can test without any signup, and copy-paste configuration blocks for the five most common agents (Hermes, OpenClaw, Claude Code, Python SDK, curl).

The chatbox uses the public Pollinations.ai gateway as a free preview so anyone can test MiMo's reasoning style before submitting. Once you receive your grant email, the same patterns work with the official `https://api.xiaomimimo.com/v1` endpoint and your `sk-xxxxx` key.

## ✨ Core Features

### 📝 Submission Flow (4-step visual)

Application → 3-day review → Approval email → Register & claim. Each step has a concrete time estimate and the exact action you need to take.

### 💬 Free MiMo Chatbox (no API key)

Embedded chatbox powered by Pollinations.ai's public OpenAI-compatible gateway. Bilingual system prompt, 4 suggestion chips, conversation history (last 8 turns), markdown rendering, graceful fallback when rate-limited.

### 🛠️ Agent Setup (5 tabs, copy-paste)

| Tab | What it covers |
|-----|----------------|
| **Hermes Agent** | Install + predefined provider + custom provider switch + verify |
| **OpenClaw** | Install + interactive wizard + manual `~/.openclaw/openclaw.json` (Token Plan) |
| **Claude Code** | Anthropic-compatible env vars + persist to `~/.zshrc` |
| **Python SDK** | OpenAI drop-in with proper system prompt |
| **Curl** | 5-second key verification |

### 🤖 Model Reference

Comparison cards for `mimo-v2.5-pro` (1M context), `mimo-v2.5` (256K, multimodal), `mimo-v2.5-tts` (voice cloning).

### ❓ FAQ (6 most-common)

Distilled from the official 100t.xiaomimimo.com FAQ, focused on what trips builders: deadline, what you actually receive, who can apply, what makes a strong submission, why the embedded chatbox uses Pollinations not MiMo directly, and the email/Xiaomi-ID mismatch (the #1 grant-delivery failure cause).

### ⏱️ Live Countdown

Real-time countdown to May 28, 2026 00:00 Beijing Time (the grant deadline) so applicants know exactly how long they have.

### 🌍 Bilingual EN/ID

Full toggle — every UI string, FAQ answer, and chatbox system prompt switches between English and Bahasa Indonesia.

### 🌓 Dark / Light Theme

WCAG-AA contrast ratios, CSS Custom Properties, `prefers-color-scheme` aware, mobile-first responsive.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla HTML + CSS + JS (~50 KB total) |
| Chatbox | [Pollinations.ai](https://pollinations.ai) (free, no key, OpenAI-compatible) |
| Theming | CSS Custom Properties + `data-theme` |
| i18n | `data-i18n` + JS object, EN/ID |
| Hosting | [GitHub Pages](https://pages.github.com) |

## 🚀 Quick Start

```bash
git clone https://github.com/gyoomei/mimoorbit.git
cd mimoorbit
# Serve locally
python3 -m http.server 8080
# Open http://localhost:8080
```

Or just open `index.html` directly in a browser.

## 📜 License

MIT. Built for the [Xiaomi MiMo Orbit 100T Creator Program](https://100t.xiaomimimo.com/).
