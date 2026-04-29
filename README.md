<div align="center">

```
░█████╗░██████╗░██╗   ██╗███╗   ██╗ █████╗░██████╗░██╗  ██╗
██╔══██╗██╔══██╗██║   ██║████╗  ██║██╔══██╗██╔══██╗██║  ██║
███████║██████╔╝██║   ██║██╔██╗ ██║███████║██████╔╝███████║
██╔══██║██╔══██╗██║   ██║██║╚██╗██║██╔══██║██╔══██╗██╔══██║
██║  ██║██║  ██║╚██████╔╝██║ ╚████║██║  ██║██████╔╝██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝  ╚═╝╚═════╝ ╚═╝  ╚═╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=SDE+%7C+AI+Engineer+%7C+Full+Stack+Builder;RAG+Pipelines+%7C+LLMs+%7C+GenAI;Final+Year+%40+Manipal+University+Jaipur;Open+to+SDE+%2F+AI+Engineering+Roles+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

---

## 🧬 About Me

```python
class ArunabhSingh:
    def __init__(self):
        self.name        = "Arunabh Singh"
        self.location    = "Varanasi → Jaipur, India 🇮🇳"
        self.degree      = "B.Tech CS — Manipal University Jaipur (July 2026)"
        self.seeking     = ["SDE Roles", "AI Engineering", "Full Stack"]
        self.obsessed_with = ["RAG Pipelines", "LLM Systems", "Intelligent UIs"]

    def current_builds(self):
        return [
            "🏛️  LexAI      — RAG over 50K+ Supreme Court judgments",
            "🌿  SmartMandi  — AI capsicum farming assistant for polyhouse farmers",
            "🎓  Evalo       — Adaptive AI Examination Intelligence Platform",
        ]

    def stack(self):
        return {
            "AI / GenAI"  : ["LLaMA 3.3 70B", "Gemini API", "HuggingFace", "Groq", "RAG"],
            "Vectors"     : ["Pinecone", "SentenceTransformers"],
            "Backend"     : ["FastAPI", "Node.js", "Express.js", "Python"],
            "Frontend"    : ["React", "Flutter", "React Native", "React Three Fiber"],
            "Data Eng"    : ["Apache Kafka", "Apache Airflow", "Pandas"],
            "Infra"       : ["MongoDB", "Firebase", "Docker", "Azure", "n8n"],
        }
```

---

## 🐍 Snake eating my contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arunabh17oo/Arunabh17oo/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Arunabh17oo/Arunabh17oo/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Arunabh17oo/Arunabh17oo/output/github-contribution-grid-snake.svg" />
</picture>

<details>
<summary><b>⚙️ How to activate the snake (one-time setup)</b></summary>

Create `.github/workflows/snake.yml` in this repo:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then go to **Actions → Generate Snake Animation → Run workflow** once manually.

</details>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Arunabh17oo&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=00D9FF&text_color=FFFFFF&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Arunabh17oo&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=FFFFFF&langs_count=8"/>

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Arunabh17oo&theme=radical&hide_border=true&background=0D1117&stroke=00D9FF&ring=00D9FF&fire=FF6B35&currStreakLabel=00D9FF)](https://git.io/streak-stats)

</div>

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Arunabh17oo&theme=react-dark&hide_border=true&bg_color=0D1117&color=00D9FF&line=00D9FF&point=FF6B35)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 🏛️ LexAI — Legal Intelligence Platform
`FastAPI` `Pinecone` `LLaMA 3.3 70B` `SentenceTransformers` `React` `Firebase`

RAG system over **50,000+ Supreme Court judgments**. Sub-2s structured legal analysis with Constitutional Advisory Mode.

- 🔍 Semantic search via SentenceTransformers + Pinecone
- ⚖️ Constitution of India in a dedicated namespace
- 💬 Lawyer-optimized system prompt, citation-backed outputs
- 🔥 Streaming ChatGPT-style frontend on Firebase Hosting

</td>
<td width="50%">

### 🎓 Evalo — Adaptive AI Examination Platform
`React` `TensorFlow.js` `React Three Fiber` `Gemini API` `MongoDB`

AI-powered exam platform with psychometric adaptive scoring and browser-native proctoring.

- 🧠 PASS Engine — real-time difficulty adaptation
- 👁️ AI Proctoring — face + gaze tracking, no server round-trips
- 🌌 3D Knowledge Orbit — R3F-powered learning analytics
- 🤖 Eva AI assistant powered by Gemini API

</td>
</tr>
<tr>
<td width="50%">

### 🌿 Smart Mandi — Farming AI Assistant
`Flutter` `Riverpod` `Firebase` `Hive` `Gemini`

AI capsicum farming assistant for Indian polyhouse farmers — price prediction, disease detection, microclimate recommendations.

- 📊 Mandi price forecasting
- 🦠 Image-based disease detection
- 📱 Offline-first Flutter architecture

</td>
<td width="50%">

### 💼 Enterprise Conversational AI — Infosys Springboard
`React` `Node.js` `HuggingFace` `MongoDB` `JWT`

Production-grade AI platform serving concurrent users at sub-300ms response latency.

- ⚡ 85%+ intent recognition accuracy
- 🔐 25+ RESTful APIs with JWT auth
- 🏢 Multi-tenant workspace support
- 📊 A/B evaluation + model versioning pipelines

</td>
</tr>
</table>

---

## 🛠️ Tech Arsenal

<div align="center">

**AI / GenAI**

![LLaMA](https://img.shields.io/badge/LLaMA%203.3%2070B-0064e0?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F54F3E?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)

**Full Stack**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Data Engineering**

![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Cloud & Infra**

![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

</div>

---

## 💼 Experience

```
2024 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2026
  │
  ├── [May–Jul 2024]  🏢 TietoEVRY — Data Engineering & AI/ML Intern
  │     └── 500K+ healthcare records • Kafka pipelines • Airflow DAG optimization
  │
  ├── [May–Jun 2025]  📊 CodSoft — Data Science Intern
  │     └── Fraud detection • SMOTE • Scikit-learn precision improvement
  │
  └── [Aug–Oct 2025]  🤖 Infosys Springboard — Full Stack + AI Engineer Intern
        └── Enterprise AI platform • 85%+ intent accuracy • sub-300ms latency
```

---

## 📜 Certifications

| Certification | Issuer |
|---|---|
| 🌐 CCNA v7 — Routing & Switching Security | Cisco |
| 🤖 Machine Learning A-Z | Udemy |
| 🗄️ Database Foundations | Oracle Academy |
| 📮 Postman API Fundamentals | Postman |
| ➕ 10+ More | [View on LinkedIn →](https://www.linkedin.com/in/arunabh-singh-63b436287/) |

---

## 📡 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arunabh-singh-63b436287/)
[![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Arunabh17oo)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Arunabh17oo@gmail.com)

</div>

---

<div align="center">

```
"Ship intelligent, scalable products. That's the goal."
```

![Profile Views](https://komarev.com/ghpvc/?username=Arunabh17oo&color=00D9FF&style=flat-square&label=Profile+Views)

</div>
