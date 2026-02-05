# Hello, I'm Sumanth Malipeddi 👋

Welcome to my GitHub profile! I'm an **Associate Data Science Engineer at GetMySaas** with a Master's in Data Science & AI from IISER Tirupati (CGPA: 9.50/10). I specialize in building **production data pipelines**, **real-time streaming systems**, and **RAG-powered AI applications** using the modern data stack.

---

## 🚀 About Me

- **💼 Current Role**: Associate Data Science Engineer @ GetMySaas (Oct 2025 - Present)
- **🎓 Education**: MS in Data Science & AI, IISER Tirupati | BTech, SASTRA University
- **🔧 Building**: Production ETL pipelines with Airflow • Real-time streaming with Kafka • Lakehouse architecture with Iceberg • Semantic search with pgvector + OpenSearch
- **🧠 Focus**: Data Engineering, MLOps, NLP, and RAG Systems
- **📈 Learning**: 120+ days DSA consistency • Fundamentals of Data Engineering (Joe Reis) • Snowflake Platform Training
- **🎥 Content Creator**: Algorithm study timelapses, ML project walkthroughs, technical deep-dives

---

## 🛠️ Technical Stack

**Data Engineering & Orchestration**  
Apache Airflow • Apache Kafka • dbt • Apache Iceberg • Airbyte • Trino

**Databases & Storage**  
PostgreSQL • pgvector • OpenSearch • Redis • MinIO • AWS S3

**Data Quality & Observability**  
Great Expectations • OpenLineage • OpenMetadata

**ML & AI**  
TensorFlow • Scikit-learn • spaCy • Transformers • LangChain • Claude API • GPT-4

**Web Scraping & Document Intelligence**  
Playwright • Scrapy • Apache Tika • Tesseract OCR • Google Document AI

**Cloud & DevOps**  
AWS (EC2, S3, SageMaker) • Docker • MLflow

---

## 🔥 Featured Projects

### 1. [airflow-postgres-to-s3-pipeline](https://github.com/sumanthmalipeddi/airflow-postgres-to-s3-pipeline)

**Production-style Apache Airflow 3.x pipeline** for Airbnb data: PostgreSQL → AWS S3 with custom operators.

**What I Built:**
- **Idempotent batch ingestion** handling CSV NULL semantics, type mismatches, and COPY edge cases
- **Custom PostgresToS3Operator** using BaseOperator, PostgresHook, S3Hook with Airflow templating (`{{ ds }}`)
- **Production error handling**: Duplicate key violations, constraint failures, safe DAG re-runs
- **End-to-end ETL**: Ingest Airbnb listings from Postgres → Transform → Export to S3 for downstream analytics

**Key Learnings:**
- Correct CSV NULL handling (`\N` vs empty strings)
- Explicit column mapping in Postgres COPY
- Airflow task dependencies and trigger rules
- Building reusable, extensible operators

**Tech**: Apache Airflow 3.x • PostgreSQL • AWS S3 • Python • Pandas • Docker

---

### 2. [wiki-pipeline](https://github.com/sumanthmalipeddi/wiki-pipeline)

**Automated ETL pipeline** tracking hourly Wikipedia pageviews for major tech companies using Airflow + Celery + Redis.

**Architecture:**
- **Download & Extract**: Fetches Wikipedia pageview dumps hourly
- **Transform**: Cleans and structures raw dumps into tabular formats
- **Load**: Stores aggregated metrics in PostgreSQL
- **Orchestration**: Airflow DAGs with CeleryExecutor for distributed task execution

**Performance:**
- Full ETL cycle: ~39 seconds
- Download & extraction: 27 seconds
- Data transformation: 2 seconds
- Database insertion: <1 second

**Tech**: Apache Airflow 3.1.5 • PostgreSQL 16 • Docker Compose • Celery • Redis • Python

---

### 3. [promptengineering_study](https://github.com/sumanthmalipeddi/promptengineering_study)

**Hands-on study repository** for systematic prompt engineering with large language models.

**What's Inside:**
- **Prompt design patterns**: Few-shot learning, Chain-of-Thought (CoT), role-based prompts
- **Jupyter notebooks**: Comparing prompting strategies on classification, summarization, reasoning tasks
- **Practical workflows**: Prompt iteration, output evaluation, instruction tuning
- **Use cases**: Integrating prompt engineering into ML/NLP projects and RAG pipelines

**Why This Matters:**  
Systematic exploration of prompting techniques for production AI applications—essential for building reliable LLM-powered systems.

**Tech**: Python • LangChain • OpenAI API • Claude API • Jupyter Notebooks

---

## 📊 Other Key Projects

### [Housing Data Analytics & Engineering](https://github.com/sumanthmalipeddi/Housing_Data-Analytics-Engineering)
Modern data engineering showcase using ETL techniques for housing market data.  
**Tech**: Python • Jupyter Notebook • Pandas • SQL

