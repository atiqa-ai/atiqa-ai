<!-- Profile README for github.com/atiqa-ai — place this file at the root of the repo atiqa-ai/atiqa-ai -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:3a0ca3,50:7209b7,100:f72585&text=Atiqa%20Mushtaq&fontColor=ffffff&fontSize=56&fontAlignY=36&desc=DevOps%20and%20Cloud%20Computing&descSize=22&descAlignY=58&animation=fadeIn" alt="Atiqa Mushtaq - DevOps and Cloud Computing" width="100%"/>

<a href="https://github.com/atiqa-ai"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=F72585&center=true&vCenter=true&width=700&lines=DevOps+Enthusiast;Cloud+Computing;BS+Computer+Science+Student;Automating+workflows+and+containerizing+applications" alt="Typing SVG"/></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-atiqa--mushtaq-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atiqa-mushtaq?utm_source=share_via&utm_content=profile&utm_medium=member_ios) [![GitHub](https://img.shields.io/badge/GITHUB-atiqa--ai-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/atiqa-ai) [![Email](https://img.shields.io/badge/EMAIL-catiqa23%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:catiqa23@gmail.com) ![Profile Views](https://komarev.com/ghpvc/?username=atiqa-ai&label=PROFILE%20VIEWS&color=7209b7&style=for-the-badge) ![Open to](https://img.shields.io/badge/OPEN%20TO-DevOps%20%C2%B7%20Cloud%20Internships-2EA043?style=for-the-badge)

</div>

> 💬 *I bridge Development, Operations and AI — and I wire up the monitoring that tells you whether any of it actually works.*

---

## 🪪 About Me in a Nutshell

| | |
|---|---|
| **Role** | DevOps Enthusiast · 🎓 BS Computer Science Student |
| **Foundation** | Linux · Bash · Python · Git & GitHub Actions |
| **Focus** | CI/CD pipelines, Docker containerization, observability (Prometheus · Loki · Grafana) |
| **Cloud** | AWS · Azure (basics) |
| **ML** | scikit-learn · Pandas · NumPy · PyTorch · Streamlit apps |
| **Now learning** | Terraform (IaC) · Trivy · Gitleaks |
| **Philosophy** | A pipeline is only real if it *tests* the thing it ships |
| **Open to** | DevOps / Cloud Engineer roles |

---

## 🧱 Building Blocks: My Path in Tech

Every project here started the same way: something worked on my machine, so I asked *"how do I prove it works anywhere — and keep proving it?"*

| Chapter | What happened |
|---|---|
| **01 · Scripts** | Started with **Bash on Linux** — automating user and permission management instead of clicking through it. |
| **02 · Python & ML** | Built classifiers and regressors (spam detection, MNIST, house prices) and learned that an honest metric beats a flattering one. |
| **03 · Containers** | Packaged apps as Docker images, then wrote pipelines that boot the container and *test the running service* before publishing. |
| **04 · Observability** | Added health endpoints, Prometheus metrics, and Loki/Promtail log shipping so failures are visible, not guessed at. |
| **05 · What's next** | Infrastructure as Code with **Terraform**, plus security scanning with **Trivy** and **Gitleaks**. |

---

## 🚦 Every Push Goes Through This

| Stage | What happens | Tools |
|:---:|---|---|
| **1 · Commit** | Code is pushed to GitHub and the workflow starts automatically | `Git` `GitHub Actions` |
| **2 · Test** | Dependencies are installed and the test suite runs | `Python` `pytest` |
| **3 · Build** | The app is packaged as a Docker image | `Docker` `Docker Compose` |
| **4 · Verify** | The container is started and the running service is checked, including Redis integration, health endpoints and `/metrics` | `Redis` `curl` `Prometheus` |
| **5 · Publish** | The image is pushed to Docker Hub, but only if every earlier stage passed | `Docker Hub` |
| **6 · Observe** | Metrics, logs and dashboards show how the service behaves | `Prometheus` `Loki` `Promtail` `Grafana` |

> **My rule:** if a stage fails, nothing ships.

## ⭐ Featured Work

### 🛠️ DevOps, Containerization & Monitoring

<table>
<tr>
<td width="50%" valign="top">

#### 🐳 [Soul of Lahore — Containerization & Monitoring](https://github.com/atiqa-ai/soul-of-lahore-containerization-monitoring)
**Next.js 14 → production Docker image**

A cinematic Next.js 14 app shipped as a **three-stage, non-root Docker image** with a `/api/health` endpoint, Docker health checks, `restart: unless-stopped` auto-start, and a container-monitoring layer.

`Docker` `Docker Compose` `Next.js` `TypeScript` `Monitoring`

</td>
<td width="50%" valign="top">

#### 🧩 [DevOps Intern — Containerization, CI & Observability](https://github.com/atiqa-ai/devops-intern-final)
**Everything wired together**

Multi-stage Dockerfile, a GitHub Actions pipeline that boots the app and **asserts its Prometheus `/metrics` endpoint responds**, a **Nomad** job spec, and Loki/Promtail/Prometheus config.

