## About Me

I'm a **Generative AI Developer** at IBM building production-grade multi-agent systems, RAG pipelines, and LLM guardrails on cloud infrastructure. My work spans agentic orchestration (LangChain, LangGraph, A2A), backend services (Python, FastAPI), and observability tooling — all shipped on OpenShift with Jenkins CI/CD.

I graduated in Computer Science Engineering from Sahrdaya College of Engineering & Technology (CGPA: 7.6) and have been hands-on with AI-first products since my internship days. Beyond the day job, I've won hackathons (BeachHack 2025 🥇, IBM GenAI Conclave 2024 🥈, Global Game Jam Kerala 2026 🥈), written technical blogs on [Dev.to](https://dev.to/joeljaison394), and enjoy sketching as a creative outlet.

## Experience

<div class="timeline" markdown="1">

<div class="exp-item" markdown="1">

### Software Developer — IBM
<span class="meta">Jul 2025 – Present · Kochi, India</span>

- Modernized observability for **Watsonx Orchestrate** by leading the migration of distributed tracing from Jaeger to **Langfuse** with external ClickHouse collectors, and built the APIs that expose those traces for real-time agent governance and monitoring.
- Eliminated manual regression-testing effort by automating **200+ test cases** with a **Pytest / Playwright** framework wired into Jenkins, GitHub, and TestRail; watsonx-driven failure analysis auto-files and validates defects in under 30 seconds.
- Hardened the control plane by building content, output-length, secret-detection, and SQL-sanitization **guardrails** that plug into every agent type (LangGraph, A2A) and tool type (Python, Langflow, OpenAPI, MCP) — shipped as **FastAPI** services on OpenShift.
- Extended the **RAG pipeline** with Milvus-based ingestion connectors for external data sources, widening the range of data agents can reliably retrieve from.

</div>

<div class="exp-item" markdown="1">

### Software Developer Intern — IBM
<span class="meta">Jan 2025 – Jun 2025 · Kochi, India</span>

- Built the data-fetching pipeline connecting **Db2 to watsonx.data**, giving the platform a direct, reliable path to pull enterprise data for downstream UI and APIs.
- Shipped new **watsonx.data UI** features end-to-end using **React** and IBM's **Carbon Design System**, from spec to production release.
- Owned the frontend migration from **React 17 → React 19**, adopting the new ref-as-prop pattern and retiring deprecated APIs.

</div>

<div class="exp-item" markdown="1">

### Frontend Web Developer — Flora Extracts
<span class="meta">Feb 2024 – Jun 2024</span>

- Designed and implemented responsive web interfaces using **React**, **Tailwind CSS**, and **Framer Motion**.
- Improved user experience through interactive and visually appealing frontend components.

</div>

<div class="exp-item" markdown="1">

### Alexa Skill Developer Intern — Inclusys Org Foundation
<span class="meta">May 2023 – Jun 2023 · Remote</span>

- Built Alexa Skills for elderly memory exercises and conversational prompts, raising engagement by **30%**.
- Deployed voice services on **AWS Lambda**, maintaining **99% uptime**.

</div>

<div class="exp-item" markdown="1">

### Tech Lead — GDSC Sahrdaya
<span class="meta">Aug 2023 – Dec 2024</span>

- Managed technical aspects of the club's activities, events, and workshop delivery.

</div>

</div>

## Featured Projects

<p class="section-lead">A selection of the products and systems I've designed and shipped end-to-end.</p>

<div class="project-grid" markdown="1">

<div class="project-card" markdown="1">

### Pakt

Multi-agent negotiation app where each user gets a personal AI agent that knows their tastes, schedule, and budget — when a group wants to plan a movie night or dinner, the agents negotiate with each other in a shared chat, searching real venues and converging on a single confirmed plan, with humans able to take over at any point. Built for the H0: Hack the Zero Stack hackathon (AWS DynamoDB + Vercel + Next.js).

