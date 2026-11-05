<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1E3A8A,100:2563EB&height=220&section=header&text=Philippe%20Mugisha&fontSize=50&fontColor=FFFFFF&fontAlignY=36&desc=AI%20%26%20Machine%20Learning%20Engineer%20%C2%B7%20Agentic%20AI%20%C2%B7%20MCP%20%C2%B7%20RAG&descAlignY=56&descSize=17&descColor=CBD5E1&animation=fadeIn" width="100%"/>
</div>

<div align="center">

<a href="https://github.com/Philippe012">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=720&lines=Building+MCP+agents+with+deterministic+evaluation;RAG+systems+over+real+financial+data;Computer+vision+in+production+%E2%80%94+96%25+accuracy;From+trained+model+to+shipped+feature" alt="Typing intro"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/philippe-mugisha-934470272/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://philippe-kappa.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.kaggle.com/philippemugisha"><img src="https://img.shields.io/badge/Kaggle-0F172A?style=for-the-badge&logo=kaggle&logoColor=20BEFF" alt="Kaggle"/></a>
<a href="mailto:mugishaphilippe3@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>

<br/>

<img src="https://img.shields.io/badge/Based_in-Kigali,_Rwanda-1E293B?style=flat-square&labelColor=0B1220" alt="Location"/>
<img src="https://img.shields.io/badge/Currently-AI_%26_Data_Engineer_Intern_%40_Rwanda_Stock_Exchange-1E293B?style=flat-square&labelColor=0B1220" alt="Current role"/>
<img src="https://img.shields.io/badge/Open_to-AI%2FML_Roles-16A34A?style=flat-square&labelColor=0B1220" alt="Open to work"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%" alt="divider"/>

## About

I'm an **AI & Machine Learning Engineer** who builds systems that work outside the notebook. My focus is **agentic AI and MCP systems**, **retrieval-augmented generation**, and **production computer vision**, backed by solid data engineering.

<table>
<tr>
<td width="33%" valign="top">

**Agents & LLM Systems**<br/>
<sub>MCP client/server design, JSON-RPC, tool orchestration, deterministic agent evaluation, reward and verifier design, RAG.</sub>

</td>
<td width="33%" valign="top">

**Machine Learning**<br/>
<sub>Computer vision, NLP, transformers, anomaly detection, Random Forest and ensembles, time-series, full lifecycle to deployment.</sub>

</td>
<td width="33%" valign="top">

**Data Engineering**<br/>
<sub>ETL and validation, Snowflake, data quality, large-scale annotation (CVAT, Segment AI), Power BI, MLflow.</sub>

</td>
</tr>
</table>

<br/>

## Impact at a Glance

<div align="center">

<img src="https://img.shields.io/badge/MCP_Agent_Reward-1.00-2563EB?style=for-the-badge&labelColor=0B1220" alt="Reward"/>
<img src="https://img.shields.io/badge/CV_Accuracy-96%25-2563EB?style=for-the-badge&labelColor=0B1220" alt="Accuracy"/>
<img src="https://img.shields.io/badge/Manual_Review_Cut-~80%25-2563EB?style=for-the-badge&labelColor=0B1220" alt="Review reduction"/>
<img src="https://img.shields.io/badge/Labeled_Images-58K-2563EB?style=for-the-badge&labelColor=0B1220" alt="Images"/>

</div>

<br/>

## Featured Work

<table>
<tr>
<td width="50%" valign="top">

### MCP Agent Evaluation Environment
<sub><code>Python</code> <code>MCP</code> <code>JSON-RPC</code> <code>pytest</code></sub>

A self-contained MCP client/server framework where a coding agent discovers repo context, reads and writes files, runs tests and inspects diffs through controlled tool calls.

- Seed, workspace, golden reference and independent verifier kept separate for tamper-resistant scoring
- 3 benchmark tasks: bug fix, order-state machine, and an O(Q×N) → O(N+Q) optimization
- **Reward 1.00** with 100% test pass rate; full trajectories logged to JSONL

