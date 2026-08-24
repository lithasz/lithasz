<!-- ============================= HEADER ============================= -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a2622,50:2a8f8a,100:4fc9c4&height=220&section=header&text=Lethania%20Davidson&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=ECE%20%40%20ZJUI%20%7C%20AI%2FML%20Engineering%20%7C%20Hardware%20%2B%20Backend&descAlignY=60&descSize=17&animation=fadeIn" alt="header" />

<a href="https://github.com/lithasz">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=ADFFFB&center=true&vCenter=true&width=820&lines=Building+production+AI+pipelines+that+ship;Bridging+hardware+and+software+engineering;Multilingual+NLP+%26+multimodal+extraction;From+RISC-V+and+FPGA+to+LLM+systems" alt="typing-svg" />
</a>

<br/>

![ECE Student](https://img.shields.io/badge/BEng-Electronic%20%26%20Computer%20Engineering-4fc9c4?style=flat-square&labelColor=0a2622)
![Focus](https://img.shields.io/badge/Focus-AI%20%2F%20ML%20%2B%20Embedded-7fe9e4?style=flat-square&labelColor=0a2622)
![Location](https://img.shields.io/badge/Studying%20in-China%20(ZJUI)-1f6b66?style=flat-square&logo=googlemaps&logoColor=white&labelColor=0a2622)

<br/>

<a href="https://www.linkedin.com/in/lethania-davidson-929206211">
  <img src="https://img.shields.io/badge/LinkedIn-1f6b66?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
</a>
<a href="https://github.com/lithasz">
  <img src="https://img.shields.io/badge/GitHub-1e3a37?style=for-the-badge&logo=github&logoColor=white" alt="github" />
</a>

<br/><br/>

</div>

---

<!-- ============================= ABOUT ============================= -->
## About

I'm an **Electronic & Computer Engineering** student at **ZJUI (Zhejiang University–UIUC Joint Institute)** who works across the full stack, from **RISC-V, FPGA, and embedded systems** up through **backend engineering and applied AI/ML pipelines**. I like taking ambiguous, real-world problems and turning them into systems that actually run in production.

- **AI / ML Engineering** — LLM-based extraction, retrieval-augmented pipelines, multilingual NLP, and multimodal (image/PDF/audio/video) processing.
- **Backend Engineering** — event-driven systems, message queues, vector databases, and observability.
- **Hardware & Embedded** — digital logic, FSM design, RISC-V, FPGA, and microcontroller projects.
- **Product Mindset** — I care about reliability, iteration speed, and shipping things that hold up under real traffic.

> **Open To:** AI/ML & software engineering internships · backend / FDE roles · research collaborations · open-source contributions

---

<!-- ============================= EXPERIENCE ============================= -->
## Experience

### AI Developer Intern · PT Charoen Pokphand Indonesia (CP Group)
`July-August 2026`

Building **Meiji Bot**, a production multilingual WhatsApp chatbot that extracts structured purchase orders from unstructured messages.

- Designed a 40+ node **n8n** workflow merging image OCR, PDF extraction, audio transcription, and text lanes into an LLM extraction agent.
- Built a confidence-band routing system that dispatches structured output to **Kafka** topics based on extraction confidence.
- Integrated **Qdrant** vector search (bge-m3 embeddings) for material-code lookup and **Evolution API** for WhatsApp messaging.
- Debugged complex conversational-state issues: reply-timing bugs, FSM-based order confirmation, and draft continuity across turns.

`n8n` `Kafka` `Qdrant` `LLMs` `Python` `Multimodal NLP`

### LLM Research Intern · Zhejiang University
`Current`

Applied research on large language model systems and evaluation titled "A Physically-Aligned Structural Mechanics Intelligent Solver Based on Multimodal Large Models".

---

<!-- ============================= TECH STACK ============================= -->
## Tech Stack

**Languages**

![Skill Icons](https://skillicons.dev/icons?i=python,cpp,c,ts,js,rust&theme=dark)

**AI / ML & Data**

![Skill Icons](https://skillicons.dev/icons?i=pytorch,fastapi,sklearn&theme=dark)

**Backend & Infra**

![Skill Icons](https://skillicons.dev/icons?i=nodejs,postgres,redis,kafka,docker,grafana,prometheus&theme=dark)

**Hardware & Embedded**

![Verilog](https://img.shields.io/badge/Verilog-1f6b66?style=flat-square&logoColor=white&labelColor=0a2622)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white&labelColor=0a2622)
![FPGA](https://img.shields.io/badge/FPGA-4fc9c4?style=flat-square&labelColor=0a2622)
![ESP32](https://img.shields.io/badge/ESP32-7fe9e4?style=flat-square&logo=espressif&logoColor=white&labelColor=0a2622)

**Tooling**

![Skill Icons](https://skillicons.dev/icons?i=git,linux,vscode&theme=dark)

---

<!-- ============================= AI / ML FOCUS ============================= -->
## AI / ML Focus

<div align="center">

| Domain | Details |
| :--- | :--- |
| **LLM Applications** | Structured extraction, confidence-band routing, prompt & output-contract design |
| **Multilingual NLP** | Cross-language purchase-order extraction, acknowledgement handling |
| **Multimodal Processing** | Image OCR, PDF parsing, audio transcription, video extraction |
| **Deep Learning** | PyTorch MLPs, fraud detection, PR-AUC model selection |
| **Retrieval & Vectors** | Qdrant, bge-m3 embeddings, RAG pipelines |
| **Data / Streaming** | Kafka topics, event-driven workflows, n8n orchestration |

</div>

---

<!-- ============================= FEATURED PROJECTS ============================= -->
## Featured Projects

<details>
<summary><b>🔵 Fraud Detection Deep Learning Pipeline</b></summary>

<br/>

End-to-end fraud detection system built on the Kaggle credit-card fraud dataset, with a served model and full observability.

| Attribute | Detail |
| :--- | :--- |
| **Stack** | PyTorch · FastAPI · Prometheus · Grafana |
| **Approach** | MLP classifier with PR-AUC-driven model selection for class imbalance |
| **Serving** | FastAPI inference endpoint with metrics instrumentation |
| **Repository** | `Dataset-DL-model` |

</details>

<details>
<summary><b>🔵 Backend Portfolio — Observability, Auth & RAG</b></summary>

<br/>

Three production-style backend services built with a focus on reliability and instrumentation.

| Project | Detail |
| :--- | :--- |
| **URL Shortener** | Full Prometheus / Grafana / Jaeger observability stack |
| **JWT Auth API** | PostgreSQL-backed auth with brute-force protection |
| **Local RAG Chatbot** | Query rewriting + Redis-backed chat history |

</details>

<details>
<summary><b>🔵 Hardware Projects</b></summary>

<br/>

Embedded and digital-logic projects spanning FSM design and microcontrollers.

| Project | Detail |
| :--- | :--- |
| **Vending Machine FSM** | Finite state machine design and implementation |
| **Analog Line Follower** | Schmitt-trigger-based sensing and control |
| **Gesture-Controlled Car** | ESP32-based gesture input and motor control |

</details>

<details>
<summary><b>🔵 MLP From Scratch (NumPy)</b></summary>

<br/>

A neural network implemented from first principles as an internship-prep project.

| Attribute | Detail |
| :--- | :--- |
| **Stack** | NumPy (no framework) |
| **Result** | 97.78% accuracy on sklearn digits |
| **Rigor** | Gradient-checking suite that caught real bugs |

</details>

---

<!-- ============================= EDUCATION ============================= -->
## Education

**BEng, Electronic & Computer Engineering** — ZJUI (Zhejiang University–UIUC Joint Institute)

Coursework spans **probability & random processes (ECE 313)**, **digital systems (ECE 314)**, calculus, physics, and Chinese, alongside independent work in embedded systems and applied ML.

---

<!-- ============================= CURRENT FOCUS ============================= -->
## Current Focus

```yaml
current_focus:
  building:
    - Meiji Bot — production multilingual PO-extraction chatbot
    - Multimodal LLM extraction pipelines
  learning:
    - LLM evaluation & agentic architectures
    - Advanced probability & random processes
  exploring:
    - Rust for high-performance backends
    - Vector databases & retrieval at scale
  open_to:
    - AI/ML & software engineering internships
    - Backend / Forward-Deployed roles
    - Open-source contributions
```

---
<!-- ============================= CONTRIBUTION ACTIVITY ============================= -->
## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=lithasz&bg_color=0a2622&color=ADFFFB&line=7fe9e4&point=ffffff&area=true&hide_border=true" alt="activity-graph" />

</div>

---

<!-- ============================= CONNECT ============================= -->
## Connect

<div align="center">

<a href="https://www.linkedin.com/in/lethania-davidson-929206211">
  <img src="https://img.shields.io/badge/LinkedIn-1f6b66?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
</a>
<a href="https://github.com/lithasz">
  <img src="https://img.shields.io/badge/GitHub-1e3a37?style=for-the-badge&logo=github&logoColor=white" alt="github" />
</a>

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:4fc9c4,50:2a8f8a,100:0a2622&height=140&section=footer" alt="footer" />

</div>
