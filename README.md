  
 
 I'm  **Atiqa**
 
 DevOps & MLOps Enthusiast | 🎓 BS Computer Science Student
 
I am a passionate engineer bridging the gap between Development, Operations, and AI. My focus is on automating workflows, containerizing applications, and wiring up the monitoring that tells you whether any of it actually works.

Currently building CI/CD pipelines, containerizing applications with Docker and Docker Compose, and instrumenting them with Prometheus, Loki, and Grafana.

### 🧰 Tech Stack & Tools

### ☁️ Containers & CI/CD:

- **Docker**
- **Docker Compose**
- **GitHub Actions**

### 📈 Monitoring & Logs

- **Prometheus**
- **Grafana**
- **Loki**
- **Promtail**

### 🧭 Orchestration & Networking:

- **Nomad**
- **Linux**
- **Networking**

### 💻 Programming & Scripting:

- Python
- Bash
- TypeScript
- C++

### 🤖 AI/ML Stack:

- Scikit-Learn
- Pandas
- NumPy
- PyTorch

## 🚀 Featured Projects

### DevOps, Containerization & Monitoring

#### [Soul of Lahore — Containerization & Monitoring](https://github.com/atiqa-ai/soul-of-lahore-containerization-monitoring)
A Next.js 14 application shipped as a production Docker image, with a `/api/health`
endpoint and a full observability stack: Prometheus for scraping, Loki and Promtail
for logs, and Grafana dashboards provisioned automatically from files in the repo.
Tech: Docker, Docker Compose, Next.js, TypeScript, Prometheus, Grafana, Loki.

#### [DevOps Intern — Containerization, CI & Observability](https://github.com/atiqa-ai/devops-intern-final)
An intern project tying together the pieces: a multi-stage Dockerfile, a GitHub
Actions pipeline that boots the app and asserts its Prometheus `/metrics` endpoint
responds, a Nomad job specification for scheduling, and Loki/Promtail/Prometheus
configuration for log and metric collection.
Tech: Docker, GitHub Actions, Prometheus, Loki, Promtail, Nomad, Bash.

#### [CI/CD Pipelines and Dockerization](https://github.com/atiqa-ai/CI-CD-Pipelines-and-Dockerization)
A working pipeline, not just a YAML file. On every push it builds the Docker image,
then runs a genuine integration test — creates a network, starts Redis and the
application together, curls the running service, and tears the whole thing down —
and only then pushes the image to Docker Hub.
Tech: Docker, Docker Compose, GitHub Actions, Redis, Flask.

### Python & Machine Learning

Each of these has a test suite and a CI pipeline that runs it on every push.

#### [AI Speech Subtitles](https://github.com/atiqa-ai/ai-speech-subtitles)
Turns a recorded lecture into Urdu subtitles: extracts audio, transcribes with
Whisper, translates with GPT-4o-mini, and writes SRT, WebVTT, or a dual-language
file. 43 tests and a Docker image in CI.
Tech: Python, Whisper, OpenAI, Docker, GitHub Actions, pytest.

#### [Spam Classifier with Streamlit Web App](https://github.com/atiqa-ai/spam-classifier)
An SMS spam classifier served through a Streamlit interface. 33 tests, including
end-to-end app tests, plus a Docker image whose container healthcheck runs in CI.
Tech: Python, scikit-learn, NLTK, Streamlit, Docker, GitHub Actions.

#### [Geolocation System](https://github.com/atiqa-ai/geolocation-system)
Looks up the public IP address, resolves it to a city and coordinates, and writes
an interactive Folium map with a platform-correct `file://` URL. Handles network
failures and API-level error payloads rather than assuming success.
Tech: Python, Folium, requests, argparse, pathlib.

#### [California Housing Regression](https://github.com/atiqa-ai/california-housing-regression)
A linear-regression study on the California housing dataset with reproducible
outputs committed and no hidden state. The honest finding is that the model is
weak (R² ≈ 0.575) and the README explains why scaling and target clipping matter.
Tech: Python, scikit-learn, Pandas, NumPy, Jupyter.

#### [Voice Assistant](https://github.com/atiqa-ai/voice-assistant)
A voice assistant that opens sites, launches apps, tells the time, and reads
Wikipedia summaries aloud. Refactored so every side effect is injectable, which
made 71 tests possible with no microphone attached.
Tech: Python, pyttsx3, SpeechRecognition, PyAudio, Wikipedia, pytest.

## 📚 What I'm currently learning

- **Infrastructure as Code (IaC): Terraform** — the gap I know I have; no public
  IaC work yet, so treat this as in progress rather than shipped.
- **Orchestration: Kubernetes**
- **MLOps: automating model retraining pipelines**

## 📫 Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/atiqa-mushtaq?utm_source=share_via&utm_content=profile&utm_medium=member_ios)  
- 📧 Email: **catiqa23@gmail.com**  

💭 *"Learning never stops, and every project is a step forward."*