<a href="https://github.com/Philippe012/MCP-Agent"><img src="https://img.shields.io/badge/View_Repository-0F172A?style=flat-square&logo=github&logoColor=white" alt="Repo"/></a>
<img src="https://img.shields.io/badge/Status-Complete-16A34A?style=flat-square" alt="Complete"/>

</td>
<td width="50%" valign="top">

### OperIQ — Enterprise RAG Assistant
<sub><code>FastAPI</code> <code>React</code> <code>Azure OpenAI</code> <code>Vector DB</code></sub>

An AI assistant that connects to company documents, databases and workflows to answer questions, analyze reports and support decisions.

- Pipeline: upload → chunking → embeddings → vector retrieval → LLM
- Azure OpenAI with a local-LLM option for testing
- MCP tool integrations for database access, retrieval and API actions

<img src="https://img.shields.io/badge/Status-In_Development-D97706?style=flat-square" alt="In development"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Real Estate Image Classifier
<sub><code>PyTorch</code> <code>CVAT</code> <code>Pongo Inc</code></sub>

Production computer-vision model that screens listing uploads automatically.

- Trained on **58,000** hand-labeled images (29K / 29K balanced)
- **96%** accuracy, roughly **80%** less manual review
- Owned the full pipeline: collection, labeling, augmentation, evaluation, deployment

<img src="https://img.shields.io/badge/Status-Deployed-16A34A?style=flat-square" alt="Deployed"/>

</td>
<td width="50%" valign="top">

### Fleet Operations: Reactive to Predictive
<sub><code>Scikit-learn</code> <code>Snowflake</code> <code>MLflow</code> <code>Power BI</code></sub>

Predictive maintenance analytics on **336,776** NYC Flights records.

- Ensemble anomaly detection plus Random Forest, tracked in MLflow
- Data modeled in a Snowflake warehouse; risk mapped with Folium
- Power BI dashboards to flag high-risk assets early

</td>
</tr>
<tr>
<td width="50%" valign="top">

### AGI Cognitive Benchmarking
<sub><code>Kaggle</code> <code>Benchmark Design</code></sub>

Led **AfriCogniBench**, an 1,800-item metacognition benchmark for Kaggle's *Measuring Progress Toward AGI* competition, built on a framework covering learning, metacognition, attention, executive function and social cognition.

<a href="https://www.kaggle.com/philippemugisha"><img src="https://img.shields.io/badge/Kaggle_Profile-0F172A?style=flat-square&logo=kaggle&logoColor=20BEFF" alt="Kaggle"/></a>

</td>
<td width="50%" valign="top">

### Agriculture & Livestock AI
<sub><code>Transformers</code> <code>Time-Series</code></sub>

- **Avocado AI** — NLP chatbot giving smallholder farmers seeding schedules, crop advice and disease guidance
- **Girinka AI** — predictive model for Rwanda's One Cow per Family program, forecasting productivity and flagging early disease risk

</td>
</tr>
</table>

<br/>

## Experience

| Role | Organization | Period |
|:--|:--|:--|
| **AI & Data Engineer Intern** — RAG over stocks, bonds and coupons data; data pipelines; system documentation | Rwanda Stock Exchange | Sep 2026 – Present |
| **AI & ML Engineer** — moved a clinical assistant from static questionnaire to LLM-based extraction aligned with the IMCI protocol | Gidion (Clinical AI) | Jun – Jul 2026 |
| **Founder & AI/ML Lead** — AI-verified renter platform; built the CV model, backend, frontend and cloud pipeline | Pongo Inc | 2025 – May 2026 |
| **Software Engineer Intern** — AI + IoT milk-tracking system; Vuba booking platform | Hanga Hub Community | Jul – Sep 2024 |
| **Project Lead & Developer** — farm management app, cross-functional team | AgriTech Harvest Hub | 2024 |

<br/>

## Competitions & Recognition

- **Winner** — AI for Public Good Hackathon, UR UNIPOD (2026)
- **Google Gemma 4 Developer Agent Competition** — coding-agent track, ongoing
- **Kaggle: Measuring Progress Toward AGI** — AfriCogniBench lead
- **micro1 Frontier Engineering Challenge** · **NandaTown SkillMD** (NandaHack x HCLTech)

