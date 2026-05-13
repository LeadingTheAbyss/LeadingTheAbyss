<h1 align="center">LeadingTheAbyss</h1>

<p align="center">
  <strong>Competitive Programmer</strong><br>
  <strong>AIML Enthusiast</strong><br>
  <strong>Building Scalable Web & AI Systems</strong>
</p>

<p align="center">
  <a href="https://github.com/leadingtheabyss">
    <img src="https://img.shields.io/badge/GitHub-leadingtheabyss-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://leetcode.com/u/leadingtheabyss/">
    <img src="https://img.shields.io/badge/LeetCode-leadingtheabyss-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
</p>

<p align="center">
  <em>Focused on competitive programming, scalable systems, AI-driven applications, and end-to-end product building.</em>
</p>

---

## Competitive Programming

I actively practice competitive programming with a strong focus on problem solving, implementation quality, and algorithmic depth.

- **LeetCode:** [LeadingTheAbyss](https://leetcode.com/u/leadingtheabyss/)

---

## GitHub Overview

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=leadingtheabyss&label=Profile%20views&color=0e75b6&style=flat" alt="views" />
</p>


<p align="center">
  <img src="https://streak-stats.demolab.com?user=leadingtheabyss&hide_border=true" />
</p>

---

## LeetCode Activity

<p align="center">
  <img src="https://leetcard.jacoblin.cool/leadingtheabyss?theme=light&font=baloo&ext=heatmap" />
</p>

---

## Technical Skills

<h3 align="center">Tech Stack</h3>

<h4 align="center">Languages</h4>
<p align="center">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

<h4 align="center">Frontend</h4>
<p align="center">
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
</p>

<h4 align="center">Backend & APIs</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
</p>

<h4 align="center">Databases & Cache</h4>
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-D82C20?style=for-the-badge&logo=redis&logoColor=white" />
</p>

<h4 align="center">AI / ML & Computer Vision</h4>
<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Tesseract-4285F4?style=for-the-badge&logo=google&logoColor=white" />
</p>

<h4 align="center">DevOps & Tools</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
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