### [Skills & Resume Intelligence Analyzer](https://github.com/sumanthmalipeddi/llm_carrerasst/tree/main)
Interactive web app for **resume analysis** and **salary prediction** using ML/NLP models:
- Named-entity recognition and skill extraction
- ATS-alignment scoring
- Salary range prediction based on skills, experience, and role
- Deployed on AWS EC2 + Streamlit Cloud

**Tech**: Streamlit • spaCy • Scikit-learn • AWS EC2 • Python

### Financial Sentiment Analysis Transformer
NLP transformer model analyzing financial texts (earnings calls, news, social media):
- **87%+ F1-score** on financial sentiment classification (positive, negative, neutral)
- Fine-tuned for domain-specific sentiment analysis
- Demonstrates transformer fine-tuning for specialized text domains

**Tech**: Transformers • TensorFlow • PyTorch • NLP

### [Spotify Trending Telugu Songs ETL](https://github.com/sumanthmalipeddi/spotify_trending_telugu)
Collects song, album, and artist details from Spotify API in intervals, performing ETL operations using AWS.  
**Tech**: Spotipy API • AWS • Python • Jupyter Notebook

---

## 💼 Professional Experience

### Associate Data Science Engineer @ GetMySaas (Oct 2025 - Present)

**Data Pipeline Architecture:**
- Managing **15+ Airflow DAGs** for automated extraction from social media APIs (X API, Reddit API) and web sources via Playwright and Scrapy crawlers
- Building **document intelligence workflows**: Apache Tika for text extraction, Tesseract and Google Document AI for OCR processing

**Modern Data Lakehouse:**
- Implementing **Airbyte connectors → S3/MinIO (Parquet bronze) → Apache Iceberg (silver/gold) → dbt transformations → Trino distributed queries**
- Developing **real-time event streaming** using Apache Kafka with Redis for caching and URL frontier management

**Data Quality & Governance:**
- Creating data quality frameworks with **Great Expectations** for validation
- **OpenLineage** for job lineage tracking
- **OpenMetadata** for data catalog and business glossary

**AI & Search Infrastructure:**
- Building **hybrid search**: OpenSearch (full-text lexical search) + PostgreSQL + pgvector (semantic vector embeddings)
- Powering **RAG-based AI applications** using Claude API, GPT-4, and Perplexity for intelligent document processing

---

## 🏆 Certifications

- **MS Data Science & AI** – IISER Tirupati (CGPA: 9.50/10)
- **Complete Data Science, Machine Learning, DL, NLP Bootcamp** – Udemy (Apr 2025)
- **Mathematics - Basics to Advanced for Data Science & GenAI** – Udemy (Oct 2024)
- **AWS Cloud Practitioner Essentials**

---

## 📈 GitHub Stats & Activity

- **99 contributions** in the last year
- **31 repositories** showcasing ETL pipelines, ML models, NLP systems, and data engineering projects
- **120+ days** consistent DSA problem-solving practice
- Active contributions to production data engineering and ML workflows

---

## 🤝 Connect with Me

- **LinkedIn**: [linkedin.com/in/sumanth-malipeddi](https://linkedin.com/in/sumanth-malipeddi)
- **Location**: Tirupati, Andhra Pradesh, India
- **Email**: Available on [GitHub Profile](https://github.com/sumanthmalipeddi)

---

## 💬 Open to Opportunities

I'm actively seeking roles in:
- **Data Engineering**: Building scalable ETL pipelines, lakehouse architectures, real-time streaming systems
- **ML Engineering**: Deploying ML models, MLOps, feature engineering, model serving
- **AI Engineering**: RAG systems, semantic search, LLM integration, prompt engineering

---

## 📝 Recent Activity Highlights

**Day 136** | Built production Airflow pipeline with custom Postgres→S3 operator, handling CSV NULL semantics and idempotent batch loads  
**Day 135** | Implemented ETL pipeline: PostgreSQL → S3 → Dockerized Pandas analysis for Airbnb pricing trends  
**Day 134** | Solved maximum subarray problem using Kadane's Algorithm (O(n) DP optimization); explored Airflow Connections for secure credential management  
**Day 131** | Mastered Dutch National Flag algorithm (three-way partitioning); learned Airflow troubleshooting with retry logic and trigger rules  
**Day 130** | Implemented Airflow branching using BranchPythonOperator and trigger rules (`none_failed`) for ERP system migration workflows

---

## 🎯 Philosophy

> **"Production pipelines live in edge cases."**

I believe in **learning by building** and **failing forward**—every broken pipeline, failed DAG run, and edge case teaches more than any tutorial. I document my journey publicly because **the failures are where the real learning happens**.

---

🔍 **Note**: This README is designed to be **clear, comprehensive, and recruiter-friendly** while showcasing **technical depth**. All projects include production-style error handling, scalable architecture, and real-world problem-solving.

Feel free to explore my repositories, star projects you find useful, and reach out for collaboration or mentorship opportunities!
