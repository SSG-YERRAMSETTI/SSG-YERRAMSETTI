<!-- Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Satya%20Sai%20Ganesh%20Yerramsetti&fontSize=40&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20%2F%20ML%20Engineer%20%7C%20LLM%20Systems%20%7C%20Agentic%20AI%20%7C%20Cloud%20MLOps&descAlignY=55&descSize=17" width="100%"/>
</div>

<!-- Typing Animation -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=21&pause=1000&color=C9A84C&center=true&vCenter=true&random=false&width=700&lines=Building+AI+Systems+That+Work+Outside+a+Notebook;LangGraph+Agents+%7C+RAG+Pipelines+%7C+LLM+Observability;YOLOv8+%7C+Deep+SORT+%7C+Real-Time+Computer+Vision;GCP+%7C+AWS+%7C+Terraform+%7C+Multi-Cloud+MLOps;Published+Researcher+%7C+MS+CS+%40+UNT+%7C+GPA+3.8" alt="Typing SVG"/>
</div>

<br/>

<!-- Badges -->
<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=SSG-YERRAMSETTI&color=C9A84C&style=flat-square&label=Profile+Views)](https://github.com/SSG-YERRAMSETTI)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/satya-sai-ganesh-yerramsetti-2a204424b)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-C9A84C?style=flat-square&logo=vercel)](https://YOUR-PORTFOLIO-URL)
[![Research Paper](https://img.shields.io/badge/Published-Springer_BVRITHCON_2023-8A2BE2?style=flat-square&logo=google-scholar)](https://doi.org/10.1007/978-981-95-0144-1_25)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail)](mailto:satyasaiganeshyerramsetti@my.unt.edu)

</div>

---

## 👋 About Me

I'm an AI/ML engineer doing my Master's in Computer Science at the **University of North Texas** (GPA 3.8), and most of my work lives at the intersection of LLM engineering, computer vision, and making AI systems actually reliable in production.

I don't like stopping at proof-of-concept. Most of what's in this GitHub is end-to-end — agents that run autonomously, tracking systems that stream to live dashboards, platforms that non-engineers can actually use, and observability pipelines that catch problems before users do.

Before grad school I spent **15 months as an Applied Scientist intern at CDK Global**, working on ML systems for one of the largest automotive retail platforms in the US. That's where I learned what production ML actually demands. I also published a **facial recognition research paper at a Springer international conference** during undergrad.

When I'm not building things: cricket, gym, and the occasional sketch.

---

## 🛠️ Tech Stack

| Area | Tools |
|------|-------|
| **Large Language Models** | GPT-4 · Gemini · LLaMA · Google Gemma · Ollama |
| **Agentic AI** | LangGraph · Multi-agent workflows · Tool-augmented LLMs |
| **RAG & Retrieval** | FAISS · Schema-grounded RAG · Embedding pipelines · Document chunking |
| **LLM Observability** | Arize · Vertex AI evaluation · LLM-as-a-judge |
| **Computer Vision** | YOLOv8 · Deep SORT · OpenCV · dlib · MTCNN · EasyOCR · face-recognition |
| **Deep Learning** | PyTorch · TensorFlow · Keras · 3D CNN · Transfer Learning (EfficientNet) |
| **Classical ML** | Scikit-learn · XGBoost · LBPH · NumPy · Pandas |
| **Cloud — GCP** | Vertex AI · AutoML · Cloud Run · BigQuery · Artifact Registry · Secret Manager |
| **Cloud — AWS** | SageMaker · S3 · IAM · ECR |
| **MLOps** | Docker · Kubernetes · Terraform · GitHub Actions CI/CD |
| **Backend** | FastAPI · Streamlit · REST APIs · WebSocket · ZMQ |
| **Databases** | PostgreSQL · MySQL · FAISS · Apache Spark · SQL |
| **Languages** | Python · Java · Bash · SQL · Linux |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 🤖 Triage Agent — Autonomous GitHub Issue Management
A LangGraph state machine that handles the full GitHub issue lifecycle without human intervention — classification, assignment, SLA enforcement, audit logging, and auto-close on stale issues.

**Business impact:** Returns 5–10 hrs/week of engineering overhead back to the team.

`LangGraph` `Agentic AI` `GitHub API` `Python` `State Machine`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/triage-agent-ssg)

</td>
<td width="50%">

### 📡 Real-Time LLM Observability Pipeline
Polls LLM trace data from Arize every minute, evaluates each response with a Vertex AI judge model, and deploys the full pipeline on GCP Cloud Run via Terraform. Multi-cloud: built on AWS SageMaker, runs on GCP.

**Business impact:** Catches model degradation in minutes, not when a customer complains.

`GCP` `AWS` `Arize` `Vertex AI` `Docker` `Terraform`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/LLM-Observability-Polling-Pipeline)

</td>
</tr>
<tr>
<td width="50%">

### 🗃️ AI-Powered Database Automation
Schema-grounded RAG pipeline that lets anyone query a PostgreSQL database in plain English. The LLM receives live table definitions, foreign keys, and business rules before generating SQL. Runs entirely locally with Ollama + Gemma — no data leaves the machine.

**Business impact:** Answers in 30s what used to require a Jira ticket and a day's wait.

`Ollama` `Gemma` `RAG` `PostgreSQL` `Streamlit`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/-AI-Powered-Database-Automation)

