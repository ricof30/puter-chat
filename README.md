<!-- Banner / Title -->
<p align="center">
  <a href="#" target="_blank" rel="noopener">
    <img src="docs/banner.png" alt="Puter Chat Studio" width="960" />
  </a>
</p>

<h1 align="center">Puter Chat Studio — ChatGPT-style, Zero-Backend</h1>

<p align="center">
  A fast, elegant chat UI powered by <strong>Puter.js</strong>. No API keys. No backend. One HTML file.
  <br/>Deploy on Vercel in minutes. Includes a tiny postMessage API.
</p>

<p align="center">
  <a href="https://your-project.vercel.app">Live Demo</a>
  ·
  <a href="#-quickstart">Quickstart</a>
  ·
  <a href="#-deploy-to-vercel">Deploy</a>
  ·
  <a href="#-messaging-api-optional">Messaging API</a>
</p>

<p align="center">
  <a href="https://vercel.com/new/clone?repository-url=https://github.com/your/repo">
    <img alt="Deploy with Vercel" src="https://img.shields.io/badge/Deploy%20to-Vercel-000000?logo=vercel&logoColor=white">
  </a>
  <img alt="Made with Puter.js" src="https://img.shields.io/badge/Made%20with-Puter.js-14b8a6?logo=sparkfun&logoColor=white">
  <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-22c55e">
  <img alt="Zero Backend" src="https://img.shields.io/badge/Backend-None-0ea5e9">
</p>

---

## ✨ Features

- **ChatGPT-style layout** — assistant on the **left**, you on the **right**
- **Streaming responses** with a smooth **typing indicator**
- **Inline “Edit & Regenerate”** for user messages
- **Copy** any message (hover toolbar)
- **Theme switcher**: System / Dark / Light
- **Responsive** design (mobile-friendly)
- **Chat History** — switch sessions from the top bar (stored in `localStorage`)
- **Advanced options**: System prompt + optional Vision (image URL)
- **Model selector** + **Streaming On/Off**
- **Zero backend** — a single `index.html` using the Puter.js CDN

> 🛡️ Privacy: All conversations live in your browser (`localStorage`). No server is involved unless you add one.

---

## 🖼️ Screenshots

| Dark (Desktop) | Light (Mobile) |
| --- | --- |
| <img src="docs/screenshot-dark.png" width="600" /> | <img src="docs/screenshot-light-mobile.png" width="240" /> |

> Add your own images in `docs/` or remove this section.

---

## 🚀 Quickstart

1. **Clone** this repo.
2. **Open** `index.html` in a browser  
   _or_ run a tiny static server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
