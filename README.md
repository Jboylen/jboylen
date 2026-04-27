# Hi, I'm J 👋

**If it's broken, I fix it. If it doesn't exist, I build it. | AI, TS/JS, Python, Embedded HW**

## 🛠 About Me
I'm a tinkerer, elite troubleshooter, and full-stack developer. With over 20 years of experience in troubleshooting complex issues (currently specializing in Ericsson/Nokia RAN), I've built a career on solving complex hardware issues, developing technical standards, and training teams. 

Recently, I've merged my engineering mindset with modern software development. I specialize in **AI integrations, API orchestration, and bridging the gap between digital tools and physical hardware**. 

## 💻 Tech Stack
- **Languages:** Python, TypeScript, JavaScript, HTML/CSS, C/Assembly
- **Frontend:** React, Tailwind CSS, shadcn/ui, Vite, Zustand
- **Backend/Systems:** FastAPI, Node.js, SQLAlchemy, REST APIs, Hybrid Async/Sync execution
- **Hardware & Embedded:** Microcontroller programming, POS/Receipt Printers (ESC/POS protocol)
- **Integrations:** Discord API, Shopify API, OAuth 2.0, Docker, SQLite/PostgreSQL

---

## 🚀 Featured Architecture & Projects
*(Repositories are kept private, but here is a look under the hood at my systems design!)*

### 1. Sierra Chart Alert Monitor
**A high-performance, low-latency pipeline bridging local trading instances with remote Discord teams.**
* **Decoupled Systems Architecture:** Built as a standalone service to isolate monitoring logic from the trading platform, preventing UI lockups and ensuring zero-loss alert processing.
* **Hybrid Concurrency:** Engineered a custom pipeline that seamlessly orchestrates asynchronous event loops (`discord.py`, `Textual` TUI) alongside synchronous, thread-safe file I/O (`watchdog`) without blocking the main thread.
* **Custom TUI Dashboard:** Built a fully reactive, live terminal dashboard using `Textual` that surfaces real-time system health, latency sparklines, and active bot logs.
* **Smart Parsing & Rate Limiting:** Includes dynamic screenshot correlation (matching local `.png` creation times to log files) and per-symbol rate throttling to prevent Discord API limits.

<img width="1338" height="914" alt="alertTUI" src="https://github.com/user-attachments/assets/905519e5-fd02-4e09-a581-01082e285832" />

### 2. "Day Printer" Task Ecosystem
**A full-stack task management platform that bridges digital organization with physical hardware.**
* **The Concept:** A modular task manager that automatically formats, schedules, and prints your daily workload directly to a thermal receipt printer (Epson TM-M30).
* **Full-Stack Orchestration:** Built with a modern **React/TypeScript** frontend and a **Python/FastAPI** backend using a modular service pattern.
* **Hardware Bridge:** Engineered a custom printing module that communicates over Network/USB/Serial. It parses task data, formats it using the native ESC/POS protocol, and includes a custom algorithm to generate accurate ASCII print-previews in the web UI.
* **Discord Integration:** Built a custom Discord bot that hooks into the backend REST API, allowing users to remotely create tasks, manage projects, and trigger physical prints via slash commands.

<img width="1215" height="733" alt="dayprinter" src="https://github.com/user-attachments/assets/72546444-9016-4b85-ac0b-7f9707ba1e5f" />

---

## 🌱 Currently Working On
- **AI & RAG:** Building Retrieval-Augmented Generation (RAG) knowledge bases to automate onboarding flows and support tickets.

📫 **Let's connect:** I'm always open to chatting about hardware hacks, AI tooling, and innovative trading dev!