</td>
<td width="50%">

### 🏪 SmartVend — AI-Powered Vending Management
Full-stack vending operations platform. OCR pipeline reads supplier receipts and updates inventory automatically. Rolling 7-day demand forecast flags machines before they stock out. Profit calculated from actual invoice costs, not estimates.

**Business impact:** Eliminates manual data entry + targets 15–25% revenue lost to stockouts.

`FastAPI` `React` `PostgreSQL` `Supabase` `OCR` `Python`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/SmartVend)

</td>
</tr>
<tr>
<td width="50%">

### 📷 Multi-Camera Live Object Tracking v3.0
Upgraded an open-source tracking system — replaced Darknet/TF 1.14 with YOLOv8, fixed a concurrency bug by giving each camera its own Deep SORT instance, and added vehicle intelligence: color detection, plate OCR, and type classification.

**Business impact:** One operator monitoring 10+ live feeds with automated event detection.

`YOLOv8` `Deep SORT` `FastAPI` `OpenCV` `MTCNN` `EasyOCR`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/multi-camera-tracking)

</td>
<td width="50%">

### 🔬 EPIANN — Efficient Person Identification
[![Published](https://img.shields.io/badge/Published-Springer_2023-8A2BE2?style=flat-square)](https://doi.org/10.1007/978-981-95-0144-1_25)

Two detection pipelines (Haar Cascade + MTCNN), LBPH recognition, and real-time color-coded alerts based on criminal record lookup. Undergraduate thesis published at BVRITHCON-2023 (Springer).

**Research:** Compared traditional vs deep learning face detection on live video.

`TensorFlow` `OpenCV` `dlib` `MTCNN` `LBPH`

[![Repo](https://img.shields.io/badge/GitHub-View_Repo-181717?style=flat-square&logo=github)](https://github.com/SSG-YERRAMSETTI/EPIANN_face-recognition-criminal-detection)

</td>
</tr>
</table>

> 🧬 **Ongoing Research:** CNN-Based Autism Detection via 4D fMRI — 3D CNN on resting-state neuroimaging to classify ASD vs. neurotypical subjects. Research project at UNT. *(Repo coming soon)*

---

## 📈 GitHub Stats

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=SSG-YERRAMSETTI&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=C9A84C&icon_color=C9A84C&text_color=ffffff"/>
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SSG-YERRAMSETTI&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=C9A84C&text_color=ffffff"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SSG-YERRAMSETTI&theme=tokyonight&hide_border=true&background=0D1117&stroke=C9A84C&ring=C9A84C&fire=C9A84C&currStreakLabel=C9A84C"/>
</div>

---

## 📚 Education & Credentials

| | Institution | Period | Result |
|---|---|---|---|
| **MS Computer Science** | University of North Texas, TX | 2024 – Present | GPA **3.8 / 4.0** |
| **BE CSE (AI & ML)** | GIET, JNTU Kakinada, India | 2020 – 2024 | CGPA **8.0 / 10** |

**Published Research**
> *Efficient Person Identification using Artificial Neural Networks*
> International Conference BVRITHCON-2023 · Published by Springer
> [doi.org/10.1007/978-981-95-0144-1_25](https://doi.org/10.1007/978-981-95-0144-1_25)

**Certifications**
- 🏆 Microsoft Azure AI Engineer Associate — Microsoft *(Apr 2023)*
- ☁️ AWS Academy: Machine Learning Foundations — Amazon Web Services *(Jan 2023)*
- ☁️ AWS Academy: Cloud Architecting — Amazon Web Services *(Jan 2023)*
- ☁️ AWS Academy: Cloud Foundations — Amazon Web Services *(Nov 2022)*
- 📊 Python for Data Science — IBM *(Jun 2023)*
- 🐍 MTA: Introduction to Programming Using Python — Microsoft *(Jun 2022)*

---

## 🤝 Let's Connect

I'm actively looking for **AI/ML engineering roles** — full-time or internship. If you're working on something in LLMs, agentic AI, computer vision, or MLOps, I'd love to connect.

<div align="center">

[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ganeshyss0916@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/satya-sai-ganesh-yerramsetti-2a204424b)
[![Portfolio](https://img.shields.io/badge/Portfolio-C9A84C?style=for-the-badge&logo=vercel&logoColor=white)](https://satyasaiganeshyerramsetti.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SSG-YERRAMSETTI)

</div>

<!-- Footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
