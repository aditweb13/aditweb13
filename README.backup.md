<div align="center">

<img src="assets/banner.svg" alt="Aditya Raj: AI/ML and data analysis" width="100%">

**I build LLM systems that check their own answers, and I turn messy data into dashboards people can act on.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-aditya--raj-1F6F5B?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-raj-a1891a285)
[![Email](https://img.shields.io/badge/Email-adi111sam121%40gmail.com-5B3F8C?logo=gmail&logoColor=white)](mailto:adi111sam121@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-aditweb13.github.io-B86E14)](https://aditweb13.github.io)

</div>

<!-- TODO: confirm the portfolio URL after enabling GitHub Pages -->

## About me

- B.E. in Bio-Technology at **RV College of Engineering**, Bengaluru (currently pursuing).
- Currently a **Data Analyst & Software Developer intern** at Pushpaka Dashanan, working on three portals.
- Previously a Data Analyst intern at Bold Analytics (May 2026 – Jul 2026), using Pandas, SQL and Power BI.
- Looking for **AI/ML Engineer and Applied AI internships or entry-level roles**, and **Data Analyst / Business Analyst roles**.

## Featured projects

| Project | Outcome | Stack |
|---|---|---|
| **Cascade** · cost-aware Nemotron model router *(TODO: repo link)* | **65.7% lower cost** than Super-only on a 40-ticket dev set, at 90.0% accuracy | Python, FastAPI, SQLite, Streamlit, Docker |
| **OpenEnv (City Ops)** · emergency response simulator *(TODO: repo link)* | EMS, Fire and Police agents trained with PPO across **8 Indian cities** | Next.js, React Three Fiber, FastAPI, PPO |
| **RTI-Lens** · RTI analytics platform *(TODO: repo link)* | Hybrid RAG over **713 CIC precedent documents**; **MLH Track Prize**, NMIT HACKS 2026 | React, FastAPI, Groq, Gemini, PostgreSQL, MongoDB |
| **Dynamic Parking Pricing** · Summer Analytics 2025 capstone *(TODO: repo link)* | Real-time pricing simulation for **14 lots over 73 days**, comparing 3 models | Python, Pathway, Bokeh |
| **FermentAI** · yield prediction and media optimization *(TODO: repo link)* | Compares **3 models** on R², MAE and RMSE, then recommends fermentation conditions | Python, Scikit-learn, XGBoost, SciPy, Streamlit |

<details>
<summary><b>Detailed results and caveats</b></summary>

**Cascade**
- Starts on NVIDIA Nemotron Nano and escalates to Super and Ultra only when a verifier rejects the answer (schema, tool-grounding, policy rules, self-consistency, LLM judge).
- Logs tokens, cost and latency per call to SQLite; includes a Streamlit dashboard, an evaluation harness and a Docker image.
- Dev set (40 synthetic support tickets): **90.0% accuracy at 65.7% lower cost** than Super-only.
- Held-out set (50 frozen tickets): **42.0% accuracy vs 56.0% for single-tier baselines**, at about 73% lower cost than Super-only. The saving held up, but accuracy did not.

**OpenEnv (City Ops)**
- 3D simulator with EMS, Fire and Police agents across 8 Indian cities, trained with PPO.
- Includes a simulated signal-spoofing scenario with a spatial trust heatmap; deployed on Hugging Face Spaces.

**RTI-Lens**
- Hybrid RAG (BM25 + embeddings) over 713 CIC precedent documents, plus a multi-agent pipeline of three Groq agents with Gemini orchestration.
- Produces case-grounded RTI answers, draft appeals and outcome predictions.
- Won the MLH Track Prize (Backboard.io) at NMIT HACKS 2026.

**Dynamic Parking Pricing**
- 14 parking lots over 73 days, about 18,000–20,000 records at 30-minute intervals, streamed through Pathway.
- Three pricing models compared: linear, demand-based (manually tuned weights), and competitive (Haversine proximity), with live Bokeh visualisation.

**FermentAI**
- Linear Regression, Random Forest and XGBoost, with the best model chosen automatically by R², MAE and RMSE.
- SciPy Differential Evolution plus Randomized Search recommend fermentation conditions in a Streamlit dashboard.

</details>

## Tech stack

| Area | Tools |
|---|---|
| **AI / LLM** | NVIDIA Nemotron (API), LLM routing and verification, function calling, hybrid RAG (BM25 + embeddings), multi-agent LLM pipelines, Groq, Gemini |
| **Data and analytics** | SQL, Python, Pandas, NumPy, Excel, Power BI, Matplotlib, Bokeh, Pathway (streaming) |
| **Machine learning** | Scikit-learn, XGBoost, SciPy, reinforcement learning (PPO) |
| **Backend** | FastAPI, Pydantic, React, Streamlit, PostgreSQL, MongoDB Atlas, SQLite |
| **Tools** | Docker, Git/GitHub, Hugging Face Spaces |

## Experience

- **Data Analyst & Software Developer Intern**, Pushpaka Dashanan: ongoing (TODO: start date). Three portals, mixing data analysis and development.
- **Data Analyst Intern**, Bold Analytics (remote), May 2026 – Jul 2026: cleaned datasets with Pandas and NumPy, found trends and anomalies with SQL, Excel and Python, built Power BI dashboards.
- **Cybersecurity Analyst Virtual Job Simulation**, Tata Group (Forage), May 2024.

## Achievements and leadership

- **MLH Track Prize (Backboard.io)**, NMIT HACKS 2026, for RTI-Lens.
- **Reliance Foundation Scholar**: ₹50,000/year merit scholarship; All India Rank 566 among 4.6+ lakh students in a national exam.
- **Joint Director, Club Services Avenue**, Rotaract Club of RVCE (2025–26).

## Certifications

Cybersecurity Analyst Job Simulation (Tata, Forage) · Networking Basics (Cisco) · AI/ML, Python, Java (Udemy) · Cybersecurity Fundamentals (Udemy) · Leadership & Sustainability (IUCEE NEP)

## GitHub stats

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=aditweb13&show_icons=true&theme=dark&hide_border=true">
  <img alt="Aditya's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=aditweb13&show_icons=true&hide_border=true">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=aditweb13&layout=compact&theme=dark&hide_border=true">
  <img alt="Aditya's top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aditweb13&layout=compact&hide_border=true">
</picture>
</div>

---

<div align="center">

Bengaluru · [adi111sam121@gmail.com](mailto:adi111sam121@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aditya-raj-a1891a285)

</div>
