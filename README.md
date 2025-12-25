# 👋 Hey there, I'm Rushyanth Nerellakunta!

🚀 **Machine Learning Engineer | AI/ML Engineer | GenAI & Cloud Solutions Builder**

## 🔍 About Me
- 🎓 **M.S. in Applied Data Science**, Indiana University Indianapolis (2025) | GPA: 3.8  
- 💼 **3+ years of experience** building production-grade intelligent systems, from voice-driven browser interfaces to RAG-based Q&A pipelines  
- ☁️ **AWS Certified Machine Learning Engineer – Associate** (Valid Jul 2025 - Jul 2028)  
- 🤖 Expert in **LLM orchestration**, **multi-agent systems**, and **MLOps**, with hands-on experience deploying models using PyTorch, LangChain, and cloud platforms.

---

## 🧠 Technical Skills

**Programming Skills:** C, C++, Python, R, SQL, Bash, UNIX  
**Machine Learning:** Supervised & Unsupervised Learning, Deep Learning (CNN, RNN, Transformers), NLP, Recommendation Systems, PyTorch, TensorFlow, Hugging Face Transformers  
**GenAI & LLMs:** OpenAI, Gemini, Claude, LangChain, LangGraph, Llama, ChromaDB, Pinecone, RAG, Multi-Agent Systems, MCP (Model Context Protocol)  
**Data Analytics:** Exploratory Data Analysis (EDA), Feature Engineering, Statistical Modeling, Hypothesis Testing, A/B Testing, Tableau, Power BI, Matplotlib, Seaborn, Plotly  
**Big Data & Cloud:** Apache Spark, Hadoop, AWS (SageMaker, Lambda, S3, CloudWatch, Cognito), SQL & NoSQL Databases, ETL Pipelines, Data Warehousing (Snowflake, Redshift), Azure ML, GCP Vertex AI  
**MLOps & Deployment:** FastAPI, Docker, Kubernetes, CI/CD, MLflow, Weights & Biases  
**Tools & Version Control:** MATLAB, Git, GitHub, Jenkins, Visual Studio, JIRA

---

## 🚀 Current Role & Impact

### 🤖 AI/ML Engineer @ Kahana Inc (Aug 2025 – Present)
- 🗣️ Built a **voice-first browsing layer** on top of Firefox, enabling users to talk to the browser for navigation and task completion (shopping, job applications, search) instead of manual clicking/typing
- ☁️ Implemented an **AWS Lambda–hosted GenAI gateway** to securely run Deepgram (speech-to-text) and Gemini (intent + reasoning) while isolating API credentials from the client
- ⚡ Added **semantic + request-level caching** (Redis) to reduce duplicate LLM calls, mitigate API rate-limit risk, and stabilize performance under repeated/looping user queries
- 🤖 Created and tested a **multi-agent orchestration system** using Google ADK, decomposing workflows into specialized sub-agents (Shopping, Job Apply, Q&A/Search) with routing + handoffs for multi-step tasks
- 🛡️ Implemented **structured reasoning + tool-use guardrails** (ReAct-style planning/execution) with retrieval/tool validation to reduce off-target responses and hallucination risk
- 🔌 Integrated **MCP (Model Context Protocol)** to standardize tool connectivity and context exchange between the browser layer, agents, and external services
- 🤝 Partnered with product + engineering to translate research prototypes into customer-facing AI capabilities

**Tech Stack:** Python, AWS Lambda, FastAPI, WebSockets, Deepgram API, Gemini, Redis, Google ADK, MCP, Docker, AWS S3, CloudWatch, Cognito

---

## 💼 Previous Experience

### 🧪 Machine Learning Engineer @ COMET Lab, Indiana University (Aug 2024 – May 2025)
- 🔄 Built an **end-to-end Natural Language → SQL Q&A system** by cleaning web-scraped CSV datasets, loading them into a SQL database, and using LangChain + Llama-3.3-70B-Versatile to generate SQL, execute and return results
- 🎯 Implemented **embedding-based retrieval** and stored vectors in local ChromaDB to fetch relevant context (schema snippets, table/column descriptions) before generation
- 📈 Improved **SQL execution accuracy from 78% → 92%** through iterative prompt engineering (one-shot/few-shot exemplars) and structured planning + tool-use prompting (ReAct-style)
- 🛡️ Added **read-only guardrails** (validation + blocklist/allowlist) to prevent destructive statements (DELETE/UPDATE/DROP) and integrated Human-in-the-Loop review for low-confidence requests
- 📊 Built a **post-training evaluation harness with 60+ ground-truth test cases**, reporting Execution Accuracy and Exact Match
- 🎤 Presented research findings and recommendations to technical and non-technical stakeholders, influencing strategic roadmap decisions

**Tech Stack:** Python, SQL, LangChain, ChromaDB, Embeddings, Llama-3.3-70B-Versatile, Local LLMs, RAG, Evaluation, Guardrails, HITL

