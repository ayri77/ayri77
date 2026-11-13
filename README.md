# Pavlo Borysov

ML & Integration Engineer in Hamburg. Enterprise integration, data platforms and applied AI.

[Deutsche Version](https://github.com/ayri77/ayri77/blob/main/README.de.md)

I build integrations, data pipelines and LLM-assisted applications, mostly in Python. In my current role at IT Services K. Rozankovic (since 09/2025) this means ERPNext/Frappe applications, an ERPNext–Microsoft 365 integration over Microsoft Graph, n8n workflows and Dynamics 365 / Power Platform automation. From 2011 to 2024 I headed software development departments at UkrLandFarming, StarLightMedia and Astarta: a distributed ERP landscape of 200+ database instances, a Microsoft Synapse and Power BI platform used daily by 100+ employees, six teams with 30+ specialists. In LLM applications I keep to one rule: the model proposes, deterministic code validates, a person approves.

I have worked in enterprise IT for more than 25 years. I am currently studying for an MSc in Computer Science (Woolf / GoIT Neoversity) and finished the MIT Professional Education Applied Data Science Program in 2025.

## Selected projects

**[AI Data Enrichment Studio](https://github.com/ayri77/ai-data-enrichment-studio)** — MVP, final project of the MSc course Generative and Agentic AI (2026).
A language model plans the enrichment of an Excel table as a validated graph of registered operations; deterministic Python executes the plan against open sources (Open-Meteo, Wikidata); ambiguous matches go to human review; every value carries its source in a JSON audit. Three tasks, one model provider, not a production system. Python, FastAPI, Pydantic, OpenAI API; the web interface was built with an AI coding assistant.

**[Churn ML Experiment Platform](https://github.com/ayri77/neoversity-ml-final/tree/feature/prepared-dataset-pipeline-v1)** — MSc course project (2026), Kaggle telecom churn.
Reproducible experimentation: dataset registry with lineage and hashes, repeated cross-validation, out-of-fold model comparison, blending, a Streamlit control panel. Best verified Kaggle public score 0.9112; internal balanced accuracy 0.8964 (std 0.0004).

**[Shinkansen Travel Experience Prediction](https://github.com/ayri77/shinkansen-travel-experience)** — rank 1 in the MIT Applied Data Science Program hackathon (2025).
Tabular ML pipeline with feature engineering from 24 to 93 features, boosted-tree models and AutoGluon; 96.245% test accuracy.

**[Facial Emotion Recognition](https://github.com/ayri77/FacialEmotionRecognition)** — MIT Applied Data Science Program capstone.
CNN for four emotion classes with hyperparameter optimisation, 79.69% validation accuracy, Streamlit demo with webcam input. TensorFlow / Keras. Course project.

**[AWS CI/CD and GitOps lab](https://github.com/ayri77/neoversity-devops-ci-cd-lab/tree/final-project)** — MSc DevOps course lab (2026).
Terraform-provisioned EKS; Jenkins and Kaniko build images to ECR; Argo CD deploys a Helm chart from a separate [GitOps repository](https://github.com/ayri77/neoversity-devops-gitops). Hands-on lab work, not production operations.

Not public:

- **Career Application Copilot** — a local application that generates evidence-grounded, vacancy-specific application packages from a structured career knowledge base and audits every generated claim against it. Single-user, in active personal use. Private repository, demonstrable on request.
- **ERPNext–Microsoft 365 integration** — production work in my current role: Python, Microsoft Graph and n8n, bidirectional calendar synchronisation, idempotent processing, logging and automated error monitoring. No public code.

## Skills

**Used in professional work:** Python, REST APIs, SQL and MS SQL Server, data modelling, data warehousing and ETL, Power BI / DAX, Microsoft Synapse, ERP integration (ERPNext/Frappe, Microsoft Graph, OData), n8n, Power Automate, Dynamics 365 / Dataverse, Docker, Git, OpenAI API.

**Used in projects and coursework:** FastAPI, Pydantic, pytest, GitHub Actions, scikit-learn, LightGBM / XGBoost / CatBoost, AutoGluon, Optuna, MLflow, PyTorch, RAG with FAISS; AWS (EKS, ECR), Terraform, Kubernetes, Helm, Jenkins and Argo CD in academic labs.

**Explored in courses, not yet applied in a project:** LangChain, LangGraph, LoRA fine-tuning, MCP.

I work with AI coding tools (Claude Code, Cursor) every day. Requirements, architecture, review and testing stay with me.

## Contact

- Hamburg, Germany. Work authorization: Germany.
- Languages: German B2 (telc), English B2, Ukrainian and Russian native.
- Email: pborisov77@gmail.com
- LinkedIn: https://www.linkedin.com/in/pavlo-borysov-ml
