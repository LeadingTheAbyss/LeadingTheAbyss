<p align="center">
  <img src="https://github.com/user-attachments/assets/9b9894ae-128c-4d15-91d9-e4bfb71267b1" width="100%" alt="Sung Jin-Woo" />
</p>
<h1 align="center">LeadingTheAbyss</h1>
<p align="center">
  <strong>Competitive Programmer</strong><br>
  <strong>AIML Enthusiast</strong><br>
  <strong>Building Scalable Web & AI Systems</strong>
</p>

| [LeetCode](https://leetcode.com/u/leadingtheabyss/) | [CodeChef](https://www.codechef.com/users/LeadingAbyss) | [AtCoder](https://atcoder.jp/users/LeadingTheAbyss) | [X](https://x.com/LeadingTheAbyss) |
| --- | --- | --- | --- |
| [![LeetCode](https://github.com/user-attachments/assets/fa1b3b00-c82a-4a43-a369-7afd57967fe4)](https://leetcode.com/u/leadingtheabyss/) | [![CodeChef](https://github.com/user-attachments/assets/d9331dbc-03ce-4abd-b878-552149bbe543)](https://www.codechef.com/users/LeadingAbyss) | [![AtCoder](https://github.com/user-attachments/assets/278b13df-d8a9-4787-8846-c3ad4220ffde)](https://atcoder.jp/users/LeadingTheAbyss) | [![X](https://github.com/user-attachments/assets/62920387-6b5d-4127-9448-1fb3571624c8)](https://x.com/LeadingTheAbyss) |

---

## GitHub Overview

<div align="center">

<a href="https://github.com/LeadingTheAbyss">
  <img
    src="https://github-readme-stats-fast.vercel.app/api?username=LeadingTheAbyss&show_icons=true&include_all_commits=true&count_private=true&theme=radical"
    height="180"
  />
</a>

<a href="https://github.com/LeadingTheAbyss">
  <img
    src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=LeadingTheAbyss&layout=compact&langs_count=8&theme=radical"
    height="180"
  />
</a>

<br>

<img
  src="https://github-readme-streak-stats.herokuapp.com/?user=LeadingTheAbyss&theme=radical"
  height="180"
/>

---

## LeetCode Activity

<p align="center">
  <img src="https://leetcard.jacoblin.cool/leadingtheabyss?theme=light&font=baloo&ext=heatmap" />
</p>

---

# Technical Skills

### Languages

<p align="centre">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" />
</p>

### Full Stack

<p align="centre">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" width="40" />
</p>

### Databases & Infrastructure

<p align="centre">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/celery/celery-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" />
</p>

### AI / ML

<p align="centre">
  <img src="https://github.com/user-attachments/assets/eda89f10-3877-4fc3-9a16-8e2ac52fbd12" width="40" height="40"/>
  <img src="https://github.com/user-attachments/assets/3b70dbf1-13d7-4933-bc8b-f4e1a9732179" width="40" height="40" />
  <img src="https://github.com/user-attachments/assets/968a55fd-d33e-4db7-aa8b-985fe2f94c5a" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="40" />
</p>

---

## Projects

### TaskFlow : Scalable Notification & Task Processing System
**Python, FastAPI, Celery, Redis, PostgreSQL, Docker, React**

- **Distributed Architecture:** Engineered an event-driven microservices backend decoupling synchronous REST APIs from resource-intensive background workloads, eliminating HTTP bottlenecks during high-throughput data ingestion.
- **Task Orchestration & Message Queuing:** Integrated Redis as an in-memory message broker to manage atomic queue locking, utilizing Celery worker nodes to guarantee at-least-once task execution for external webhook dispatching.
- **Telemetry & Containerization:** Containerized the full end-to-end cluster using Docker Compose and developed a React/Vite frontend dashboard utilizing Tailwind CSS to visualize real-time task throughput and worker loads.

### TruthScope : Evidence-Aware Fact Checking  
**Python, Flask, React, PostgreSQL, OCR, REST API**

- **Claim Verification Pipeline:** Designed and implemented a real-time fact-checking pipeline for verifying user-provided claims from text and images, combining OCR-based claim extraction, backend processing, and structured result storage for later analysis.
- **System Design and Retrieval Workflow:** Built backend APIs in Flask to support text-based claim verification, evidence-driven response generation, and persistence of past fact-check outcomes, enabling comparison and review of earlier verification results.
- **Interface for Analysis:** Developed a React-based interface and dashboard for submitting claims, inspecting verification outputs, and revisiting historical results, making the system usable for iterative experimentation and workflow evaluation.

### Visual Authenticity Classifier System  
**Python, PyTorch, Flask, CNN, Grad-CAM**

- **Model Development:** Trained and evaluated a ResNet18-based binary image classifier for distinguishing authentic and AI-generated images, achieving 95.8% validation accuracy on a balanced dataset of 200K+ samples.
- **Dataset Curation:** Constructed and cleaned a multi-source dataset by removing noisy, low-quality, grayscale, and ambiguous samples, improving data consistency and reducing sources of spurious learning.
- **Interpretability and Deployment:** Integrated Grad-CAM visualizations to inspect prediction-driving regions and deployed the model through a Flask-based inference interface for image upload, prediction, and qualitative analysis of model behavior.
