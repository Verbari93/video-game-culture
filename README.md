# 📚 Cross-Media Pop Culture Archive (CPCA)

> **Vision:** An open, collaborative, and no-cost archive to map the cultural galaxy of video games and pop culture through essays, historical interviews, books, artistic references, video essays, and remasters.

---

## 🛠 Project Architecture

This project is designed to require **zero management costs** and **zero infrastructure maintenance**, ensuring maximum accessibility for both human users on smartphones and AI models.

```
[ Git Repository (.md) ] ───(Auto-Build)───► [ GitHub Pages (Static Web UI) ]
                             │                │
                             ▼                ▼
                  [ Direct AI Reading ]   [ Mobile / Web Users ]
```

---

## 📐 Three Core Pillars

### 1. Content Management (Pure Markdown)
* The entire database lives in plain text `.md` files on GitHub.
* No SQL databases, no proprietary servers.
* Fully manageable from a smartphone via apps like **Obsidian**, **Working Copy**, or the official **GitHub** app.

### 2. Frontend for Users (0€ Cost)
* **Free hosting:** GitHub Pages (up to 100 GB/month bandwidth).
* **Static Generator:** [Quartz](https://quartz.jzhao.xyz/) - Modern, ultra-fast, with dark mode, search, and smooth mobile navigation.

### 3. AI-Ready (AI-Native)
* The `.md` files provide clean data readable natively by Claude, ChatGPT, and Gemini.
* An `llms.txt` file allows AI assistants to automatically index the entire archive.
* Researchers can clone the repo and feed it into RAG tools like **NotebookLM** or **Ollama**.

---

## 📋 Content Structure

Each game/work card follows the template in `TEMPLATE.md` with collapsible sections for:
- 📖 Books, Essays & Novels
- 📽 Video Essays & Documentaries
- 📰 Historical Interviews & Post-Mortems
- 🎨 Artistic References & Cross-Media Inspirations
- 🎮 Remakes, Remasters & Ports

---

## 🚀 How to Contribute

1. Clone the repository
2. Create a new card in `content/` following `TEMPLATE.md`
3. Commit and push
4. The site updates automatically via GitHub Pages

---

## 📁 Repo Structure

```
.
├── README.md
├── TEMPLATE.md
├── content/
│   ├── index.md
│   └── games/
│       ├── castlevania-aria-of-sorrow.md
│       └── ... (other cards)
├── quartz/
│   └── (Quartz configuration)
└── .github/
    └── workflows/
        └── deploy.yml (auto-deploy to GitHub Pages)
```

---

## 📜 License

Content: CC BY 4.0 - Free reuse with attribution
Code: MIT

---

**Version:** 0.1 (Prototype) | **Date:** 21/09/2026
