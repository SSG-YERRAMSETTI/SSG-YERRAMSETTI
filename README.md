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



</div>

About Me

I build AI systems that move beyond demos and deliver measurable business value.

I'm an AI/ML Engineer specializing in Generative AI, LLM systems, Agentic AI, RAG, and MLOps, with experience building production-grade AI solutions across enterprise environments. My work sits at the intersection of AI engineering, software engineering, cloud infrastructure, and business impact—turning complex AI capabilities into scalable, reliable products.

At Uber, I contribute to real-time ML inference infrastructure supporting ride-demand forecasting with AWS SageMaker, Kubernetes, Python, and LangGraph. I also develop model-routing workflows that evaluate quality, latency, and inference cost across foundation and fine-tuned models to support smarter model-selection decisions.

Previously at KPMG, I built enterprise AI systems that processed 40,000+ legal clause types, reclaimed approximately 1,900 attorney-hours per quarter, reduced audit search time from 45 minutes to under 4 seconds, lowered model degradation incidents from 9 per quarter to 1, and reduced deployment lead time from 8 days to 18 hours.

My projects extend this focus into Agentic AI, LLM evaluation, observability, NL-to-SQL, OCR automation, forecasting, and computer vision. I'm especially interested in the engineering challenges that make AI successful in production: evaluation, hallucination mitigation, observability, model routing, latency, cost optimization, responsible AI, and reliable deployment.

When I'm not building things: cricket, gym, and the occasional sketch.

Experience

Uber — AI/ML Engineer

June 2026 – Current | USA (Remote)

Contribute to a real-time ML inference platform supporting ride-demand forecasting workloads using AWS SageMaker and Kubernetes, with a focus on latency optimization and model-serving infrastructure.

Develop model-routing workflows in Python and LangGraph to evaluate quality, latency, and inference-cost trade-offs across fine-tuned and foundation models including GPT-4, LLaMA, and Mistral.

KPMG — AI Software Engineer

June 2022 – June 2024 | India

Delivered an NLP contract intelligence platform using BERT and GPT-3 fine-tuning that extracted and classified 40,000+ clause types, reclaiming approximately 1,900 attorney-hours per quarter.

Built a production RAG pipeline with Azure OpenAI, Pinecone, embedding models, and semantic search, reducing auditor search time from 45 minutes to under 4 seconds.

Implemented Azure ML, MLflow, automated retraining, and blue/green deployment workflows, reducing model degradation incidents from 9 per quarter to 1.

Engineered anomaly-detection systems with XGBoost and Isolation Forest for enterprise financial datasets.

Containerized 14 ML microservices with Docker and automated CI/CD through GitHub Actions, reducing deployment lead time from 8 days to 18 hours.

Built an internal LLM evaluation harness benchmarking six foundation models against KPMG-specific advisory tasks.

🛠️ Tech Stack

Area

Tools

LLM / GenAI

Large Language Models · LLM Fine-Tuning · RAG · Prompt Engineering · Agentic AI · Multi-Agent Systems · LangGraph · LangChain · LlamaIndex · Hugging Face Transformers · SFT · RLHF · LoRA · QLoRA

ML / Deep Learning

PyTorch · TensorFlow · Scikit-learn · XGBoost · BERT · GPT · Transformer Models · Neural Networks · NLP · Anomaly Detection · Time-Series Forecasting · Model Quantization · Distributed Training

MLOps / Deployment

MLflow · Kubeflow · AWS SageMaker · Vertex AI · Azure Machine Learning · Model Drift Detection · Model Monitoring · CI/CD · Blue/Green Deployment · A/B Testing · Model Serving · vLLM · ONNX

Vector / Retrieval

Pinecone · Weaviate · FAISS · pgvector · Embedding Models · Hybrid Search · Semantic Search

Data Engineering

Apache Spark · Feature Engineering · PostgreSQL · ETL Pipelines · SQL

Cloud

AWS · GCP · Microsoft Azure · Azure OpenAI · AWS Bedrock · GCP Cloud Run · Multi-Cloud Architecture

Infrastructure

Docker · Kubernetes · Terraform · Infrastructure-as-Code · GitHub Actions · FastAPI · Microservices · REST APIs · Grafana · Prometheus · Arize AI

Computer Vision

YOLOv8 · Deep SORT · OpenCV · dlib · MTCNN · EasyOCR · face-recognition

Languages

Python · SQL · Bash · YAML · JavaScript

AI Governance

Responsible AI · LLM Evaluation · LLM-as-Judge · Bias Detection · Hallucination Mitigation · Model Cards · AI Safety · Guardrails