<div class="tags">
<span class="tag">Next.js 16</span>
<span class="tag">React 19</span>
<span class="tag">TypeScript</span>
<span class="tag">LangGraph</span>
<span class="tag">GPT-4o</span>
<span class="tag">AWS Lambda</span>
<span class="tag">DynamoDB</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/JoelJaison394/Pakt) · [Live](https://pakts.tech)
</div>

</div>

<div class="project-card" markdown="1">

### Roleify — AI Job Hunter <span class="badge">In build</span>

Job-search assistant delivered entirely through a Telegram bot: extracts ranked keywords from a resume with a locally-hosted LLM, matches them against a shared multi-source job pool, scores every match with GPT-4o mini, and writes tailored cover letters — with a free tier and a pay-per-run tier backed by Razorpay.

<div class="tags">
<span class="tag">n8n</span>
<span class="tag">PostgreSQL</span>
<span class="tag">Ollama · Llama 3.1</span>
<span class="tag">GPT-4o mini</span>
<span class="tag">Telegram Bot API</span>
<span class="tag">Razorpay</span>
</div>

<div class="links" markdown="1">
[Live](https://roleify.joeljaison.com)
</div>

</div>

<div class="project-card" markdown="1">

### LawLens AI — Compliance Assistant <span class="badge">🥇 BeachHack 2025</span>

AI-powered compliance assistant using RAG with Mistral-7B and ChromaDB retrieval, achieving 96% rule-match accuracy. Won 1st Prize at BeachHack 2025.

<div class="tags">
<span class="tag">RAG</span>
<span class="tag">Mistral-7B</span>
<span class="tag">ChromaDB</span>
<span class="tag">LangChain</span>
<span class="tag">Python</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/LawLens)
</div>

</div>

<div class="project-card" markdown="1">

### KeyPilot — Semantic API Gateway

GenAI API gateway for semantic routing, caching, and vector retrieval, built on an event-driven architecture with Redis Streams.

<div class="tags">
<span class="tag">Node.js</span>
<span class="tag">RedisVL</span>
<span class="tag">Redis Streams</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/KeyPilot)
</div>

</div>

<div class="project-card" markdown="1">

### Livie — AI Storytelling Assistant <span class="badge">🥈 IBM GenAI Conclave 2024</span>

Elderly wellness companion powered by a fine-tuned Mistral-7B, deployed as microservices on AWS. 1st Runner-Up at IBM GenAI Conclave 2024.

<div class="tags">
<span class="tag">Watsonx</span>
<span class="tag">Mistral-7B</span>
<span class="tag">Spring Boot</span>
<span class="tag">AWS</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/Livie)
</div>

</div>

<div class="project-card" markdown="1">

### Amenly — Daily Prayer & Bible App

Mobile app helping Christians build a daily prayer and Bible-reading habit: a 100+ prayer library with audio narration and ambient soundscapes, a full Bible reader with verse saving, devotional stories, and streak-based habit tracking — free to use, with an optional Pro tier.

<div class="tags">
<span class="tag">Mobile App</span>
<span class="tag">Android</span>
<span class="tag">iOS · coming soon</span>
</div>

<div class="links" markdown="1">
[Website](https://amenly.vercel.app)
</div>

</div>

</div>

### Other Projects

<div class="project-grid compact" markdown="1">

<div class="project-card" markdown="1">

### GeeksforGeeks Profile API

API to fetch GFG user profile details — name, rank, scores, institution, problems solved — and generate downloadable DSA cards.

<div class="tags">
<span class="tag">Node.js</span>
<span class="tag">Express.js</span>
<span class="tag">Cheerio</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/GeeksforGeeks-Profile-API)
</div>

</div>

<div class="project-card" markdown="1">

### Downloads Organizer

Rust application that automatically organizes downloads by moving files into appropriate directories based on their extensions.

<div class="tags">
<span class="tag">Rust</span>
<span class="tag">Crossbeam</span>
<span class="tag">Notify</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/Downloads-Organizer)
</div>

</div>

<div class="project-card" markdown="1">

### StarBoard

Task management application built with Rust and Tauri — organize tasks into pages, track completion status, and manage workload efficiently.

<div class="tags">
<span class="tag">Rust</span>
<span class="tag">Tauri</span>
<span class="tag">React.js</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/JoelJaison394/StarBoard)
</div>

</div>

<div class="project-card" markdown="1">

### AI Matchmaker

Retro-inspired chat game where users try to "woo" an AI with creativity, humor, and charm. Built for the Useless Hackathon by ThinkerHub.

<div class="tags">
<span class="tag">React.js</span>
<span class="tag">OpenAI API</span>
</div>

