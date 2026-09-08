# Hi, I'm Komalpreet 👋

I'm a **Data Scientist at the University of British Columbia (UBC)**, working on NLP, machine learning, and Generative AI applications in healthcare research.

I have 3 years of industry experience building machine learning solutions, data pipelines, and analytics systems. Previously, I worked as a **Senior Software Engineer – Data Science at Merkle**, supporting **The Home Depot USA**, where I developed large-scale data and analytics solutions using Python, SQL, BigQuery, PySpark, Airflow, and Google Cloud Platform.

I hold a **Master of Data Science (Computational Linguistics) from UBC**. My interests span **machine learning, Generative AI, NLP, MLOps, and data engineering**, with a focus on building reliable and scalable AI systems.

---

## 🚀 Projects

### 🎗️ BC Cancer Exercise Oncology Chatbot

**Tech:** Python, AWS Bedrock, Llama 3 70B, ChromaDB, RAG, RAGAS, Docker, AWS ECS Fargate, CloudFormation, CI/CD

AI-powered exercise coaching assistant developed in collaboration with **BC Cancer and UBC**, grounded in clinical exercise oncology resources.

- Built a **multimodal document processing pipeline** for research papers, clinical manuals, motivational interviewing resources, and audio/video content.
- Designed an **agentic RAG workflow** combining semantic routing, retrieval, cross-encoder reranking, citation validation, conversational memory, and safety routing.
- Integrated **AWS Bedrock Llama 3 70B** for generation and **all-MiniLM-L6-v2** embeddings with ChromaDB for semantic retrieval.
- Evaluated retrieval and generation quality using **RAGAS** and information retrieval metrics.
- Deployed the application on **AWS ECS Fargate** using Docker and CloudFormation with automated CI/CD workflows.

---

### 🤖 Agentic Text-to-SQL

**Tech:** Python, LangGraph, LangChain, Groq, PostgreSQL, SQLAlchemy, SQLGlot, FastAPI, Streamlit, LangSmith

