<h1 align="center">Hi 👋, I'm Stephan Looten</h1>
<h3 align="center">Data Engineering · Marketing Technology · Orlando, FL</h3>

<br>

Final-year Computer Science student with 9 years of professional marketing experience. I've spent nearly a decade making decisions based on data, campaign performance, customer segmentation, pricing trends, and conversion funnels.

My background means I don't just move data from point A to point B. I understand what the analysts and marketers downstream actually need, because I've been that person.

---

## Featured Projects

### [citibike-weather-analytics](https://github.com/stephangl/citibike-weather-analytics)
Explored, cleaned, and merged NYC Citi Bike ridership data with NOAA weather data using pandas. Designed and implemented a normalized PostgreSQL database schema with analytics-ready SQL views for weather-based ridership analysis.

**Tech:** Python, pandas, PostgreSQL, Jupyter Notebooks

---

### [ai-lead-scoring-system](https://github.com/stephangl/ai-lead-scoring-system)
Built a production automated pipeline that receives form submissions via webhook, stores them in PostgreSQL, and scores each applicant using OpenAI with a strict evidence-based rubric and deterministic penalty overrides. The system doesn't trust the AI blindly — it runs word-count analysis on key fields, detects non-answers, and applies hard score penalties for low-evidence responses.

**Tech:** Node.js, Express, PostgreSQL, OpenAI API

**Key design decisions:**
- Deterministic penalties override AI scores when answers lack evidence (< 8 words, yes/no only)
- Concurrent processing with `FOR UPDATE SKIP LOCKED` prevents duplicate work across workers
- Raw payloads stored as JSONB for auditing and reprocessing
- Automatic retry with configurable max attempts

---

### Automated ETL Pipeline *(In Progress)*
Building a pipeline to routinely clean and transform a messy, multi-source subscriber database into a reliable analytical source of truth — with unit tests, error logging, and bash-scripted orchestration.

**Tech:** Python, pandas, PostgreSQL, Bash

---

## Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python, SQL|
| **Data** | pandas, NumPy, Jupyter Notebooks |
| **Databases** | PostgreSQL |
| **Tools** | Git, Bash, Docker, VS Code |
| **APIs** | OpenAI API, Webhooks |

---

## Background

Before pivoting to data engineering, I spent 9 years in marketing where I:
- Scaled an Amazon FBA operation to **$1M+ in revenue** with **11x ROAS** on ad spend
- Grew social media accounts generating **20M+ impressions** and **500K+ engagements**
- Managed paid campaigns across Meta, Google, and Amazon with six-figure budgets
- Built an e-commerce store (Shopify + Printful) generating **$70K+ in revenue** organically

That experience is why I care about data quality. Every bad join, missing field, and broken pipeline I've encountered downstream made me want to fix things upstream.

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stephan-gl/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sglooten@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=safari&logoColor=white)](https://stephangl.github.io/marketing/)
