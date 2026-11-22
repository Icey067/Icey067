<div align="center">

# Hi, I'm Aaditya 👋

**Software Engineer · ML Systems · Android · Full-Stack**

I build AI-powered systems end to end: streaming ML pipelines, native Android apps and cloud-backed web platforms. I also compete in hackathons.

[![Portfolio](https://img.shields.io/badge/Portfolio-icey--portfolio.vercel.app-0A66C2?style=for-the-badge&logo=vercel&logoColor=white)](https://icey-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-icey07-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/icey07/)
[![Email](https://img.shields.io/badge/Email-Contact_me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@example.com)

📍 New Delhi, India &nbsp;·&nbsp; 💼 Open to internships, full-time roles and collaborations

</div>

---

## ⭐ Flagship: Sentinel, Real-Time Anomaly Detection

**[realtime-mlops-anomaly-detection](https://github.com/Icey067/realtime-mlops-anomaly-detection)** is a streaming anomaly detection service for financial transactions, with the full MLOps loop around the model.

- **Model:** PyTorch autoencoder trained only on normal transactions (unsupervised), exported to ONNX with dynamic INT8 quantization
- **Accuracy:** ROC-AUC **0.94** on the Kaggle credit-card fraud dataset, with 81% recall at the calibrated threshold (trade-offs documented in the repo)
- **Ingestion:** Redis Streams with consumer groups, payload validation and a dead-letter queue
- **Serving:** FastAPI with single and batch prediction, health/readiness probes and Prometheus metrics
- **MLOps:** statistical drift monitoring (KS-test + Wasserstein distance) that triggers a retraining pipeline tracked in MLflow
- **Ops:** Docker Compose stack with Grafana dashboards and a React telemetry UI
- **Performance:** Locust load test on the `/predict` endpoint, 540+ RPS on a local machine (reproducible script in `benchmarks/`)

`Python` `PyTorch` `ONNX Runtime` `FastAPI` `Redis` `Docker` `Prometheus` `Grafana` `React`

---

## 🏆 Hackathons

| Result | Project | Details |
|---|---|---|
| 🥇 **1st, GDG Hackathon** | [**Lumina**](https://github.com/Icey067/Lumina) | AI lost-and-found platform. Gemini analyses item photos, TomTom Maps handles location, and a matching engine links lost and found reports. React, TypeScript, Firebase. [Live demo](https://campusfind-7a340.web.app) |
| 🏎️ **4th, GrandPrix AI Finals** | [**Silent Co-Driver**](https://github.com/Icey067/Silent-Co-Driver-Prototype) | Pit-wall prototype that extracts stress biomarkers (pitch, energy) from driver radio with Python DSP and combines them with Gemini audio analysis. Node.js, React, TypeScript. |

## 🚀 More Projects

- 🏁 [**TrackShift**](https://github.com/Icey067/TrackShiftPrototype): F1 telemetry and race-strategy engine that separates tire degradation from dirty air, fuel burn and track grip to predict pit windows.
- 🧪 [**Product Synthesis Studio**](https://github.com/Icey067/product-synthesis-studio): local-first AI pipeline that turns market research into ebooks and guides using Ollama, SQLite and Streamlit, with no cloud API keys.
- 🎯 [**SkillScopia**](https://github.com/Icey067/SkillScopia-Automated-ATS-Interview-Prep-System): career-prep platform with local-LLM resume entity extraction and timed technical mock interviews.
- 👾 [**KOrunner-Android**](https://github.com/Icey067/KOrunner-Android): Android game in Kotlin with a custom physics loop and no game engine.
- 👁️ [**Focus-Monitor**](https://github.com/Icey067/Focus-Monitor): real-time attention tracking with OpenCV and MediaPipe (face, eyes and head pose).
- ☁️ [**Fullstack-Weather-App**](https://github.com/Icey067/Fullstack-Weather-App): Kotlin Android client with a Python/Flask REST backend.

## 🛠️ Tech Stack

| | |
|---|---|
| **Languages** | Python · Kotlin · TypeScript · JavaScript · SQL |
| **ML & Data** | PyTorch · ONNX Runtime · MLflow · OpenCV · MediaPipe · Ollama · Gemini API |
| **Backend & Infra** | FastAPI · Flask · Node.js · Express · Redis Streams · Docker · Prometheus · Grafana |
| **Frontend & Mobile** | React · Jetpack Compose · Tailwind CSS · Firebase |

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Icey067&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Icey067&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />

*Building something interesting? I'd love to hear about it.*

</div>
