# 👋 Welcome to My GitHub Profile! ✨

<table>
  <tr>
    <td>
      <img src="me.png" alt="Rutika Kadam" width="500", height="700">
    </td>
    <td valign="top">
      <p>
        I'm <b>Rutika Avinash Kadam</b>, a <b>Data Scientist & Machine Learning Engineer</b> passionate about building intelligent systems that transform complex data into meaningful insights.
        With experience in <b>Data Science & Analytics, Machine Learning and Generative AI</b>, I enjoy solving real-world problems using scalable data-driven solutions and modern AI technologies.
      </p>
    </td>
  </tr>
</table>

---

# 🌟 About Me

- 🎓 **Master’s in Data Science**  
  **Stony Brook University, New York (Graduated: May 2026)**

- 🎓 **Bachelor of Engineering in Information Technology**  
  **Savitribai Phule Pune University, India (Graduated: May 2020)**

- 💡 **Strong foundation in:**
  - Machine Learning
  - Deep Learning
  - Natural Language Processing
  - Large Language Models
  - Generative AI
  - Big Data Systems

- 🔍 Passionate about building **AI-powered systems**, **RAG applications**, and **data pipelines** that turn raw data into actionable insights.

---

# 💼 Professional Experience

## 🧠 Data Scientist (Graduate Researcher)  
📍 Stony Brook Medicine — New York

- Built an end-to-end multi-modal RAG pipeline over 6k+ pages of Department of Public Health medical documents, using
Azure Document Intelligence for layout-aware extraction, GPT-4o for figure captioning, and custom semantic chunking with
adaptive breakpoints.
- Benchmarked FLAT, HNSW, and IVF_FLAT indexes in Milvus on 27k+ multi-modal chunks (p50/p95 latency, Recall@5);
approximate indexes matched accuracy at∼2.5× lower latency.
- Evaluated vector search, MMR reranking, and hybrid Vector+BM25 retrieval with RRF on a synthetic ground-truth set
spanning text, tables, and images, reaching 0.90 Recall@5.
- Built grounded generation with source citations, scoring RAGAS 0.82 faithfulness, 0.82 answer relevancy, 0.93 context
precision, and 0.74 context recall.

---

## 📊 Data Analyst  
📍 Tata Consultancy Services — India

- Performed exploratory data analysis on 1M+ vulnerability records from Qualys VMDR with the Vulnerability
Management team, surfacing trends, anomalies, and threat vectors that guided remediation prioritization.
- Built linear and logistic regression models (scikit-learn) predicting CVSS severity and exploit availability on∼150K findings,
achieving 0.74 ROC-AUC and 22% lower risk exposure vs. FIFO prioritization in backtests.
- Uncovered recurring remediation patterns in 150K+ records via semantic clustering (E5 embeddings + HDBSCAN), then
fine-tuned a DistilBERT classifier on cluster labels (100% held-out accuracy), laying groundwork for automated ticket routing.
- Built a Power BI dashboard with DAX KPIs (CVSS, exploit exposure, MTTR, SLA compliance) that turned alert noise into
clear actions for non-technical stakeholders, showing 64% fewer Jira tickets.
- Achieved 99% patch compliance by automating enterprise remediation workflows with SCCM and PowerShell, boosting
productivity by 25%.

---

# 🚀 Projects

## Electric Vehicle Battery Capacity Prediction

**Tech:** PyTorch, MLOps, Data Version Control, Azure  

- Predicted EV battery capacity from everyday charging data, since direct measurement needs conditions present in only 56% of
sessions; trained PyTorch models on 111K charging windows from 30 vehicles with vehicle-wise 5-fold CV.
- Benchmarked LSTM and Transformer models against baselines over 10 tracked experiments; a linear odometer model won
(RMSE 1.10 vs. 1.69/1.71), and a positional-encoding ablation showed the 21-minute window, not model capacity, was the limit.
- Versioned data and models with DVC across two cloud remotes, tracked experiments in MLflow, and deployed a FastAPI service
via Docker and Azure Container Registry to a public Azure Container Apps endpoint, with CI running 43 tests per push.

---

## Make Your Trip

**Tech:** Agentic AI, LangGraph, MCP, Human-in-the-Loop, Guardrails, PostgreSQL  

- Engineered an agentic AI travel planner with supervisor-led multi-agent routing and MCP-based retrieval, turning
natural-language requests into personalized itineraries covering flights, hotels, weather, and budget.
- Added guardrails, human-in-the-loop approval, and PostgreSQL-backed LangGraph checkpointing for reliability, and cut token
usage by 25% via prompt optimization and tighter context management.

---

## 🏠 Airbnb Price Prediction

**Tech:** Python, scikit-learn, Bagging and Boosting, NLTK

- Analyzed 3.8K Seattle Airbnb listings and ran sentiment analysis on 84K reviews; room type and bedroom count drove price
most, while review sentiment showed no effect.
- Engineered 19 amenity features and benchmarked 6 models (linear, bagging, boosting) with leak-free 10-fold CV,
reaching R2 ≈ 0.51 (RMSE ≈ $62); boosting overfit.

---

# 🛠️ Technical Skills

### 💻 Programming
- Python  
- R  
- SAS  
- SQL (MySQL, PostgreSQL, PL/SQL)  
- C++  
- HTML  
- CSS  

### 🤖 Machine Learning & AI
- scikit-learn  
- TensorFlow  
- PyTorch  
- Hugging Face  
- LangChain  
- LangGraph  

### ☁️ Data Engineering
- Azure Data Factory  
- Azure Data Lake  
- Databricks  
- MS Fabric  
- SSIS  

### 🚀 Deployment & MLOps
- FastAPI  
- Flask  
- Streamlit  
- Gradio  
- Docker  
- Kubernetes  
- MLflow  

### 📊 Data Visualization
- Power BI  
- Tableau  
- Excel  

---

# 🌐 Connect With Me

- 📧 **Email:** rkadam1827@gmail.com
- 💼 **LinkedIn:** https://www.linkedin.com/in/rutika-avinash/
- 💻 **GitHub:** https://github.com/RutikaKadam10 
- 🌍 **Portfolio:** https://rutikakadam10.github.io/Portfolio-Rutika-Kadam/

---

# ⚡ Fun Fact

Beyond Data Science, I enjoy painting, cooking and music. 

---

# ✨ Let’s Build the Future with AI

I’m always open to collaborating on **Data Science, AI, and Machine Learning projects**.  
If you're working on something exciting — let’s connect!