<br/>

## Tech Stack

<div align="center">

<sub><b>AI · AGENTS · ML</b></sub><br/>
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,opencv&theme=dark" alt="ML stack"/>
<br/>
<img src="https://img.shields.io/badge/MCP-0F172A?style=flat-square" alt="MCP"/>
<img src="https://img.shields.io/badge/RAG-0F172A?style=flat-square" alt="RAG"/>
<img src="https://img.shields.io/badge/LlamaIndex-0F172A?style=flat-square" alt="LlamaIndex"/>
<img src="https://img.shields.io/badge/Hugging_Face-0F172A?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="HF"/>
<img src="https://img.shields.io/badge/Azure_OpenAI-0F172A?style=flat-square&logo=microsoftazure&logoColor=0078D4" alt="Azure OpenAI"/>
<img src="https://img.shields.io/badge/MLflow-0F172A?style=flat-square&logo=mlflow&logoColor=0194E2" alt="MLflow"/>

<br/><br/>

<sub><b>DATA</b></sub><br/>
<img src="https://img.shields.io/badge/Snowflake-0F172A?style=flat-square&logo=snowflake&logoColor=29B5E8" alt="Snowflake"/>
<img src="https://img.shields.io/badge/Apache_Kafka-0F172A?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka"/>
<img src="https://img.shields.io/badge/Power_BI-0F172A?style=flat-square&logo=powerbi&logoColor=F2C811" alt="Power BI"/>
<img src="https://img.shields.io/badge/Pandas-0F172A?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/CVAT-0F172A?style=flat-square" alt="CVAT"/>
<img src="https://img.shields.io/badge/SQL-0F172A?style=flat-square&logo=mysql&logoColor=4479A1" alt="SQL"/>

<br/><br/>

<sub><b>ENGINEERING & INFRASTRUCTURE</b></sub><br/>
<img src="https://skillicons.dev/icons?i=fastapi,django,react,nextjs,ts,cpp,postgres,docker,kubernetes,git&theme=dark" alt="Engineering stack"/>

</div>

<br/>

## Education & Certifications

**BSc, Computer and Software Engineering** — University of Rwanda, College of Science and Technology

- **Global Data Science Program** — GCI World, Matsuo-Iwasawa Lab, University of Tokyo (JICA) · *selected from 25,000+ applicants* · 2026
- **LFD259 Kubernetes for Developers** and **LFS250 Kubernetes & Cloud Native Essentials** — The Linux Foundation · 2025
- **AI & ML Advanced (DTP)** — IHS Towers / Ministry of ICT & Innovation, Rwanda · 2025
- **Data Labelling & Annotation for AI** — DataLens Africa · 2026

<br/>

## GitHub Activity

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Philippe012&show_icons=true&include_all_commits=true&count_private=true&theme=transparent&hide_border=true&bg_color=0B1220&title_color=3B82F6&icon_color=3B82F6&text_color=CBD5E1&ring_color=2563EB" alt="Stats"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Philippe012&theme=transparent&hide_border=true&background=0B1220&stroke=1E3A8A&ring=2563EB&fire=3B82F6&currStreakNum=FFFFFF&currStreakLabel=3B82F6&sideNums=FFFFFF&sideLabels=CBD5E1&dates=94A3B8" alt="Streak"/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Philippe012&bg_color=0B1220&color=CBD5E1&line=2563EB&point=FFFFFF&area=true&area_color=1E3A8A&hide_border=true&custom_title=Contribution%20Activity" alt="Activity graph"/>

</div>

<br/>

## Let's Build Something

<div align="center">

I'm open to **AI/ML engineering roles**, **agent and evaluation work**, and **RAG or data platform projects**.

<br/>

<a href="mailto:mugishaphilippe3@gmail.com"><img src="https://img.shields.io/badge/mugishaphilippe3@gmail.com-0F172A?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email"/></a>
<a href="https://www.linkedin.com/in/philippe-mugisha-934470272/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Philippe012&color=2563EB&style=flat-square&label=Profile+Views" alt="Views"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,50:1E3A8A,100:0B1220&height=120&section=footer" width="100%"/>
