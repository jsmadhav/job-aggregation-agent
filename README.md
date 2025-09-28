# Agentic Job Aggregation Framework (PoC)

## Overview
This project explores agentic frameworks for job aggregation using **LangGraph** for workflow orchestration and **Selenium** for dynamic web scraping.  
The proof-of-concept agent extracts structured job postings from multiple career portals (Google, Meta, Greenhouse).

## Features
- 🕸️ Selenium-based scraping with infinite scroll and consent overlay handling  
- 🧩 LangGraph workflow: `detect → parse → enrich → normalize`  
- 📝 Enrichment: fetch job descriptions from detail pages  
- 📊 Exports: CSV/JSON for downstream analytics  
- 🤖 Optional LLM normalization for titles and locations  

## Tech Stack
- Python 3.10+
- Selenium
- LangGraph
- Pandas
- tqdm

## Getting Started
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Main.ipynb
