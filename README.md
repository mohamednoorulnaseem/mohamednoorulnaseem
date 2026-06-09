<!-- Header -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a7c5c,100:0d1117&height=220&section=header&text=Mohamed%20Noorul%20Naseem&fontSize=38&fontColor=00e5a0&animation=fadeIn&fontAlignY=42&desc=AI%20Engineer%20%C2%B7%20RAG%20%C2%B7%20LLMs%20%C2%B7%20R%26amp%3BD%20%C2%B7%20Building%20from%20first%20principles&descAlignY=62&descSize=14&descColor=6b7a8f" width="100%"/>
</div>

<!-- Typing animation -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=00E5A0&center=true&vCenter=true&width=700&lines=AI+Engineer+%7C+Building+RAG+%26+LLM+Systems;Obsessed+with+R%26D+%7C+Breaking+things+to+learn;Scalable+Tech+%C3%97+AI-Driven+Growth;Building+from+first+principles" alt="Typing SVG" />
  </a>
</div>

<br/>

<!-- Badges -->
<div align="center">
  <a href="https://www.linkedin.com/in/mohamednoorulnaseem">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:noorulnaseem11@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <img src="https://komarev.com/ghpvc/?username=mohamednoorulnaseem&style=for-the-badge&color=0a7c5c&label=PROFILE+VIEWS"/>
</div>

<br/>

---

<!-- Terminal about section -->
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

```bash
$ whoami
→ Mohamed Noorul Naseem

$ cat about.txt
→ I learn by breaking things.
  Not tutorials. Not courses alone.
  Actual systems — tested, deployed, and sometimes very broken.
  That's how I understand what's really going on under the hood.

$ cat current_mission.txt
→ Building RAG pipelines, LLM systems & backend infra
  that actually run in production — not notebook demos.
  Also thinking about why products win. How AI creates real value.
  Both sides live in my head simultaneously.

$ cat status.txt
→ [●] Building ZynKU — early-stage AI startup
  [●] R&D mode — always
  [●] Open to AI roles & collabs
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

---

<!-- Currently building -->
## ⚡ Current Focus

```python
naseem = {
    "role"       : "AI Engineer × Chief Growth Strategist @ ZynKU",
    "building"   : ["RAG systems with real retrieval accuracy",
                    "LLM fine-tuning for domain-specific problems",
                    "AI infrastructure that ships, not just demos"],
    "exploring"  : ["How AI products go from 0 → first users",
                    "MLOps patterns for small founding teams",
                    "Attention mechanisms from the inside out"],
    "philosophy" : "Being a beginner means asking questions others stopped asking.",
    "superpower" : "AI Engineer who also understands why products win 🎯",
}
```

<br/>

---

<!-- Animated snake contribution graph -->
## 🐍 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mohamednoorulnaseem/mohamednoorulnaseem/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mohamednoorulnaseem/mohamednoorulnaseem/output/github-contribution-grid-snake.svg"/>
    <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/mohamednoorulnaseem/mohamednoorulnaseem/output/github-contribution-grid-snake-dark.svg" width="100%"/>
  </picture>
</div>

<br/>

---

<!-- Projects -->
## 🚀 Projects — Things I've Actually Built

<br/>

<!-- Project 1 -->
<details>
<summary><b>🔵 RAG-Powered Domain Expert System</b> &nbsp;|&nbsp; <code>GenAI · Backend · Production</code></summary>
<br/>

> Ask questions. Get accurate answers from your own documents. No hallucinations.

**The real challenge wasn't building it — it was making retrieval actually work.**

Chunking strategy matters enormously. Chunks too small lose context. Too large dilute relevance. I ran experiments before landing on a configuration that gave accurate answers. The model is only as good as what you retrieve.

```
Architecture:
User Query → Embeddings (text-embedding-ada) → FAISS Vector Store
          → Top-K Retrieval → Context Builder → GPT-4 → Answer
