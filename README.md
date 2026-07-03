# Hi, I'm Komalpreet 👋

I'm a **Master of Data Science (Computational Linguistics)** graduate from the **University of British Columbia (UBC)**, with approximately 3 years of industry experience building data pipelines, analytics and engineering solutions for Fortune 500 clients.

Previously I worked as a **Senior Software Engineer (Data Science)** at Merkle, supporting analytics and data engineering initiatives for **The Home Depot USA**. My work spanned building distributed feature engineering pipelines, automated reporting workflows and large-scale customer analytics using Python, SQL, BigQuery, PySpark, and Airflow on GCP.

My interests are in **machine learning, MLOps, applied AI, and data engineering** — building systems that combine statistical rigour, scalable infrastructure, and real-world business impact.

---

## Projects

---

### 🎗️ BC Cancer Exercise Oncology Chatbot
**Tools:** Python, LangChain, LangGraph, AWS Bedrock (Llama 3.3 70B), ChromaDB, Groq, RAGAS, Docker,CI/CD

Capstone project developed in collaboration with **BC Cancer** and **UBC**, building an AI-powered exercise coaching assistant grounded in clinical exercise oncology resources.

- Built a **multimodal document processing pipeline** to ingest research papers, clinical manuals, motivational interviewing transcripts, and audio/video content into a structured **ChromaDB** knowledge base with metadata filtering for efficient retrieval
- Designed an **agentic RAG workflow** using **LangChain** and **LangGraph**, orchestrating semantic routing, retrieval, cross-encoder reranking (ms-marco-MiniLM-L-6-v2), citation validation, conversation memory, and a 5-tier safety router.
- Integrated **AWS Bedrock Llama 3.3 70B** as the primary generation model with **Groq** as a fallback, and used **all-MiniLM-L6-v2** embeddings for semantic retrieval
- Evaluated response quality using **RAGAS** (faithfulness, answer relevancy, context precision) and retrieval metrics to benchmark grounding and relevance
- Deployed the application on **AWS ECS Fargate** via **CloudFormation** with a **Streamlit** UI and containerized CI/CD workflows

---

### 💳 American Express Credit Default Prediction
**Tools:** Python, PySpark, Dataproc Serverless, BigQuery, Vertex AI (Pipelines, Endpoint, Model Registry, Experiments), LightGBM, XGBoost, Optuna, MLflow, Redis (Memorystore), Pub/Sub, Dataflow (Apache Beam), SHAP, GCS