<div class="links" markdown="1">
[GitHub](https://github.com/Joeljaison391/Propose-Your-AI) · [Live](https://propose-your-ai.vercel.app/)
</div>

</div>

<div class="project-card" markdown="1">

### KeyMomentum 🚀

Typing speed checker designed to enhance typing skills with engaging challenges.

<div class="tags">
<span class="tag">React.js</span>
<span class="tag">TypeScript</span>
<span class="tag">Tailwind CSS</span>
</div>

<div class="links" markdown="1">
[Live](https://keymomentum.vercel.app/)
</div>

</div>

</div>

## Skills

<div class="skills-grid" markdown="1">

<div class="skill-group" markdown="1">
#### Generative AI & Agentic Systems
<div class="skill-tags">
<span class="pill">LangChain</span><span class="pill">LangGraph</span><span class="pill">RAG Pipelines</span><span class="pill">MCP</span><span class="pill">A2A Protocol</span><span class="pill">Langflow</span><span class="pill">LLM Guardrails</span><span class="pill">LLM Benchmarking</span><span class="pill">Milvus</span><span class="pill">ChromaDB</span><span class="pill">Watsonx.ai</span><span class="pill">Watsonx Orchestrate</span><span class="pill">Watsonx.data</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Languages
<div class="skill-tags">
<span class="pill">Python</span><span class="pill">Java</span><span class="pill">TypeScript</span><span class="pill">Rust</span><span class="pill">SQL</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Backend & APIs
<div class="skill-tags">
<span class="pill">FastAPI</span><span class="pill">Node.js</span><span class="pill">Spring Boot</span><span class="pill">PostgreSQL</span><span class="pill">MongoDB</span><span class="pill">Redis</span><span class="pill">Db2</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Frontend
<div class="skill-tags">
<span class="pill">React.js</span><span class="pill">Next.js</span><span class="pill">Tailwind CSS</span><span class="pill">Carbon Design System</span><span class="pill">Material UI</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Cloud & DevOps
<div class="skill-tags">
<span class="pill">AWS (Lambda, S3)</span><span class="pill">Azure</span><span class="pill">OpenShift (OCP)</span><span class="pill">Docker</span><span class="pill">Kubernetes</span><span class="pill">GitHub Actions</span><span class="pill">Jenkins</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Testing & Observability
<div class="skill-tags">
<span class="pill">Pytest</span><span class="pill">Playwright</span><span class="pill">TestRail</span><span class="pill">Jaeger</span><span class="pill">Langfuse</span><span class="pill">ClickHouse</span>
</div>
</div>

<div class="skill-group" markdown="1">
#### Other Tooling
<div class="skill-tags">
<span class="pill">Hugging Face</span><span class="pill">MLflow</span><span class="pill">Ollama</span><span class="pill">TensorFlow</span><span class="pill">PyTorch</span>
</div>
</div>

</div>

## Achievements

<div class="achievements" markdown="1">

<div class="achievement" markdown="1">
<span class="icon">🥇</span>
<span><strong>1st Prize — BeachHack 2025</strong><span class="detail">LawLens AI, Compliance Assistant with 96% accuracy</span></span>
</div>

<div class="achievement" markdown="1">
<span class="icon">🥈</span>
<span><strong>1st Runner-Up — IBM GenAI Conclave 2024</strong><span class="detail">Livie, scalable multi-agent workflows using IBM Watsonx</span></span>
</div>

<div class="achievement" markdown="1">
<span class="icon">🥈</span>
<span><strong>2nd Place — Global Game Jam Kerala 2026</strong><span class="detail">Chaatan: The Last Ritual, multiplayer horror game</span></span>
</div>

<div class="achievement" markdown="1">
<span class="icon">🏆</span>
<span><strong>Best Project Award — S5, CS Dept, Sahrdaya College of Engineering and Technology 2024</strong></span>
</div>

<div class="achievement" markdown="1">
<span class="icon">🏆</span>
<span><strong>Best Project Award — Refine Hackathon 2023</strong></span>
</div>

</div>

## Education

<div class="edu-grid" markdown="1">

<div class="edu-item" markdown="1">
### B.Tech, Computer Science Engineering
<span class="detail">Sahrdaya College of Engineering & Technology · 2021 – 2025 · CGPA: 7.6 / 10</span>
</div>

<div class="edu-item" markdown="1">
### Higher Secondary (Computer Science)
<span class="detail">Don Bosco HSS Irinjalakuda · 2019 – 2021 · 97.5%</span>
</div>

</div>

## Interests

<ul class="interests-list">
<li>✍️ Blogging — <a href="https://dev.to/joeljaison394">dev.to/joeljaison394</a></li>
<li>🎨 Sketching / Drawing</li>
<li>🎮 Game Jams & Hackathons</li>
</ul>
