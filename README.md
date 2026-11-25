<div align="center">

# Sushmitha Sudharsan

### Fresher AI/ML Engineer and Data Scientist

</div>

<div align="justify">

I like the part of machine learning that happens *around* the model: where the data comes from, how the pieces connect, and what it takes to ship something people can actually use. I have an MS in Data Analytics Engineering from Northeastern (2026) and a first-author IEEE paper. I've shipped four team projects and I'm building one agent project on my own.

</div>

<div align="center">

**Open to:** full-time roles, remote work and freelance projects<br>
**Where:** Chennai, Bengaluru, London or fully remote (based in Bengaluru, available now)

[Portfolio](https://sushmithasudharsan.github.io/) · [LinkedIn](https://www.linkedin.com/in/sushmitha-sudharsan-2101) · [Email](mailto:sushmitha.sudharsan21@gmail.com) · [IEEE paper](https://ieeexplore.ieee.org/abstract/document/10601997)

</div>

<div align="justify">

---

## What I'm working on right now

**[SkillBridge](https://github.com/SushmithaSudharsan/skillbridge-agent)**: an honest resume checker. Paste a job description, pick a resume, and it tells you whether the job is a realistic target, which skills to learn, and what you already have but your resume hides. I'm building it solo, and I'm now working on the evals and the web demo.

Also learning: Azure Databricks (working towards DP-750), Kubernetes, and what breaks when ML systems hit production.

---

## Projects I'm proudest of

### SkillBridge Agent (solo)
*Can a resume tool be useful without telling people to stuff in keywords?* SkillBridge compares your resume with a job description and recommends what to learn for your current level. It separates a skill gap (go learn it) from a presentation gap (you have it, your resume doesn't show it).
**The design rule:** the AI reads and writes, and Python checks. Every AI claim has to quote the resume or the job description word for word, or it's thrown away. The fit verdict is calculated in code, so the model can't overrule it. Personal details are masked before any AI call, and resumes are never saved.
**Also built in:** fairness tests (swapping name, university or city must not change the result), a per-call cost log, and CI that checks quality on every change.
`Python` `FastAPI` `LangChain` `Gemini` `Pydantic` `Docker` `GitHub Actions` `pytest`
[Code](https://github.com/SushmithaSudharsan/skillbridge-agent)

### Financial Stress Test Platform (team of 6)
*What if the 2008 crisis or COVID happened again?* An end-to-end MLOps platform that stress-tests 100 companies against historical crisis scenarios.
**What I built:** the CI/CD and deployment pipeline. A push to the repo goes to a live model on GCP with no manual steps.
**Result:** under 200 ms p99 latency, with weekly drift monitoring.
`Airflow` `MLflow` `Docker` `FastAPI` `GCP Cloud Run` `Prometheus` `Grafana`
[Case study](https://sushmithasudharsan.github.io/projects/financial-stress-test/) · [Code](https://github.com/Novia-Dsilva/Mlops_Project_FinancialCrises)

### World Cup Analyst Chatbot (team of 3, 48-hour hackathon)
*How do you stop an LLM from making up sports stats?* A ReAct agent over 49K+ matches where the numbers are computed in code, so the model explains results and doesn't invent them.
**What I built:** the data pipeline, validation, FAISS vector store and prompt templates.
`LangChain` `FAISS` `GPT-4o` `Gradio`
[Case study](https://sushmithasudharsan.github.io/projects/world-cup-chatbot/) · [Code](https://github.com/Novia-Dsilva/GenAI_Hackathon_Grp5)

### ICU Mortality & Length-of-Stay Prediction (team of 2)
*Can the first 24 hours predict how long a patient stays in the ICU?* Models trained on MIMIC-IV, roughly 94,000 ICU admissions.
**What I built:** the length-of-stay regression. **Result:** MAE of 0.94–0.96 days against a 1-day target. The mortality model reached 0.90 ROC-AUC.
`Python` `Pandas` `Scikit-learn` `XGBoost`
[Case study](https://sushmithasudharsan.github.io/projects/icu-prediction/) · [Code](https://github.com/SushmithaSudharsan/icu-mortality-prediction-using-ehr-data)

### VisionScript: Image Captioning (team of 4)
*Can a model describe what's actually in an image?* A CLIP-to-GPT-2 captioner, then a BLIP app that does captions, paragraphs and visual Q&A.
**What I built:** the system architecture.
`CLIP` `BLIP` `GPT-2` `PyTorch` `Hugging Face`
[Case study](https://sushmithasudharsan.github.io/projects/visionscript/) · [Code](https://github.com/SimranaSinha/VisionScript-ImageCaptioning-BLIP)

---

## Research

**Learning Behavior Analysis for Personalized E-Learning using EEG Signals**: IEEE, 2024, first author.
I used LSTM-based recurrent networks to detect engagement and fatigue from the EEG signals of 30 participants, reaching 96% accuracy. [Read the paper](https://ieeexplore.ieee.org/abstract/document/10601997)

---

## Experience

**Graduate Teaching Assistant, Data Mining (IE 7275)**, Northeastern University · Jan 2026 – Apr 2026
Mentored 40+ students through the course and graded their assignments and projects.

**Data Analyst Intern**, Whirl Data Inc. · 2023
Built a Python and OpenCV pipeline that scored 10,000+ dashcam frames for image quality, so weak images were caught and better ones went into the next stage of analysis, plate-detection training.

---

## What I work with

| | |
|---|---|
| **Machine learning** | Python, PyTorch, TensorFlow, Scikit-learn, XGBoost |
| **GenAI & agents** | LLMs, RAG, LangChain, FAISS, Hugging Face |
| **Data** | SQL, Pandas, NumPy, ETL |
| **MLOps** | Docker, MLflow, Airflow, CI/CD, FastAPI, Git |
| **Cloud** | GCP, Azure, Databricks |

**Certifications:** [Microsoft Azure Fundamentals (AZ-900)](https://drive.google.com/file/d/1-akk5yvHN2ExvmXFCMbZ097xl4-3Tou-/view?usp=sharing) · [Microsoft Azure AI Fundamentals (AI-901)](https://drive.google.com/file/d/1ecMNnJZd3kwGWYb-fRF_io6c2wt6Pz3F/view?usp=sharing) · [AWS Prompt Engineering](https://drive.google.com/file/d/1J-irIsVJHzZii4gYxT9lY9Xja3zXWgkw/view?usp=sharing) · [AWS Generative AI](https://drive.google.com/file/d/1gVsuCeaJkwSbJZOgCHRIwwR79ZYT0Bmx/view?usp=sharing) · Azure Databricks Data Engineering (DP-750, in progress)

---

## Let's work together

I'm looking for my first full-time role in AI/ML, data science or data analytics, and I'm open to freelance projects too. I do my best work when I can own a real problem, like:

- A model that works in a notebook and now needs to ship.
- A data pipeline that keeps breaking.
- An LLM feature that has to be trustworthy, not just impressive.

</div>

<div align="center">

### Hiring, or have a project in mind?

**Send me a line about the role or the problem, and I'll reply within 2 days.**

[Email me](mailto:sushmitha.sudharsan21@gmail.com?subject=Hello%20Sushmitha) · [Connect on LinkedIn](https://www.linkedin.com/in/sushmitha-sudharsan-2101) · [Download my resume](https://sushmithasudharsan.github.io/assets/Sushmitha_AIML_Resume.pdf) · [See my portfolio](https://sushmithasudharsan.github.io/)

</div>