🔗 [GitHub Repository](https://github.com/komalpreet10/agentic-text2sql)

Agentic analytics application for conversational querying of relational e-commerce data using natural language.

- Built a **LangGraph workflow** for question contextualization, dynamic schema selection, SQL generation, execution, and grounded answer generation.
- Implemented **SQL validation and self-repair** using SQLGlot and database execution feedback with conditional routing and bounded retries.
- Added **conversational memory** for multi-turn analytical questions and **LangSmith tracing** for LLM and workflow observability.
- Exposed the system through a **FastAPI backend** and interactive **Streamlit interface**.

---

### 🖼️ ViT Fine-Tuning on Food-101

**Tech:** Python, PyTorch, Hugging Face Transformers, PEFT, LoRA, Torchvision

🔗 [GitHub Repository](https://github.com/komalpreet10/vit-lora-food101)

Compared parameter-efficient and full fine-tuning approaches for adapting a pretrained Vision Transformer to Food-101.

- Fine-tuned `google/vit-base-patch16-224` on **60,600 training images across 101 classes**.
- Compared **linear probing, LoRA, and full fine-tuning**, ranging from 0.09% to 100% trainable parameters.
- LoRA achieved **85.35% validation accuracy while training only 0.43% of model parameters**, compared with 85.09% for full fine-tuning and 81.82% for linear probing.

---

### 👗 H&M Personalized Recommendation System

**Tech:** Python, Implicit ALS, CLIP, LightGBM, LambdaRank, Learning-to-Rank

🔗 [GitHub Repository](https://github.com/komalpreet10/hm-personalized-recommendation-system)

Two-stage recommendation system combining collaborative filtering, multimodal representations, and learning-to-rank.

- Built candidate generation using **implicit ALS, CLIP image/text embeddings, product metadata, and popularity-based retrieval**.
- Developed a **LightGBM LambdaRank reranker** using collaborative, content, popularity, and retrieval signals.
- Implemented **temporal validation and mixed hard/random negative sampling** for leakage-safe offline evaluation.

---

### 💳 American Express Credit Default Prediction

**Tech:** Python, PySpark, Dataproc Serverless, BigQuery, Vertex AI, Kubeflow Pipelines, LightGBM, Optuna, MLflow

🔗 [GitHub Repository](https://github.com/komalpreet10/amex-credit-default-prediction)

End-to-end ML pipeline for predicting customer credit default using the Kaggle American Express dataset.

- Designed **batch training and inference pipelines on GCP**, integrating Dataproc Serverless, BigQuery, LightGBM, Optuna, Vertex AI Batch Prediction, and Kubeflow Pipelines.
- Engineered behavioral, temporal, and statistical features across delinquency, spending, payment, balance, and risk variables.
- Achieved **0.959 ROC-AUC, 0.894 PR-AUC, and 0.808 F1-score** on imbalanced data.

---

### 🛒 Amazon Product Query Assistant

**Tech:** Python, BM25, FAISS, Sentence Transformers, OpenAI GPT-4o-mini, RAG, RAGAS, Docker, GitHub Actions

🔗 [GitHub Repository](https://github.com/komalpreet10/Amazon_Product_Query_Assistant)

Hybrid search and RAG system built on **112,000+ Amazon products and 701,000+ customer reviews**.

- Implemented **hybrid retrieval** combining BM25 sparse search and FAISS dense retrieval using Reciprocal Rank Fusion (RRF).
- Built a **RAG pipeline** using GPT-4o-mini for grounded product recommendations with input/output guardrails.
- Evaluated the system using **Precision@K, Recall@K, NDCG, RAGAS faithfulness, and answer relevancy**.
- Containerized the application with **Docker** and implemented CI/CD using **GitHub Actions**.

---

## 🛠️ Technical Skills

| Category | Tools & Technologies |
| --- | --- |
| **Programming** | Python, SQL, R |
| **Machine Learning** | PyTorch, Scikit-learn, XGBoost, LightGBM, Optuna, SHAP, Regression, Classification, Clustering, Learning-to-Rank |
| **Generative AI & LLMs** | OpenAI, Claude, LLaMA, LangChain, LangGraph, RAG, LoRA/PEFT, Prompt Engineering, Tool Calling, Agentic Systems |
| **NLP & Retrieval** | Transformers, Sentence Transformers, Embeddings, FAISS, ChromaDB, BM25, Hybrid Search, Reranking, RAGAS |
| **Computer Vision** | PyTorch, Vision Transformers (ViT), CLIP, Hugging Face Transformers |
| **Data Engineering** | PySpark, Apache Spark, Airflow, Apache Beam, Dataflow, BigQuery |
| **Cloud & MLOps** | GCP (Vertex AI, BigQuery, Dataproc, Cloud Composer), AWS (Bedrock, ECS, S3), MLflow, Docker, GitHub Actions, CI/CD |
| **Databases** | PostgreSQL, BigQuery, Redis, ChromaDB |
| **Statistics** | A/B Testing, Hypothesis Testing, Statistical Inference |
| **Visualization** | Tableau, Matplotlib, Seaborn |

---

## 📚 Currently Exploring

- Advanced RAG, retrieval, and LLM evaluation
- Agentic AI and tool-driven LLM systems
- Production ML and MLOps
- ML system design and scalable deployment

---

## 🎓 Education

**University of British Columbia**  
Master of Data Science – Computational Linguistics | 2026

**Langara College**  
Post-Degree Diploma, Data Analytics | 2025

**Lovely Professional University**  
B.Tech, Electronics & Communications Engineering | 2020

---

## 📬 Connect

📧 **Email:** [komalubc@gmail.com](mailto:komalubc@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/komalpreet-kaur-28b3231a0](https://www.linkedin.com/in/komalpreet-kaur-28b3231a0/)
