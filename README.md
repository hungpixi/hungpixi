<div align="center">

# Phạm Phú Nguyên Hùng

> *"Voyageur entre le code et les rêves"*  
> 🇫🇷 **DELF B2 Certified** · 🇻🇳 **Ho Chi Minh City, Vietnam**

### **Product-Minded Systems Builder & Pragmatic Software Engineer**
*Bridging Commercial Strategy, Resilient System Architecture, and Practical AI Tooling.*

[![GitHub](https://img.shields.io/badge/GitHub-26730023--PhamPhuNguyenHung-0F172A?style=flat-square&logo=github&logoColor=white)](https://github.com/26730023-PhamPhuNguyenHung)
[![Portfolio](https://img.shields.io/badge/Portfolio-phamphunguyenhung.com-2563EB?style=flat-square&logo=globe&logoColor=white)](https://phamphunguyenhung.com)
[![Email](https://img.shields.io/badge/Email-hungphamphunguyen%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hungphamphunguyen@gmail.com)
[![PyPI](https://img.shields.io/badge/PyPI-hcc--reader-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/hcc-reader/)
[![Education](https://img.shields.io/badge/UIT--VNUHCM-B.Sc.%20in%20IT-005BAA?style=flat-square&logo=university&logoColor=white)](https://www.uit.edu.vn)
[![DELF B2](https://img.shields.io/badge/Français-DELF%20B2-002395?style=flat-square&logo=france&logoColor=white)](https://www.france-education-international.fr)

</div>

---

## 🧭 About Me & Engineering Philosophy

I am a **Product-Minded Systems Builder and Pragmatic Software Engineer** with a distinctive dual-engine foundation: a formal background in **Business Strategy & Market Research** paired with **rigorous Computer Science training at the University of Information Technology (UIT – VNU-HCM)**.

Rather than writing code in isolation, I focus on solving **high-friction operational bottlenecks**, delivering **concrete commercial and civic value**, and creating leverage through **pragmatic systems automation**. My cross-functional journey enables me to translate complex stakeholder requirements into clear domain models, resilient software architectures, and intuitive digital products.

```text
🏛️ Academic Path:   University of Information Technology – VNU-HCM (UIT) | B.Sc. in Information Technology
🎖️ Business Foundation: Former Marketing Team Lead & BTEC FPT Valedictorian Track (HND Merit/Distinction, 100/100 Thesis)
🌐 Languages:           Vietnamese (Native) · English (Professional Working) · French (DELF B2 Certified)
⚙️ Core Focus:          Pragmatic Systems · Agentic Workflows (MCP) · Quantitative Pipelines · Developer Tooling
💡 Guiding Creed:       "Voyageur entre le code et les rêves" — Building with engineering rigor and visionary purpose.
```

---

## 🏆 Featured Flagships & Core Pillars

### 1. 🌍 [unicef-dustguard](https://github.com/26730023-PhamPhuNguyenHung/unicef-dustguard) — Civic Environmental Intelligence Platform
* **Honors:** **Top 6 National Finalist — UNICEF Youth Innovation Challenge 2026**
* **The Mission:** Mitigating urban air quality hazards for vulnerable children and school communities through real-time hyperlocal monitoring and civic action alerts.
* **Architecture & Engineering:** 
  * Low-latency IoT telemetry ingestion pipeline built on **Cloudflare Workers & Edge D1 Database**.
  * Dynamic geospatial hazard visualization using **real-time GIS mapping layers & MapLibre**.
  * Automated SMS and push notification queues dispatching actionable health advisories.
* **Tech Stack:** `TypeScript` `Cloudflare Workers` `D1 Database (Edge SQLite)` `GIS / MapLibre` `IoT Sensor Ingestion`

---

### 2. 🦜 [vietfi-advisor](https://github.com/26730023-PhamPhuNguyenHung/vietfi-advisor) — AI Financial Command Center
* **Honors:** **WebDev Arena (WDA) 2026 Showcase Project**
* **The Mission:** Demystifying wealth-building, credit card traps, and margin debt for Vietnamese young adults with tailored local market context.
* **Architecture & Engineering:**
  * Domestic financial market engine tracking real-time SJC physical gold rates, VN-Index metrics, and interbank deposit yields.
  * Centralized Debt Reduction Hub implementing automated **Debt-to-Income (DTI)** analysis and waterfall payoff amortization strategies.
  * Algorithmic **T+2.5 settlement stock backtesting engine** designed specifically for the Vietnamese securities regulatory framework.
  * Voice-driven multimodal AI companion (*"Vẹt Vàng"*) powered by streaming LLM agents and edge TTS.
* **Tech Stack:** `Next.js` `React 19` `Tailwind CSS` `Vercel AI SDK` `SQLite / Supabase` `Gemini`

---

### 3. 📦 [hcc-reader](https://github.com/26730023-PhamPhuNguyenHung/hcc-reader) — High-Performance Binary Tick/Bar Parser
* **Publication:** **Official PyPI Package Author** ([`pypi.org/project/hcc-reader`](https://pypi.org/project/hcc-reader/))
* **The Problem:** MetaTrader 5 stores historical tick and minute bar data in proprietary compressed binary `.hcc`/`.hc` containers, preventing quantitative researchers from running rapid offline analysis in Python.
* **Architecture & Engineering:**
  * Reverse-engineered binary format with zero-dependency C-struct byte slicing for maximum extraction throughput.
  * Direct extraction into columnar NumPy arrays and Pandas DataFrames with sub-second parsing benchmarks.
  * Distributed as an open-source package on PyPI to support algorithmic traders and quantitative researchers worldwide.
* **Tech Stack:** `Python` `Binary Decoding` `NumPy` `Pandas` `PyPI Distribution`

---

### 4. 📐 [revit-mcp](https://github.com/26730023-PhamPhuNguyenHung/revit-mcp) — Model Context Protocol for BIM Automation
* **Domain:** **Autodesk Revit BIM & Generative AEC Systems**
* **The Problem:** Architectural and MEP engineering teams spend hundreds of manual hours translating 2D CAD drafting sheets into parametric 3D Autodesk Revit family elements.
* **Architecture & Engineering:**
  * Enterprise Model Context Protocol (MCP) server establishing a bi-directional IPC bridge between frontier LLMs (Claude / GPT) and local Autodesk Revit runtime.
  * C# Revit .NET API controller executing transactional family instantiation, spatial clash checks, and automated parameter binding.
  * Automated layer-to-BIM mapping eliminating repetitive drafting tasks by over 70%.
* **Tech Stack:** `C# (.NET / Revit API)` `TypeScript` `Model Context Protocol (MCP)` `Dynamo` `Local IPC`

---

### 5. ⚙️ [ex5-backtest](https://github.com/26730023-PhamPhuNguyenHung/ex5-backtest) — Headless Algorithmic Trading Pipeline
* **Domain:** **Quantitative Finance & Automated Strategy Validation**
* **The Problem:** Manual compilation, backtesting, and parameter optimization of multi-asset Expert Advisors (EAs) on MetaTrader 5 GUI is labor-intensive, error-prone, and unscalable.
* **Architecture & Engineering:**
  * Headless CLI pipeline orchestrating automated batch compilation and historical backtesting for **70+ algorithmic strategies simultaneously**.
  * Multi-dimensional parameter optimization computing risk-adjusted metrics (Sharpe, Sortino, Max Drawdown, Recovery Factor) and compiling automated PDF/HTML performance catalogs.
  * Resilient error-recovery scripts and local tick-data cache management.
* **Tech Stack:** `PowerShell` `MQL5` `MetaTrader 5 CLI` `Python` `Quantitative Analytics`

---

### 6. 🎓 [UIT-Assistant](https://github.com/26730023-PhamPhuNguyenHung/UIT-Assistant) — Intelligent Campus Life Utility
* **Domain:** **Student Workflow Automation & Academic Operations**
* **The Mission:** Streamlining university life for UIT students through unified timetable synchronization, credit progression analytics, and automated administrative query resolution.
* **Architecture & Engineering:**
  * High-speed academic portal timetable parser with automated Google Calendar / iCal synchronization.
  * Credit audit dashboard tracking prerequisites, GPA trajectories, and graduation readiness milestones.
  * Instant campus bulletin parsing delivering curated notifications on scholarships, academic competitions, and deadlines.
* **Tech Stack:** `TypeScript` `Next.js` `FastAPI` `Student Portal Scraper` `PWA`

---

## 🛠️ Technical Capabilities & Pragmatic Stack

| Domain | Core Technologies & Tooling |
|---|---|
| **Systems & Architecture** | TypeScript, Python, C# (.NET), Go, PowerShell, Edge Runtimes (Cloudflare Workers, D1, KV) |
| **Frontend & Product UI** | Next.js (App Router), React 19, Tailwind CSS, Radix UI, TanStack Query, PWA *(Crisp Light Theme, High Contrast, No Glassmorphism)* |
| **AI Agents & Developer Tools** | Model Context Protocol (MCP), Vercel AI SDK, LangChain/LangGraph, Function Calling, Prompt Engineering, DevTools Workspaces |
| **Data & Quantitative Engineering** | NumPy, Pandas, XGBoost, MQL5, MetaTrader 5 Headless CLI, Gymnasium, Pine Script v6 |
| **Databases & Storage** | Cloudflare D1 (Edge SQLite), PostgreSQL (Supabase), Redis, SQLite, Vector Databases |
| **DevOps & Delivery** | Docker, Dokploy, GitHub Actions, Wrangler CLI, Linux/Windows Automation |

---

## 🎓 Academic Foundation & Leadership Track Record

* **University of Information Technology — VNU-HCM (UIT)** *(2026 – Present)*
  * *Bachelor of Science in Information Technology (B.Sc. in IT)*
  * Focus: Software engineering, distributed edge architectures, and real-world system integrations.
* **BTEC FPT International College** *(Graduated 2024)*
  * *Higher National Diploma (HND) in Business — Graduated with Merit/Distinction*
  * **100/100 Graduation Thesis Defense**: Market entry strategy, data-driven positioning, and financial feasibility modeling.
  * **Former Marketing Team Lead**: Directed student marketing initiatives, campus event organization, brand campaigns, and data tracking pipelines.
* **French Language Proficiency**
  * **DELF B2 Diploma** (*Diplôme d'Études en Langue Française*) — Confident communication, analytical writing, and international collaboration in French.

---

## 🤝 Connect & Collaborate

I am always open to discussions regarding **high-impact digital products**, **AI agent architectures**, **quantitative systems**, and **pragmatic software engineering**.

* 🌐 **Portfolio & Journal:** [phamphunguyenhung.com](https://phamphunguyenhung.com)
* 🐙 **GitHub:** [@26730023-PhamPhuNguyenHung](https://github.com/26730023-PhamPhuNguyenHung)
* 📦 **PyPI:** [pypi.org/user/hungpixi](https://pypi.org/user/hungpixi/)
* 📧 **Direct Inquiries:** [hungphamphunguyen@gmail.com](mailto:hungphamphunguyen@gmail.com)

---

<div align="center">

*"Voyageur entre le code et les rêves."*  
**Built with purpose, precision, and pragmatic engineering.**

</div>
