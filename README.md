<h1 align="center">Hi, I'm Sagarika Pandey 👋</h1>

<p align="center">
  <strong>Software Engineer · Seattle, WA</strong><br/>
  MS Computer Software Engineering · Northeastern University<br/>
  <em>Building cloud-native systems, AI pipelines, and full-stack applications</em>
</p>

<p align="center">
  <a href="https://linkedin.com/in/sagarika-p-8881ab114">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:sagarikapandey1702@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-January%202026-brightgreen?style=for-the-badge"/>
</p>

---

## 🚀 Featured Projects

### 🏠 [HomeVault](https://github.com/spandey1702/HomeVault) — Cloud-Native Family Inventory System
> Java · Spring Boot · React · PostgreSQL · AWS ECS Fargate · Terraform · Packer · JWT · AWS SES

Full-stack household inventory manager with family sharing, expiry tracking, and daily email notifications. Infrastructure-as-code across **44 Terraform resources** — multi-AZ VPC, RDS, ALB, ECR, CloudWatch, Secrets Manager. `terraform apply` deploys everything, zero manual console steps.

- JWT auth (jjwt 0.12.3) · household invite system · Spring `@Scheduled` daily alerts via SES
- Role-based item visibility: personal vs. household-scoped queries
- Custom Packer AMIs provision the backend EC2 host; ECS Fargate handles container orchestration

---

### 🍽️ [FoodCamp](https://github.com/spandey1702/FoodCamp) — Food Waste Reduction Platform
> Python · FastAPI · React · PostgreSQL · PyTorch · ResNet-50 · Leaflet/OSM · AWS S3

Platform connecting restaurants with nearby food camps to eliminate surplus food waste. Restaurants upload a photo — a **ResNet-50 model fine-tuned on Food-101** (101 categories) auto-detects the food name. Camps browse a live Leaflet map, claim portions, and mark pickups.

- Partial claiming — multiple camps share one listing until fully claimed
- Auto-release background task — unclaimed portions return to the pool after 4 hours
- Geocoding via Nominatim (OpenStreetMap) — no paid API key needed
- AWS S3 image storage with local `/tmp` fallback for dev (`MOCK_SCAN=true`)

---

### 🤖 [CodeAgent](https://github.com/spandey1702/CodeAgent) — Self-Healing AI Code Pipeline as an MCP Plugin
> Python · Google Gemini · FastMCP · Pydantic

Multi-agent system that takes a plain-English prompt and autonomously **generates → reviews → debugs → deploys** Python code. Exposed as an MCP plugin — one-command install in Claude Desktop, Cursor, or Windsurf. Each agent (Coder, Reviewer, Debugger, Deployer, Explainer) is a separate Gemini instance with a specialised system prompt, exponential-backoff retry, and regex-based code extraction.

```bash
uvx codeagent-mcp          # run as MCP server
python agents/plugin_server.py --cli   # interactive terminal mode
```

---

### ☕ [a2a-java](https://github.com/a2aproject/a2a-java) — Open-Source Contribution
> Java · Kubernetes · Agent2Agent Protocol

Contributed to the official Java SDK for the Agent2Agent (A2A) Protocol — resolved Kubernetes deployment issues and enhanced agent framework reliability.

---

## 🛠 Tech Stack

### Languages
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Frameworks & Libraries
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![CI/CD](https://img.shields.io/badge/-CI/CD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Packer](https://img.shields.io/badge/-Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)

### Databases & Monitoring
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=spandey1702&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=spandey1702&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

## 💼 About Me

- 🎓 **MS Computer Software Engineering** — Northeastern University
- 💼 **SWE Intern @ Aeone Platforms Inc** — API integrations, analytics dashboards, cloud infrastructure
- 🌱 Currently exploring: distributed systems, LLM pipelines, agent frameworks
- 📍 Seattle, WA · Open to remote or hybrid roles
- 📬 [sagarikapandey1702@gmail.com](mailto:sagarikapandey1702@gmail.com)

<p align="center">
  <strong>🟢 Actively seeking full-time SWE roles starting January 2026</strong>
</p>