`Docker` `GitHub Actions` `Prometheus` `Loki` `Promtail` `Nomad` `Bash`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🔁 [CI/CD Pipelines and Dockerization](https://github.com/atiqa-ai/CI-CD-Pipelines-and-Dockerization)
**A working pipeline, not just a YAML file**

On every push it builds the image, then runs a genuine integration test — creates a network, starts **Redis and the application together**, `curl`s the running service, tears it all down — and only then **pushes the image to Docker Hub**.

`Docker` `Docker Compose` `GitHub Actions` `Redis` `Flask`

</td>
</tr>
</table>

### 🤖 Python & Machine Learning

> Each of these ships with a test suite and a CI pipeline that runs on every push.

| Project | What it does | Proof of quality | Stack |
|---|---|---|---|
| [**AI Speech Subtitles**](https://github.com/atiqa-ai/ai-speech-subtitles) | Turns a recorded lecture into **Urdu subtitles** — extracts audio, transcribes with Whisper, translates with GPT-4o-mini, writes SRT / WebVTT / dual-language files | **43 tests** + Docker image built in CI | Python · Whisper · OpenAI · Docker · pytest |
| [**Spam Classifier**](https://github.com/atiqa-ai/spam-classifier) | SMS spam classifier served through a Streamlit UI | **33 tests** incl. end-to-end app tests; container healthcheck runs in CI | scikit-learn · NLTK · Streamlit · Docker |
| [**Voice Assistant**](https://github.com/atiqa-ai/voice-assistant) | Opens sites, launches apps, tells the time, reads Wikipedia summaries aloud | Side effects made injectable → **71 tests**, no microphone needed | pyttsx3 · SpeechRecognition · PyAudio · pytest |
| [**Geolocation System**](https://github.com/atiqa-ai/geolocation-system) | Resolves public IP → city + coordinates → interactive Folium map | Handles network failures and API-level error payloads instead of assuming success | requests · Folium · argparse · pathlib |
| [**California Housing Regression**](https://github.com/atiqa-ai/california-housing-regression) | Linear-regression study with reproducible, committed outputs | Honest result: **R² ≈ 0.575** — the README explains why scaling and target clipping matter | scikit-learn · Pandas · NumPy · Jupyter |

<details>
<summary><b>🧪 More from the lab</b></summary>
<br/>

- 📚 [**ML-Projects**](https://github.com/atiqa-ai/ML-Projects) — Email spam classifier (TF-IDF + Naive Bayes / XGBoost / Random Forest, **up to 97% accuracy**, Streamlit app), MNIST digit classifier, SMS spam classifier with SVM, house-price prediction.
- 🐍 [**pyhton-projects**](https://github.com/atiqa-ai/pyhton-projects) — Python practice: record management, voice assistant, geolocation tools.
- 🐚 [**Bash-Scripting**](https://github.com/atiqa-ai/Bash-Scripting) — *User Automator*: Bash automation for Linux user and permission management.

</details>

---

## 🛠️ Tech Arsenal

### ☁️ Cloud Computing (Basics)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge)

### 📦 Containers & CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### 📈 Monitoring & Logs
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=for-the-badge) ![Promtail](https://img.shields.io/badge/Promtail-F46800?style=for-the-badge)

### 🧭 Orchestration & Networking
![Nomad](https://img.shields.io/badge/Nomad-00CA8E?style=for-the-badge&logo=nomad&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Networking](https://img.shields.io/badge/Networking-4B5563?style=for-the-badge)

### 💻 Programming & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### 🤖 AI / ML
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-154F5B?style=for-the-badge)


### 📚 Currently Learning
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge) ![Gitleaks](https://img.shields.io/badge/Gitleaks-DF3079?style=for-the-badge)

---

## 🎯 Where I Fit

<table align="center">
<tr>
<td align="center" width="25%"><h3>⚙️ DevOps</h3>CI/CD pipelines that build, test, and publish Docker images automatically.</td>
<td align="center" width="25%"><h3>☁️ Cloud Computing</h3>Working knowledge of AWS and Azure basics.</td>
<td align="center" width="25%"><h3>🔭 Observability</h3>Health checks, Prometheus metrics, and Loki log shipping.</td>
<td align="center" width="25%"><h3>🐧 Linux & Automation</h3>Bash and Python scripts that replace repetitive manual work.</td>
</tr>
</table>

---

## 📚 Currently Sharpening

- 🏗️ **Infrastructure as Code — Terraform** *(no public IaC work yet, so this is in progress, not shipped)*
- 🛡️ **Trivy** — vulnerability scanning
- 🔐 **Gitleaks** — secret detection

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=atiqa-ai&theme=tokyonight" alt="GitHub profile details" width="49%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=atiqa-ai&theme=tokyonight" alt="Top languages" width="49%"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=atiqa-ai&theme=tokyonight" alt="Repos per language" width="49%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=atiqa-ai&theme=tokyonight" alt="GitHub stats" width="49%"/>

<img src="https://ghchart.rshah.org/7209b7/atiqa-ai" alt="Contribution graph" width="100%"/>

</div>

---

## 🤝 Let's Build Something Reliable

I'm looking for **DevOps and Cloud** opportunities where I can ship, test, and observe real systems.

<div align="center">

[![Connect on LinkedIn](https://img.shields.io/badge/CONNECT%20ON%20LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atiqa-mushtaq?utm_source=share_via&utm_content=profile&utm_medium=member_ios) [![Say Hello](https://img.shields.io/badge/SAY%20HELLO-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:catiqa23@gmail.com)

*💭 "Learning never stops, and every project is a step forward."*

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:f72585,50:7209b7,100:3a0ca3&section=footer" width="100%" alt="footer"/>

</div>
