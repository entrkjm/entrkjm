# Jongmin Kim (김종민)

### Data & Applied AI Engineer

I build data + AI products end-to-end — from unstructured data pipelines to LLM-powered systems running in production — and I care most when that work connects to real business impact.

- Started in **NLP data analysis**, expanded into **data engineering** and **AI agent development**.
- Comfortable across the whole stack: data collection → ETL → analysis → datamart → product.
- Currently deployed as a **Forward Deployed Engineer (FDE)** at a public institution, building production AI agents.

---

### Tech Stack

**LLM / AI Agent**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![Claude Agent SDK](https://img.shields.io/badge/Claude%20Agent%20SDK-D97757?style=flat&logo=anthropic&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![OpenAI Apps SDK](https://img.shields.io/badge/OpenAI%20Apps%20SDK-412991?style=flat&logo=openai&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white)

**Backend / Data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**Cloud**
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFA000?style=flat&logo=firebase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

**Distributed / Big Data**
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=flat&logo=apachehadoop&logoColor=black)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)

---

### Featured Projects

**Multimodal LLM Influencer Analysis & Data Productization** — *WHOTAG*
Pipeline that analyzes global influencers (image / video / caption) with multimodal LLMs and turns the results into data products.
- Designed the analysis → datamart pipeline; modeled influence / authenticity scores via 1-vs-1 win-rate comparison.
- Cut analysis cost ~90% by moving repeated key-based lookups from BigQuery full scans to Firestore.
- Shipped the output as Data API / MCP / GPT Apps.
`Vertex AI` `Firestore` `BigQuery` `Python`

**Natural-Language Influencer Search SaaS** — *WHOTAG (Global B2C)*
Search engine that finds influencers from plain-language queries across 2.4M+ creators / 120 countries.
- LangGraph intent routing + text2sql / vector hybrid search (vector fallback when SQL fails).
- Trimmed storage cost 84% by pruning unused Firestore indexes based on real call statistics.
- Launched globally — peak MAU 10K, up to 10K queries/day at ~sub-cent per query.
`LangChain` `LangGraph` `text2sql` `Qdrant` `Docker` `CI/CD`

**Agentic Weekly Movie-Review Analytics** — *CJ CGV*
Automated system delivering AI-analyzed reviews of each week's new releases to a major cinema chain.
- 9-category classification + unsupervised clustering (HDBSCAN / UMAP) for sub-topic discovery.
- Auto-generated reports (Markdown → Marp), with edits delegated back to the LLM.
- Agentized weekly operation with Claude Agent SDK — ~90% less operating effort; PoC → annual contract.
`Claude Agent SDK` `LangGraph` `Python` `GCP`

**Social Big-Data NLP Analytics Engine** — *Infrastructure*
The in-house engine that powers B2B social-data reports: ETL, document management, and analysis indexing.
- Took over and ran a 40-node Hadoop / Spark indexing pipeline with zero downtime (tens of GB/day).
- Built hash-based deterministic sampling — same sample reproduces even as the document pool changes.
- Stood up collection monitoring + auto-recovery; migrated the engine to AWS with lifecycle-based cost control.
`Hadoop` `Spark` `Airflow` `dbt` `AWS (Glue / Athena / EMR)`

---

### Currently

- Building production AI agents as an FDE at a public institution.
- Interested in agent orchestration, retrieval, and data infrastructure that holds up at scale.

### Writing

- Co-author, *"Korean adolescents' coping strategies on self-harm, ADHD, insomnia during COVID-19: text mining of social media big data"* — **Frontiers in Psychiatry** (SCIE, 2023). Text-mining of ~12.5M adolescent social posts.
