<h1 align="center">Talin Daga</h1>

<p align="center">
  <strong>Backend Engineer</strong> · Python · Django · PostgreSQL · Docker<br>
  <sub>CS undergrad at Scaler School of Technology & BITS Pilani · Bangalore, India</sub>
</p>

<p align="center">
  <a href="mailto:talindaga692@gmail.com">
    <img src="https://img.shields.io/badge/Email-talindaga692%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/talin-daga/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://drive.google.com/file/d/1o6qLdTB1wFJFt5Pb61im7XK-jWmEMUPn/view?usp=sharing">
    <img src="https://img.shields.io/badge/Résumé-View-34A853?style=flat-square&logo=googledrive&logoColor=white" />
  </a>
</p>

---

I build backend systems that actually ship. As a solo freelancer I took a **B2B e-commerce platform from zero to production in 6 weeks** — Django REST API, React frontend, PostgreSQL — now [live at pronounjeans.com](https://www.pronounjeans.com/) and serving **50+ active B2B users**. Most of my work sits at the intersection of clean API design, concurrency correctness, and containerized deployment.

**Currently:** building [CodeGraph](https://github.com/Talin12/CodeGraph) — a static-analysis engine that maps code relationships using Python's AST, with Celery + Redis handling heavy parsing off the request thread.

**Open to:** backend / full-stack internships at early-stage startups where I can own features end-to-end.

<p align="left">
  <a href="https://www.pronounjeans.com/"><img src="https://img.shields.io/badge/Live_in_production-pronounjeans.com-16A34A?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Active_B2B_users-50%2B-0A0A0A?style=flat-square" />
  <img src="https://img.shields.io/badge/Projects_shipped-3-0A0A0A?style=flat-square" />
  <img src="https://img.shields.io/badge/LeetCode-150%2B_solved-0A0A0A?style=flat-square&logo=leetcode&logoColor=white" />
  <img src="https://img.shields.io/badge/Retail_Insight-Top_5_of_200%2B-0A0A0A?style=flat-square" />
</p>

---

## What I've Shipped

### 🛒 B2B E-commerce Platform — *Pronoun Jeans*
**Freelance · Live in production · Mar–Apr 2026**

&nbsp;&nbsp;[**🌐 Live Site**](https://www.pronounjeans.com/) &nbsp;·&nbsp; [**💻 Code**](https://github.com/Talin12/Pronoun-jeans)

Designed, built, and deployed the entire platform solo, end-to-end.

- **50+ active B2B users** on the live platform today
- **4 modular DRF apps** — product catalog, cart, checkout, order management — exposing REST APIs to a React frontend
- **3-service deployment pipeline** owned end-to-end: Django on Render Pro, React on Vercel, PostgreSQL on Supabase
- Diagnosed and fixed a production static-file outage via Django's `collectstatic` pipeline + Whitenoise — **eliminated 100% of frontend asset errors**

<sub>`Django` `Django REST Framework` `PostgreSQL` `Supabase` `React` `Whitenoise` `Render` `Vercel`</sub>

---

### 🕸️ CodeGraph
**In progress · June 2026 – Present**

&nbsp;&nbsp;[**💻 Code**](https://github.com/Talin12/CodeGraph)

Code-parsing system built on Python's `ast` module to extract structural relationships from source files.

- Async parsing via **Celery + Redis** — resource-intensive jobs never block the main application thread
- **Multi-container stack** — frontend, backend, and Celery workers containerized and orchestrated with Docker Compose
- RESTful API serves parsed AST data and code metrics to a **React + Vite** frontend that renders the graphs

<sub>`Python` `Celery` `Redis` `Docker` `Docker Compose` `React` `Vite`</sub>

---

### 🏦 Bank Server
**Dec 2025 – Feb 2026**

&nbsp;&nbsp;[**💻 Code**](https://github.com/Talin12/Bank-server)

Full-stack banking application — designed and built the React frontend and Django REST backend independently.

- **Atomic fund transfers** using Django ORM's `select_for_update()` — prevents double-spend under concurrent requests
- PostgreSQL schemas with **integrity constraints** enforcing valid financial states at the database level
- Structured into modular Django apps for clean separation of concerns

<sub>`Django` `PostgreSQL` `REST APIs` `Docker` `React`</sub>

---

## Tech Stack

**Languages** &nbsp;&nbsp;`Python` `JavaScript` `SQL` `Java`

**Backend** &nbsp;&nbsp;`Django` `Django REST Framework` `Celery`

**Frontend** &nbsp;&nbsp;`React` `Vite`

**Data & Infra** &nbsp;&nbsp;`PostgreSQL` `Redis` `Supabase` `Docker` `Docker Compose` `Linux` `Git` `Postman`

**Focus areas** &nbsp;&nbsp;REST API design · async task processing · concurrency control · database schema design · containerization

---

## GitHub

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Talin12&theme=default" alt="Top Languages by Repo" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Talin12&theme=default" alt="Top Languages by Commit" />
</p>

<p align="center">
  <sub>Reach me at <a href="mailto:talindaga692@gmail.com">talindaga692@gmail.com</a> — I reply fast.</sub>
</p>
