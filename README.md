# Hi, I'm Juan Felipe Ladeira

**Tech Lead · Fullstack Software Engineer (Python + React) · Applied AI**<br>
Rio de Janeiro, Brazil

I build production web systems end to end: domain modeling, Django/FastAPI APIs,
React + TypeScript frontends, and AI features that stay predictable in production.
Today I'm a **Tech Lead at MTM Tecnologia**, where I lead the team behind five
government systems in production for SEFAZ Bahia (Bahia's State Finance Department)
and contribute to **Neo AI**, an agentic framework on our Product team.

How I build with AI: deterministic workflows first, with the model only at controlled
decision points. I expose RPA automations as **MCP tools** that agents can call, and I
develop with Spec-Driven Development (spec → plan → code) with a human in the loop.

---

## Featured projects

### [Leaseflow](https://github.com/JuanLadeira/Leaseflow) · [live demo](https://leaseflow-web-8pqc.onrender.com)

A leasing dashboard for property managers: properties and units, a 600-lead inbox,
a tour agenda without double booking, and an **AI assistant that streams reply drafts
token by token** from Claude.

- **Frontend:** React 19, TypeScript, Redux Toolkit Query (optimistic updates with rollback),
  virtualized lists, filters kept in the URL, React Hook Form, lazy routes, dark mode, i18n
- **Backend:** Django + Django Ninja async views, JWT, SSE streaming over `StreamingHttpResponse`,
  PostgreSQL, layered apps (models → repositories → services → routers)
- **Quality:** Vitest + Testing Library + MSW flow tests, pytest, Docker Compose, GitHub Actions, Render Blueprint deploy
- Try it with `demo` / `leaseflow123` (free tier: the first request may take a minute to wake the API)

### [DocAgent](https://github.com/JuanLadeira/docagent)

A multi-tenant SaaS where configurable AI agents serve customers over **WhatsApp and Telegram**,
search indexed PDFs (RAG) and keep conversation memory. Orchestrated with LangChain and
LangGraph, connected to external tools through MCP, runs locally on GPU via Ollama, and is
covered by **500+ pytest tests written with TDD**.

---

## What I care about

- Domain modeling before code (DBML, class diagrams)
- Reproducible environments with Docker and CI/CD with GitHub Actions
- Rigorous automated testing (1,000+ tests in one production project)
- Documentation that non-technical stakeholders can read

---

## Tech stack

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![DRF](https://img.shields.io/badge/Django%20REST%20Framework-%23ff1709.svg?style=for-the-badge&logo=django&logoColor=white)
![Django Ninja](https://img.shields.io/badge/Django%20Ninja-30B980?style=for-the-badge&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-2F4F4F?style=for-the-badge&logo=pydantic)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-FC5C65?style=for-the-badge)
![Alembic](https://img.shields.io/badge/Alembic-5A5A5A?style=for-the-badge)
![Cookiecutter](https://img.shields.io/badge/Cookiecutter-d4aa00?style=for-the-badge)

### AI & Agents
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge)
![SpaCy](https://img.shields.io/badge/SpaCy-09A3D5?style=for-the-badge)

### Frontend
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![HTMX](https://img.shields.io/badge/HTMX-36C?style=for-the-badge)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TanStack Router](https://img.shields.io/badge/TanStack%20Router-CA4245?style=for-the-badge)

### Testing
![Pytest](https://img.shields.io/badge/Pytest-%230A9EDC.svg?style=for-the-badge&logo=pytest&logoColor=white)
![Hypothesis](https://img.shields.io/badge/Hypothesis-BD1C2B?style=for-the-badge)
![Factory Boy](https://img.shields.io/badge/Factory%20Boy-123456?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-45ba57?style=for-the-badge&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing%20Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

### DevOps & Infrastructure
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge)
![Poetry](https://img.shields.io/badge/Poetry-60A5FA?style=for-the-badge&logo=poetry)

---

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-felipe-6ba4181b3/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ladeirajuan96@gmail.com)
