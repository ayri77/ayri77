# Pavlo Borysov

ML & Integration Engineer in Hamburg. Systemintegration, Datenplattformen und angewandte KI.

[English version](https://github.com/ayri77)

Ich entwickle Integrationen, Datenpipelines und LLM-gestützte Anwendungen, überwiegend in Python. In meiner aktuellen Position bei IT-Dienstleistungen K. Rozankovic (seit 09/2025) sind das ERPNext/Frappe-Anwendungen, eine ERPNext–Microsoft-365-Integration über Microsoft Graph, n8n-Workflows und Automatisierung mit Dynamics 365 / Power Platform. Von 2011 bis 2024 habe ich Softwareentwicklungsabteilungen bei UkrLandFarming, StarLightMedia und Astarta geleitet: eine verteilte ERP-Landschaft mit über 200 Datenbankinstanzen, eine Analytics-Plattform auf Microsoft Synapse und Power BI mit täglich über 100 Nutzern, sechs Teams mit über 30 Fachkräften. Bei LLM-Anwendungen halte ich mich an eine Regel: Das Modell schlägt vor, deterministischer Code prüft, ein Mensch gibt frei.

Ich arbeite seit über 25 Jahren in der Unternehmens-IT. Derzeit absolviere ich ein Masterstudium in Informatik (Woolf / GoIT Neoversity); 2025 habe ich das Applied Data Science Program von MIT Professional Education abgeschlossen.

## Ausgewählte Projekte

**[AI Data Enrichment Studio](https://github.com/ayri77/ai-data-enrichment-studio)** — MVP, Abschlussprojekt des Masterkurses Generative and Agentic AI (2026).
Ein Sprachmodell plant die Anreicherung einer Excel-Tabelle als validierten Graphen registrierter Operationen; deterministisches Python führt den Plan gegen offene Quellen aus (Open-Meteo, Wikidata); mehrdeutige Treffer gehen in eine manuelle Prüfung; jeder Wert trägt seine Quelle in einem JSON-Audit. Drei Aufgaben, ein Modellanbieter, kein Produktivsystem. Python, FastAPI, Pydantic, OpenAI API; die Weboberfläche wurde mit einem KI-Coding-Assistenten erstellt.

**[Churn ML Experiment Platform](https://github.com/ayri77/neoversity-ml-final/tree/feature/prepared-dataset-pipeline-v1)** — Kursprojekt im Masterstudium (2026), Kaggle Telecom Churn.
Reproduzierbare Experimente: Dataset-Registry mit Herkunft und Hashes, wiederholte Kreuzvalidierung, Modellvergleich auf Out-of-Fold-Vorhersagen, Blending, ein Streamlit-Kontrollpanel. Bester verifizierter Kaggle Public Score 0,9112; interne Balanced Accuracy 0,8964 (Standardabweichung 0,0004).

**[Shinkansen Travel Experience Prediction](https://github.com/ayri77/shinkansen-travel-experience)** — Platz 1 im Hackathon des MIT Applied Data Science Program (2025).
ML-Pipeline für tabellarische Daten mit Feature Engineering von 24 auf 93 Merkmale, Boosted-Tree-Modellen und AutoGluon; 96,245 % Testgenauigkeit.

**[Facial Emotion Recognition](https://github.com/ayri77/FacialEmotionRecognition)** — Capstone-Projekt des MIT Applied Data Science Program.
CNN für vier Emotionsklassen mit Hyperparameter-Optimierung, 79,69 % Validierungsgenauigkeit, Streamlit-Demo mit Webcam-Eingabe. TensorFlow / Keras. Kursprojekt.

**[AWS CI/CD und GitOps Lab](https://github.com/ayri77/neoversity-devops-ci-cd-lab/tree/final-project)** — Laborprojekt des DevOps-Kurses im Masterstudium (2026).
Mit Terraform bereitgestelltes EKS; Jenkins und Kaniko bauen Images nach ECR; Argo CD deployt ein Helm-Chart aus einem separaten [GitOps-Repository](https://github.com/ayri77/neoversity-devops-gitops). Praktische Laborarbeit, kein Produktivbetrieb.

Nicht öffentlich:

- **Career Application Copilot** — eine lokale Anwendung, die aus einer strukturierten Wissensbasis zum Werdegang stellenspezifische Bewerbungsunterlagen erzeugt und jede erzeugte Aussage gegen diese Wissensbasis prüft. Einzelnutzer-System, im aktiven persönlichen Einsatz. Privates Repository, Demonstration auf Anfrage.
- **ERPNext–Microsoft-365-Integration** — Produktivarbeit in meiner aktuellen Position: Python, Microsoft Graph und n8n, bidirektionale Kalendersynchronisation, idempotente Verarbeitung, Logging und automatisierte Fehlerüberwachung. Kein öffentlicher Code.

## Kenntnisse

**Im Beruf eingesetzt:** Python, REST-APIs, SQL und MS SQL Server, Datenmodellierung, Data Warehousing und ETL, Power BI / DAX, Microsoft Synapse, ERP-Integration (ERPNext/Frappe, Microsoft Graph, OData), n8n, Power Automate, Dynamics 365 / Dataverse, Docker, Git, OpenAI API.

**In Projekten und im Studium eingesetzt:** FastAPI, Pydantic, pytest, GitHub Actions, scikit-learn, LightGBM / XGBoost / CatBoost, AutoGluon, Optuna, MLflow, PyTorch, RAG mit FAISS; AWS (EKS, ECR), Terraform, Kubernetes, Helm, Jenkins und Argo CD in Laborprojekten des Studiums.

**In Kursen kennengelernt, noch nicht in einem Projekt angewendet:** LangChain, LangGraph, LoRA-Fine-Tuning, MCP.

Ich arbeite täglich mit KI-Coding-Werkzeugen (Claude Code, Cursor). Anforderungen, Architektur, Review und Tests bleiben in meiner Verantwortung.

## Kontakt

- Hamburg, Deutschland. Arbeitserlaubnis für Deutschland vorhanden.
- Sprachen: Deutsch B2 (telc), Englisch B2, Ukrainisch und Russisch Muttersprache.
- E-Mail: pborisov77@gmail.com
- LinkedIn: https://www.linkedin.com/in/pavlo-borysov-ml