Featured Projects

<table>
<tr>
<td width="50%">

Triage Agent — Autonomous GitHub Issue Management

A LangGraph state machine that handles the full GitHub issue lifecycle without human intervention — classification, assignment, SLA enforcement, audit logging, and auto-close on stale issues.

Business impact: Returns 5–10 hrs/week of engineering overhead back to the team.

LangGraph Agentic AI GitHub API Python State Machine



</td>
<td width="50%">

Real-Time LLM Observability Pipeline

Polls LLM trace data from Arize every minute, evaluates each response with a Vertex AI judge model, and deploys the full pipeline on GCP Cloud Run via Terraform. Multi-cloud: built on AWS SageMaker, runs on GCP.

Business impact: Catches model degradation in minutes, not when a customer complains.

GCP AWS Arize Vertex AI Docker Terraform



</td>
</tr>
<tr>
<td width="50%">

AI-Powered Database Automation

Schema-grounded RAG pipeline that lets anyone query a PostgreSQL database in plain English. The LLM receives live table definitions, foreign keys, and business rules before generating SQL. Runs entirely locally with Ollama + Gemma — no data leaves the machine.

Business impact: Answers in 30s what used to require a Jira ticket and a day's wait.

Ollama Gemma RAG PostgreSQL Streamlit



</td>
<td width="50%">

SmartVend — AI-Powered Vending Management

Full-stack vending operations platform. OCR pipeline reads supplier receipts and updates inventory automatically. Rolling 7-day demand forecast flags machines before they stock out. Profit calculated from actual invoice costs, not estimates.

Business impact: Eliminates manual data entry + targets 15–25% revenue lost to stockouts.

FastAPI React PostgreSQL Supabase OCR Python



</td>
</tr>
<tr>
<td width="50%">

Multi-Camera Live Object Tracking v3.0

Upgraded an open-source tracking system — replaced Darknet/TF 1.14 with YOLOv8, fixed a concurrency bug by giving each camera its own Deep SORT instance, and added vehicle intelligence: color detection, plate OCR, and type classification.

Business impact: One operator monitoring 10+ live feeds with automated event detection.

YOLOv8 Deep SORT FastAPI OpenCV MTCNN EasyOCR



</td>
<td width="50%">

EPIANN — Efficient Person Identification



Two detection pipelines (Haar Cascade + MTCNN), LBPH recognition, and real-time color-coded alerts based on criminal record lookup. Undergraduate thesis published at BVRITHCON-2023 (Springer).

Research: Compared traditional vs deep learning face detection on live video.

TensorFlow OpenCV dlib MTCNN LBPH



</td>
</tr>
</table>

Ongoing Research: CNN-Based Autism Detection via 4D fMRI — 3D CNN on resting-state neuroimaging to classify ASD vs. neurotypical subjects. Research project at UNT. (Repo coming soon)

GitHub Stats

<div align="center">
  <img height="175em" src="https://github-readme-stats.vercel.app/api?username=SSG-YERRAMSETTI&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=C9A84C&icon_color=C9A84C&text_color=ffffff"/>
  <img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SSG-YERRAMSETTI&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=C9A84C&text_color=ffffff"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SSG-YERRAMSETTI&theme=tokyonight&hide_border=true&background=0D1117&stroke=C9A84C&ring=C9A84C&fire=C9A84C&currStreakLabel=C9A84C"/>
</div>

Education & Credentials



Institution

Period

Result

MS Computer Science

University of North Texas, TX

2024 – Present

GPA 3.8 / 4.0

BE CSE (AI & ML)

GIET, JNTU Kakinada, India

2020 – 2024

CGPA 8.0 / 10

Published Research

Efficient Person Identification using Artificial Neural NetworksInternational Conference BVRITHCON-2023 · Published by Springerdoi.org/10.1007/978-981-95-0144-1_25

Certifications

Microsoft Azure AI Engineer Associate — Microsoft (Apr 2023)

AWS Academy: Machine Learning Foundations — Amazon Web Services (Jan 2023)

AWS Academy: Cloud Architecting — Amazon Web Services (Jan 2023)

AWS Academy: Cloud Foundations — Amazon Web Services (Nov 2022)

Python for Data Science — IBM (Jun 2023)

MTA: Introduction to Programming Using Python — Microsoft (Jun 2022)

Let's Connect

I'm actively looking for AI/ML engineering roles — full-time or internship. If you're working on something in LLMs, agentic AI, computer vision, or MLOps, I'd love to connect.

<div align="center">



</div>

<!-- Footer -->

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</div>
