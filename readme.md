<h1 align="center">Muzamil Ali</h1>

<p align="center">Software Engineer — AI Systems & Full-Stack Development</p>

<p align="center">
  <a href="https://www.muzamilali.online/">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/muzamil-ali-b771aa356">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:me@muzamilali.online">Email</a> &nbsp;·&nbsp;
  <a href="https://dev.to/m-uzamiali">Dev.to</a>
</p>

---

## Profile

I’m a **Software Engineering Intern at Agento** and a third-year Computer Science student at **FAST-NUCES Karachi**. I build AI workflows, backend services, and full-stack applications, including an ERP used daily by a local water plant.

At Agento, I contribute to a workflow automation platform, working on:

- **Agent guardrails:** tool permissions, rules that constrain agent actions, and automatic stops and alerts for rule violations.
- **Backend reliability:** fixed OAuth state handling across load-balanced replicas by moving state to Redis.
- **Performance and monitoring:** multi-tenant caching and polling, TanStack Query caching, and service monitoring with Azure Application Insights.

I also teach C programming to beginners, focusing on problem-solving, pointers, and memory management.

**Current focus:** agent security, tool permissions, and workflow guardrails.

<p align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://streak-stats.demolab.com/?user=M-uzamilAli&hide_border=true&background=00000000&stroke=888888&ring=888888&fire=888888&currStreakNum=888888&sideNums=888888&currStreakLabel=888888&sideLabels=888888&dates=888888" alt="GitHub Streak" />
  </a>
</p>

---

## Tech Stack

| | |
|---|---|
| **Languages** | `Python` `Go` `C++` `Rust` `JavaScript` |
| **Frontend** | `React` `HTML5` `CSS3` `Tailwind CSS` |
| **Backend** | `FastAPI` |
| **Databases** | `PostgreSQL` `MongoDB` `Oracle` `Redis` `Supabase` |
| **Cloud & DevOps** | `Docker` `Azure` `Render` `Linux` `Git` |
| **Azure services** | `Container Apps` `Application Insights` `Blob Storage` |
| **AI & Automation** | `OpenAI API` `n8n` `Claude Code` `OpenAI Codex` |

---

## Selected Projects

### [Tulip ERP](https://github.com/M-uzamilAli/WATER_PLANT_FULL_STACK_APP) — Production System

Built solo for a reverse osmosis (RO) water plant to manage customers, pricing, deliveries, and billing. Uses **FastAPI, React/Vite, and PostgreSQL**, with stored procedures and atomic transactions to prevent partially saved dispatch batches. Reduced daily dispatch preparation from **approximately 20 minutes to under 5 minutes**. Used daily by the business.

[Read the case study →](https://www.muzamilali.online/tulip-erp.html)

<br>

### [SnapRelay](https://github.com/M-uzamilAli/SnapRelay) — Windows Utility

Capture screenshots from anywhere, let them **queue up in memory**, and send them all into an AI chat with one shortcut, instead of snip, switch tab, paste, switch back for every one. Built in **Rust** on the Windows APIs: it finds the focused text box through the **UI Automation** accessibility layer and confirms each paste through a delayed-rendering **clipboard promise**, so it works in ChatGPT, Claude, and WhatsApp with no app-specific code. Cut a 9-screenshot task from **17 tab switches to 1**; about 15 MB of RAM when idle, under 1 MB on disk. Open source (MIT).

[Download the latest release →](https://github.com/M-uzamilAli/SnapRelay/releases/latest)

<br>

### [Sticky Todo](https://github.com/M-uzamilAli/Sticky-Todo-Desktop-App) — Desktop App

An **always-on-top desktop widget** that brings personal notes and tasks from **ClickUp, GitHub, and Google Classroom** into one window. Built with **Electron, React, and Node.js**, with OAuth 2.0 integrations and login tokens encrypted locally. Shipped as an installable desktop app.

[Download the latest release →](https://github.com/M-uzamilAli/Sticky-Todo-Desktop-App/releases/latest)

<br>

### [AI Smart-Distiller](https://github.com/M-uzamilAli/AI-Smart-Distiller)

Team project; **I built the backend and API integrations**. Extracts structured summaries, tasks, and deadlines from documents using the **OpenAI API**, then routes results to Google Sheets, Discord, or email through **n8n** and webhooks.

<br>

### [Flappy Droniee](https://github.com/M-uzamilAli/Flappy-Droniee) — Motion-Controlled Game

A browser game where **your phone becomes the controller**: the PC shows the course, and tilting the phone sets the drone's height. The phone pairs over local Wi-Fi by **QR code** with a local **HTTPS** server (Node.js) and streams its **motion sensors**; the game predicts the tilt about **40 ms ahead** to hide input delay. The course speeds up and unlocks new obstacle patterns as the score rises.

---

<p align="center"><sub>me@muzamilali.online</sub></p>