```

**Stack:**
`Python` `FastAPI` `LangChain` `FAISS` `GPT-4` `Docker` `CI/CD`

**What I learned:** Production RAG is 20% model, 80% retrieval engineering.

</details>

---

<!-- Project 2 -->
<details>
<summary><b>🟢 AI Network Intrusion Detection System</b> &nbsp;|&nbsp; <code>ML · Security · Real-time</code></summary>
<br/>

> Real-time anomaly detection on live network traffic. Catches threats as they happen — not after the fact from logs.

**The hard parts:** Feature engineering from raw packets. Class imbalance — attacks are rare events. Making inference fast enough to be useful in real environments.

```
Pipeline:
Live Traffic → Feature Extraction → ML Classifier → Anomaly Score
            → Alert (sub-100ms) → Log & Monitor
```

Benchmarked Random Forest vs XGBoost on precision, recall, and latency before choosing. In security, a false negative (missed attack) is far worse than a false positive — so accuracy alone is the wrong metric.

**Stack:**
`Python` `Random Forest` `XGBoost` `Scikit-learn` `Real-time Inference` `MLOps`

</details>

---

<!-- Project 3 -->
<details>
<summary><b>🟣 Airfoil RL Optimizer</b> &nbsp;⭐ Most Unique&nbsp;|&nbsp; <code>Reinforcement Learning · Physics · R&D</code></summary>
<br/>

> RL applied to aerodynamic shape optimisation. Not a game. Not NLP. Actual physics.

**Most RL projects are games. This one optimises wing cross-sections.**

An RL agent learns to improve airfoil designs through trial and feedback. Traditional methods (CFD simulations) are expensive. I explored whether an agent could find good shapes faster through iterative reward-based learning.

The hardest part: **reward engineering.** You can't design a good reward without understanding aerodynamics — this project forced me to read outside my field. That's the lesson.

```
Agent → Shape Parameters → Aerodynamic Simulation
      → Lift/Drag Reward → Policy Update → Repeat
```

**Stack:**
`Python` `Reinforcement Learning` `Policy Gradients` `Reward Engineering` `NumPy`

**What makes it unique:** Using RL as a general-purpose optimiser, not a gaming technique.

</details>

<br/>

---

<!-- Tech Stack -->
## 🛠️ Tech Stack

<div align="center">

### 🧠 AI / ML / GenAI
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=00e5a0"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>

### ⚙️ Backend / Infra
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

</div>

<br/>

---

<!-- Certifications -->
## 🏆 Certifications

<div align="center">

| 🥇 | Certification | Issuer | Year |
|:---:|---|---|:---:|
| 🌐 | **Foundations of Prompt Engineering** | Amazon Web Services (AWS) | 2026 |
| 📊 | **GenAI Powered Data Analytics Job Simulation** | Tata Group / Forage | 2026 |
| 📈 | **Data Analytics Job Simulation** | Deloitte Australia / Forage | 2026 |
| 🗄️ | **SQL and Relational Databases 101** | Cognitive Class | 2026 |
| 🔗 | **CCNA: Introduction to Networks** | Cisco Networking Academy | 2024 |
| 🤖 | **Automation Explorer Training** | UiPath Academy | 2024 |
| 📣 | **Digital Marketing Certified** | HubSpot Academy | 2026 |

</div>

<br/>

---

<!-- GitHub Stats -->
## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=mohamednoorulnaseem&show_icons=true&theme=tokyonight&hide_border=true&title_color=00e5a0&icon_color=00e5a0&text_color=c9d1d9&bg_color=0d1117"/>
  <img height="180em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=mohamednoorulnaseem&layout=compact&theme=tokyonight&hide_border=true&title_color=00e5a0&text_color=c9d1d9&bg_color=0d1117"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=mohamednoorulnaseem&theme=tokyonight&hide_border=true&background=0D1117&ring=00e5a0&fire=764ba2&currStreakLabel=00e5a0" width="60%"/>
</div>

<br/>

---

<!-- Activity Graph -->
## 📈 Activity Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=mohamednoorulnaseem&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=00e5a0&line=764ba2&point=ffffff" width="100%"/>
</div>

<br/>

---

<!-- Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a7c5c,100:0d1117&height=120&section=footer&text=Let%27s%20build%20something%20real&fontSize=20&fontColor=00e5a0&animation=fadeIn" width="100%"/>

<div align="center">
  <i>"Being a beginner means I ask the questions others stopped asking."</i>
  <br/><br/>
  <a href="https://www.linkedin.com/in/mohamednoorulnaseem">
    <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</div>