🔗 [GitHub Repo](https://github.com/komalpreet10/amex-credit-default-prediction)

End-to-end credit default prediction pipeline built on GCP, predicting the probability of customer default using anonymized behavioral credit card data from the **Kaggle AmEx competition**.

- Designed and deployed an end-to-end credit default prediction pipeline on GCP, orchestrating distributed feature engineering, hyperparameter tuning, model training, and real-time inference across monthly statement cycles.
- Engineered 22+ behavioral, temporal, and statistical aggregations across delinquency, spend, payment, balance, and risk variables; optimized a LightGBM model via Optuna with stratified cross-validation, achieving a 0.959 ROC-AUC and 0.894 PR-AUC on imbalanced data.
- Integrated SHAP for model explainability and PSI to assess potential feature drift in production
- Built a three-tier real-time inference pipeline using **Redis** (Memorystore) as an online feature store, **BigQuery** as a fallback lookup, and **Vertex AI Endpoint** for model serving, with streaming feature updates via **Pub/Sub** and **Dataflow** on each statement cycle close

---

### Transformer From Scratch (Encoder + Decoder)
**Tools:** Python, PyTorch

🔗 [GitHub Repo](https://github.com/komalpreet10/pytorch-transformer-from-scratch)

Implementation of the Transformer architecture ("Attention Is All You Need") built entirely from raw PyTorch.

- Implemented **multi-head self-attention**, sinusoidal **positional encoding**, and position-wise feed-forward layers from scratch, with a shared core reused across both encoder and decoder variants
- Built an **encoder-only (BERT-style)** model with bidirectional attention for text classification on **AG News** (4-class, 120K articles), achieving **91.3% validation accuracy** with a custom word-level tokenizer built from scratch
- Built a **decoder-only (GPT-style)** model with causal self-attention for character-level autoregressive text generation on **Tiny Shakespeare**, with a custom character-level tokenizer
- Verified architectural correctness with 11 unit tests covering attention mechanics, causal masking (zero future-token leakage), and residual connection integrity


### 🔐 Membership Inference Attacks on LLMs and VLMs
**Tools:** Python, PyTorch, Hugging Face Transformers, CLIP

🔗 [GitHub Repo](https://github.com/komalpreet10/membership_inference_attacks)

Security research project targeting fine-tuned LLMs and Vision-Language Models (VLMs) to assess privacy vulnerabilities in model training data.

- Investigated membership inference attacks on fine-tuned LLMs and VLMs using loss-based and entropy-based approaches
- Developed EM-MIAs ensemble using XGBoost combining LOSS, zlib, Min-k%, and reference model features with 5-fold CV,achieving AUC 0.83 on clinical text data
- Applied CLIP-based image-text alignment for VLM membership inference, achieving AUC 0.78
- Conducted experiments on 50K+ samples and evaluated using ROC-AUC and TPR@FPR metrics across text and image-caption datasets

### 🛒 Amazon Product Query Assistant
**Tools:** Python, BM25 (rank-bm25), FAISS, Sentence Transformers, OpenAI GPT-4o-mini, RAGAS, Docker, GitHub Actions

🔗 [GitHub Repo](https://github.com/komalpreet10/Amazon_Product_Query_Assistant)

Product search and recommendation system built on **112,000+ Amazon products** and **701,000+ customer reviews** from the Amazon Reviews 2023 All\_Beauty dataset.

- Implemented **hybrid retrieval** combining BM25 sparse search and semantic dense search via **FAISS**, fused using Reciprocal Rank Fusion (RRF) for improved ranking
- Built a **RAG pipeline** using **GPT-4o-mini** for grounded product recommendations with input/output guardrails to prevent hallucination and off-topic responses
- Evaluated retrieval and generation quality using **RAGAS** (faithfulness, answer relevancy) and standard IR metrics (precision@k, recall@k, NDCG)
- Containerized the application using **Docker** and automated testing and deployment via **GitHub Actions CI/CD**
---

## Technical Skills

| Category | Tools & Technologies |
|---|---|
| **Languages** | Python, SQL, R |
| **Machine Learning** | LightGBM, XGBoost, scikit-learn, PyTorch, Optuna, SHAP |
| **AI & NLP** | RAG, LangChain, LangGraph, ChromaDB, FAISS, Sentence Transformers, AWS Bedrock, GPT-4o-mini |
| **Data Engineering** | PySpark, Apache Airflow, Apache Beam, Dataflow, BigQuery, GCS |
| **Cloud & MLOps** | GCP (Vertex AI, Dataproc, Pub/Sub, Memorystore), AWS (Bedrock, ECS Fargate), MLflow, Docker, CI/CD |
| **Databases & Storage** | BigQuery, ChromaDB, Redis, PostgreSQL |
| **Evaluation** | RAGAS, PSI, IR metrics |
| **Visualization** | Tableau, Matplotlib, Seaborn |

---

## 📚 Currently Learning

- Production ML systems and MLOps best practices
- LLM evaluation, monitoring, and observability
- Real-time feature stores and streaming inference
- Agentic AI system design

---

## 🎓 Education

**University of British Columbia** — Master of Data Science (Computational Linguistics) | Jun 2026

**Langara College** — Post-Degree Diploma, Data Analytics | Apr 2025

**Lovely Professional University** — B.Tech, Electronics & Communications Engineering | 2020

---

## 📬 Connect

- 📧 Email: [komalubc@gmail.com](mailto:komalubc@gmail.com)
- 🔗 LinkedIn: [linkedin.com/in/komalpreet-28b3231a0](https://www.linkedin.com/in/komalpreet-kaur-28b3231a0/)
- 🌐 Portfolio: [komalpreet-portfolio-lac.vercel.app](https://komalpreet-portfolio-lac.vercel.app)