### 📈 Jr Machine Learning Engineer @ Virgenverse (Feb 2022 – Nov 2023)
- ⚙️ Engineered resilient **ETL pipelines** using Apache Airflow + Python, reducing **data refresh latency by 40%** and ensuring T+1 data availability
- 💬 Built a **sentiment analytics pipeline** with spaCy/NLTK to process **100K+ social/customer posts**, generating actionable insights and dashboards for marketing teams
- 🧪 Designed and executed **A/B and multivariate experiments** to optimize pricing and marketing initiatives, improving conversion rates
- ❄️ Optimized data warehousing in **Snowflake** by migrating legacy stored procedures into efficient SQL transformations, improving **BI/dashboard query performance by 3×**
- ✅ Improved **data quality and reliability** with validation checks, retry logic, and lineage-friendly logging
- 🤝 Collaborated with data engineers, product managers, and marketing teams to translate insights into actionable recommendations

**Tech Stack:** Python, Apache Airflow, SQL, Snowflake, spaCy, NLTK, BI Dashboards

---

## 🛠️ Featured Projects

### 💼 **Advanced Financial RAG System for SEC 10-K Filings** (Dec 2025)
[🔗 GitHub Repository](https://github.com/RushyanthN/RAG-for-Finance.git)
- Built a **production-grade Retrieval-Augmented Generation (RAG) pipeline** for SEC 10-K filings, enabling natural-language Q&A over **200+ pages** of Apple and Tesla annual reports with source-level citations
- Engineered a **multi-modal document ingestion pipeline** using PyMuPDF and pdfplumber to extract narrative text and financial tables, including intelligent year-column alignment for time-series data
- **Benchmarked three embedding models** (Google text-embedding-004, MiniLM, E5-Large) across retrieval accuracy, latency (p50/p90), and confidence scoring
- Implemented **ChromaDB-based semantic vector search** with neighbor chunk expansion and cross-page overlap, reducing context fragmentation and improving **answer completeness by ~30%**
- Integrated **Gemini 2.5 Flash** with JSON-schema-enforced outputs, automated citation extraction, and answer confidence scoring to support audit-ready financial analysis

**Tech Stack:** Python, ChromaDB, Gemini API, PyMuPDF, pdfplumber, Sentence-Transformers, PyTorch, Pandas

### ⚡ **SparkFlow — Streamlined Machine Learning with Apache Spark** (May 2025)
[🔗 GitHub Repository](https://github.com/RushyanthN/SparkFlow---Streamlined-machine-learning-with-Apache-Spark.git)
- Built an **end-to-end distributed ML pipeline** in Apache Spark ML implementing Linear Regression, Logistic Regression, K-Means, and LDA, with automated JSON metrics logging
- Trained a Linear Regression model on a **692-dimensional feature space**, achieving **R² = 0.73, RMSE = 0.26, and MSE = 0.068**
- Developed a binary Logistic Regression classifier achieving **100% accuracy / precision / recall / F1** with **AUC-ROC = 1.0** on the test set
- Implemented K-Means with k comparison (k=2 vs k=3), improving **WSSSE from 0.12 → 0.075 (37.5% better)**
- Built an LDA topic modeling pipeline extracting 10 topics, comparing hyperparameters across k=[5,10], and reporting perplexity for model selection

**Tech Stack:** Python, Apache Spark, PySpark (Spark MLlib), Spark SQL, argparse, JSON metrics logging, Jupyter Notebook, Pandas/NumPy, Git/GitHub

---

## 🎓 Education

**Master of Science, Applied Data Science**  
Indiana University Purdue University Indianapolis | GPA: 3.8/4.0 | May 2025

**Bachelor of Technology, Electronics & Communication Engineering**  
Sreenidhi Institute of Science and Technology, Hyderabad, India | May 2022

---

## 🏆 Certifications
- ☁️ [**AWS Machine Learning Engineer – Associate**](https://www.credly.com/badges/00e0554f-08f5-4514-832f-2731734cecf3/public_url) (Valid Jul 2025 - Jul 2028)

---

## 🧭 Areas I'm Exploring
- Advanced **MLOps & model monitoring** in production environments
- **LLM fine-tuning** for domain-specific applications
- Multi-agent systems and agentic workflows
- Real-time streaming analytics (Kafka + Kinesis)
- Voice-enabled AI interfaces and conversational systems

---

## 🧑‍🤝‍🧑 Open to Collaborate On
- LLM-powered SQL & natural language interfaces
- Scalable real-time ML pipelines
- Cloud-native AI/ML platform architectures
- Multi-agent systems and RAG applications
- Voice-first AI applications

---

## 📬 Connect with Me
- 📧 **Email:** [rushyanth.work@gmail.com](mailto:rushyanth.work@gmail.com)  
- 💼 **LinkedIn:** [nerellakunta-rushyanth](https://www.linkedin.com/in/nerellakunta-rushyanth/)  
- 🐙 **GitHub:** [RushyanthN](https://github.com/RushyanthN)  
- 📍 **Location:** Indianapolis, IN, USA

---

## ⚡ Fun Facts
- 🏸 **Sports enthusiast:** Badminton, Cricket & Chess  
- 📊 Advocate for **data storytelling** & clean architecture  
- ☕ Coffee is my co-pilot — best models are brewed with espresso  
- 🗣️ Building intelligent systems that understand and interact naturally with humans, one voice command at a time!

---

💡 *"Strong collaborator skilled at translating complex AI capabilities into customer-facing products and actionable business insights."*
