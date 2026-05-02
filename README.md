<!-- Copy to the LifeofArin profile repo as README.md at the repository root. -->

<div align="center">

### Arin Rajiv Gupta

**Data science, product analytics, and applied AI**

MS Data Science @ University of Maryland (4.0). Open to roles from **framing the problem** through **models, systems, and measurement**.

[Email](mailto:agupta17@umd.edu) · [LinkedIn](https://www.linkedin.com/in/arin-rajiv-gupta/)

</div>

---

Most of my work sits in one lane. I help teams decide what to build or change next, whether that is a funnel, a forecast, a classifier, or an LLM backed workflow. I care about clean data and solid methods, and I care just as much that the output fits how people actually work (dashboards, routing rules, alerts, and plain language summaries). If generative AI is the answer, I want it grounded in evals, guardrails, and how the team will run it tomorrow, not only how it looks in a notebook today.

**Selected impact** (high level. Happy to walk through definitions, baselines, and caveats in conversation.)

| Area | Outcome |
|------|--------|
| LLM triage and routing (UMD) | **~78%** less manual processing and **~35%** fewer unresolved escalations compared to the prior process |
| Edtech GTM and analytics (UMD) | **~29%** weekly engagement lift and **~22%** campaign ROI improvement, with leadership reporting moving from weekly to daily |
| Healthcare claims (Azure) | **~92%** precision on narrative flagging and **~40%** faster claim review on the workflows we measured |
| Defense anomaly detection | **~95%** detection accuracy on a large internal style benchmark and review timelines shortened from about two weeks to about four days for similar briefing packages |
| Energy and ops (Indian Oil) | **1M+** datapoints per day through SQL pipelines and **~40%** better inventory accuracy on the forecasting workstream, with about two weeks forward visibility for procurement |
| English to Hindi NMT research | Transformer at **BLEU 16.48** and **TER 74.01** on **310K** pairs, with dependency reordering applied on **~43%** of test sentences |

*Each percentage is against an explicit baseline (manual process, prior period, or model baseline) for a comparable window or data split.*

---

## Pinned repositories 

| Repo | What it is |
|------|------------|
| [**Real-Time-Bitcoin-Price-Prediction**](https://github.com/LifeofArin/Real-Time-Bitcoin-Price-Prediction) | Time series work with a live style data path |
| [**english-hindi-nmt-source-reordering**](https://github.com/LifeofArin/english-hindi-nmt-source-reordering) | LSTM, attention, and Transformer comparison plus English to Hindi reordering before decode |
| [**Resume chat (fast session recovery)**](https://github.com/abhyansh26/resume-chat-fast-recovery) | Resume editor with AI assisted bullets and durable session state (React, FastAPI, DynamoDB, S3, AWS Lambda behind CloudFront) |



## Technical stack

**Core:** Python (Pandas, NumPy, scikit-learn), SQL, R  

**ML and deep learning:** TensorFlow, PyTorch, Transformers, CNNs, RNNs, sequence models  

**NLP and GenAI:** LangChain, RAG patterns, vector databases, prompt design, OpenAI and Claude APIs  

**Data and infra:** Spark, Databricks, PostgreSQL, MLflow, Docker, AWS, Azure, AKS  

**Analytics and BI:** Power BI, Tableau, A/B tests, funnels, cohorts  

**Collaboration:** Git, CI/CD, working with engineering on scope, handoffs, and what “done” means for a model in production  

---

## What I am looking for

Teams where measurement is serious, where AI is used on real decisions, and where clear writing and spoken explanation matter as much as the notebook. If that sounds like your group, I would be glad to talk.

---

<details>
<summary><b>My approach</b> (expand)</summary>

I start from the decision, not the spreadsheet. I want to know what changes if we are right and what breaks if we are wrong. That order keeps data definitions, model choice, evaluation, and how we package results aligned with the people who actually move budget, staffing, or product priorities.

</details>

<details>
<summary><b>Selected work in more detail</b> (expand)</summary>

### LLM assisted triage and case routing (UMD)

I built routing that connects counseling, testing, and admin through classification, priority, and assignment powered by LLMs. Manual processing dropped by **~78%** and unresolved escalations fell by **~35%** relative to the prior manual routing baseline for the same intake types.

### Product analytics and GTM (Smith School, UMD)

As an ML consultant for an edtech startup I mapped engagement across **50+** U.S. universities, ran cohort segmentation with K-Means, modeled conversion with logistic regression, and helped design A/B tests on paid and organic channels. Weekly engagement rose **~29%** and campaign ROI improved **~22%** against prior period baselines. I also automated pipelines into leadership dashboards so reporting went from weekly to daily and time to decision on ad spend improved by **~60%**.

### Healthcare claims anomaly detection

On Azure Databricks I trained an Isolation Forest model and an NLP classifier on narratives for **250K+** claims. The narrative model reached **~92%** precision on the audit sample we used for validation. I then used LangChain with RAG and a vector database to turn flags into short auditor summaries, deployed on AKS. Measured claim review time fell **~40%** and auditor escalations dropped **~28%** compared to the prior workflow metrics.

### Anomaly detection for defense systems (DRDO, India)

I built SVM based pipelines focused on steganography oriented signals in communication data. The work highlighted concrete vulnerability themes such as payload patterns, weak key reuse, and compression side channels. Detection accuracy on the internal benchmark style dataset (**100K+** records) was **~95%**. I condensed results for senior researchers and cut a typical review cycle from about two weeks to about four days for similar briefing packages.

### Real time operations analytics (Indian Oil)

I processed **1M+** daily datapoints through SQL, shipped a real time Power BI layer with row level security for **500+** analysts across **200+** stations, and built ARIMA style demand forecasts that supported **~40%** better inventory accuracy and about two weeks of forward visibility for procurement.

### Neural machine translation (English to Hindi)

I compared LSTM, Bahdanau attention, and Transformer architectures on **310K** sentence pairs. The Transformer led on **BLEU 16.48** and **TER 74.01**. I added a dependency based reordering step that changed inputs on **~43%** of test sentences and ran structured error analysis that fed the final co authored report.

</details>


