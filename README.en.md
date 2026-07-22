<div align="center">

# Pietro Prauchner

### Full-stack developer focused on Python backend and applied AI

**Looking for a software engineering internship — Alegrete/RS (Brazil) or remote · evening degree program**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pietroprauchner/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pietro.mprauchner@gmail.com)
[![Lattes](https://img.shields.io/badge/Lattes_CV-0A5C9E?style=for-the-badge&logoColor=white)](http://lattes.cnpq.br/8153919281360932)

**[🇧🇷 Português](README.md) · [🇺🇸 English](README.en.md)**

</div>

Software Engineering student at **UNIPAMPA — Alegrete/RS, Brazil**, in the 4th of 9 semesters (expected graduation: mid-2029). I like taking an idea off paper and watching it work end to end: gathering the requirements, designing the architecture, writing the code — and leaving the project organized enough that someone else can step into it the next day.

---

## 💼 Experience

**Extension Research Fellow — AI Horizon Labs / UNIPAMPA** · 2026 – present · 20h/week

Project *Educador 5.0: Training Teachers to Use Artificial Intelligence in Basic Education*. I work on-site in the continuing education of K-12 teachers, translating AI tools into practical classroom use.

---

## 🚀 Featured projects

### [SAGA — Academic Monitoring and Management System](https://github.com/PPrauchner/SAGA-Sistema-de-Acompanhamento-e-Gestao-Academica)

Management system for graduate programs: student registration, work plans, credit validation, deadline extensions and management reports. Six-person team project, featuring a **logic inference engine built from scratch in Python** and **Aspect-Oriented Programming** for authorization, auditing and alerts.

> **My role:** top contributor to the repository (307 commits). I gathered the requirements, organized the team's work and wrote most of the issues and documentation. I **designed the inference engine's architecture** — the split between terms, unification, substitution, resolver and knowledge base — and wrote the **declarative rule layer (RL01–RL05)** and the **test suite** the team implemented against. I reviewed half of the pull requests and worked across backend, frontend and database.

`Python` `FastAPI` `React` `TypeScript` `Firebase` `pytest`

### [ORÁCULO — Python dependency auditing](https://github.com/PPrauchner/Oraculo)

Web tool that cross-references what a project **declares** it depends on (`pyproject.toml`, `requirements.txt`, `environment.yml`) against what the code **actually imports**, via AST analysis, and checks both against PyPI. It reports *Zombies* (declared but never used), *Ghosts* (imported but never declared) and outdated packages, with size, age and a Health Index.

> **My role:** 227 of the repository's 238 commits — effectively my own project. Core fully decoupled from the UI, parsers registered by decorator, test suite, internationalization (pt/en) and documented architecture decisions.

`Python` `Streamlit` `Plotly` `AST` `uv`

### [LazyPR — functional analysis of pull requests](https://github.com/PPrauchner/LazyPR-Grupo-06)

Platform that lazily ingests large GitHub pull request datasets and classifies them semantically via LLM (Groq/Llama): nature of the change, description clarity and project type. Fully functional pipeline — pure functions, composition, `map`/`filter`/`reduce` — with interactive dashboards.

> **My role:** top contributor to the repository (56 commits). I built the **LLM integration layer** — prompt engineering, retry logic and Groq rate-limit handling — along with the classifiers for change nature, description clarity and project type, plus the **multi-level cache with atomic disk persistence**. I wrote half of the test suite and handled requirements, team organization, issues and PR review.

`Python` `LLM (Groq/Llama)` `Streamlit` `Functional Programming`

---

## 📌 Other projects

- **[Maria Dinoir's Website — Therapist](https://github.com/PPrauchner/Site-de-terapeuta)** · **[🔗 live](https://maria-dinoir-terapeuta.com/)** — professional website for a real client, from briefing to delivery: institutional pages, interactive FAQ, modals and WhatsApp scheduling. Started in plain HTML/CSS and later migrated to Astro, reorganizing the entire CSS into a design system of my own. `Astro` `TypeScript` `CSS`
- **[mini-simulador-edge-cloud](https://github.com/PPrauchner/mini-simulador-edge-cloud)** — simulator for task allocation across Edge-Cloud infrastructure, built as a technical challenge for a research fellowship process. `Python`

---

## ⚙️ How I work

I treat small projects with the same process as large ones — that's what lets someone else (or me, three months later) actually step into them.

- **Issues and pull requests even on solo projects.** Over the last 12 months: ~1,200 contributions, 52 PRs and 205 issues.
- **Written decisions.** Every project has a `CONTEXT.md` with the domain model and ADRs under `docs/adr/` recording decisions and their rationale — the source of truth before implementing.
- **Atomic commits** and coding conventions versioned alongside the project.
- **Automating my own workflow.** I maintain [`.claude-generica`](https://github.com/PPrauchner/.claude-generica), the skills, hooks and rules I use to standardize PR review, issue creation and commits. That's the base I adapted to organize the team's workflow on SAGA.

---

## 🛠️ Stack

**Backend**  Python · FastAPI · Firebase

**Frontend**  TypeScript · React · Astro · HTML/CSS

**Data & AI**  LLM integration (Groq/Llama) · AST analysis · Streamlit · Plotly

**Practices**  Git · issues and code review · pytest · uv · ADRs

---

## 📫 Contact

Looking for a software engineering internship, **in Alegrete/RS (Brazil) or remote**. My degree program runs in the evening — I'm available during the day.

**[LinkedIn](https://www.linkedin.com/in/pietroprauchner/)** · **[Email](mailto:pietro.mprauchner@gmail.com)** · **[Lattes CV](http://lattes.cnpq.br/8153919281360932)**
