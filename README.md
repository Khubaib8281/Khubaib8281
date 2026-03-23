<h1 align="center">Muhammad Khubaib Ahmad</h1>

<p align="center">
  <strong>AI Research Engineer &nbsp;·&nbsp; Speech & Language Intelligence &nbsp;·&nbsp; NLP &nbsp;·&nbsp; LLM Engineering</strong>
</p>

<p align="center">
  <a href="https://huggingface.co/Khubaib01">
    <img src="https://img.shields.io/badge/HuggingFace-Khubaib01-FFD21F?style=flat-square&logo=huggingface&logoColor=black" />
  </a>
  <a href="https://linkedin.com/in/muhammad-khubaib-ahmad-">
    <img src="https://img.shields.io/badge/LinkedIn-Muhammad%20Khubaib%20Ahmad-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:muhammadkhubaibahmad854@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=Khubaib8281&style=flat-square&color=1A4F8A" alt="Profile Views" />
</p>

---

## About

I design and build systems at the intersection of rigorous research and production engineering — specializing in **speech intelligence**, **low-resource NLP**, and **LLM systems**. My work spans representation learning, speaker-invariant embeddings, cross-lingual transfer for underrepresented languages, and end-to-end ML deployment.

I work as a solo researcher and engineer — owning the full lifecycle from dataset construction and architecture design through to published preprints, live inference APIs, and open-source libraries.

**Research focus areas:**
- Speaker-invariant speech representations and vocal health modeling
- Emotion and sentiment analysis for Roman Urdu — a low-resource, code-switched language
- LLM observability, hallucination detection, and agentic AI systems
- Applied computer vision for behavioral and safety intelligence

---

## Research & Preprints

> All preprints are publicly available with DOIs. Datasets, model weights, and reproducible artifacts are released alongside each paper.

**Modeling Vocal Fatigue as Embedding-Space Deviation Using Contrastively Trained ECAPA-TDNNs**
`Preprint · DOI: 10.5281/zenodo.18305757 · Under Review: Springer EURASIP Journal on Advances in Signal Processing`
Designed ECAPA-TDNN-VHE from scratch using supervised contrastive loss for speaker-invariant vocal fatigue estimation. Achieved 2.5× accuracy improvement over baseline (78% vs. 36%). Independently collected a multi-language, multi-microphone dataset of 90–100 speakers.

**Roman Urdu Emotion Recognition — First-of-Kind Dataset & XLM-R Model**
`Preprint in preparation · HuggingFace: khubaib01/roman-urdu-emotion-xlmr`
Built the first emotion recognition dataset and model for Roman Urdu — a completely unaddressed NLP task. Curating 134–140K annotated samples. XLM-R fine-tuned to state-of-the-art performance. Dataset and weights publicly released.

**Data-Centric Roman Urdu NLP: Dataset Curation and Model Benchmarking**
`Preprint · DOI: 10.5281/zenodo.18080524`
Built the largest high-quality Roman Urdu sentiment dataset. Trained state-of-the-art classifier achieving 0.84 accuracy and 0.83 Macro-F1.

**Forecast-Based Decision Support System for Mango Malformation Disease**
`Preprint · DOI: 10.5281/zenodo.16090477 · Ahmad, M.K. & Mangana, A.A.`
Time-series forecasting pipeline and smart agriculture decision system demonstrating 50–60% yield improvement through data-driven interventions.

---

## Open-Source Libraries

| Library | Description | Status |
|---|---|---|
| [`auralis-vfs`](https://github.com/Khubaib8281/auralis) | Objective vocal fatigue scoring from raw speech using ECAPA-TDNN-VHE embeddings | Active |
| `voicemonitor` | Real-time continuous voice health monitoring built on the Auralis framework | Active |
| `VocalID` | Voice biometric speaker verification using cosine-similarity embedding evaluation | Active |
| `DataForge` | Multi-agent system for automated data cleaning, EDA, and report generation | Active |

---

## Selected Projects

**QueryVault — LLM Observability & Hallucination Detection Platform**
End-to-end LLM observability system with real-time hallucination detection, structured logging, and a developer dashboard tracking hallucination rate, P50/P95 latency metrics, and error events. Integrated local LLM with few-shot learning. Deployed on Streamlit Cloud.

**Confidence & Posture Analysis — Behavioral Intelligence Application**
Multimodal desktop application combining computer vision and NLP to analyze speaker confidence and posture in real time via webcam using pose estimation and facial cue extraction. Generates structured post-session reports with visualizations of confidence and posture trajectories.

**VigilantEye — Real-Time Violence Detection System**
Real-time violence detection system operating on live camera feed using a fine-tuned deep learning classification pipeline with instant alert triggering and frame-level logging. Optimized for low-latency inference in surveillance environments.

**Auralis — MLOps Framework & REST API for Vocal Health**
Containerized production REST API accepting raw audio and returning normalized vocal fatigue scores via the ECAPA-TDNN-VHE encoder. Deployed on Hugging Face Spaces.

**Roman Urdu Sentiment & Emotion Systems**
State-of-the-art NLP pipelines for sentiment analysis and emotion recognition in Roman Urdu — handling code-switching, slang, and noisy social media text. Models and datasets publicly released on HuggingFace.

---

## Technical Stack

**Core**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)

**Speech & Audio**
![Torchaudio](https://img.shields.io/badge/Torchaudio-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SpeechBrain](https://img.shields.io/badge/SpeechBrain-2C2C2C?style=flat-square)
![ECAPA-TDNN](https://img.shields.io/badge/ECAPA--TDNN-6A1B9A?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-FF6F00?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

**NLP & LLMs**
![Transformers](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=chainlink&logoColor=white)
![XLM-R](https://img.shields.io/badge/XLM--R-0066CC?style=flat-square)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square)

**LLM Engineering**
![LoRA](https://img.shields.io/badge/LoRA-000000?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA-3333FF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_Pipelines-663399?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=flat-square)
![AutoGen](https://img.shields.io/badge/AutoGen-0078D4?style=flat-square)

**Computer Vision**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square)
![CLIP](https://img.shields.io/badge/CLIP-FF7F50?style=flat-square&logo=openai&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FFCC00?style=flat-square&logo=google&logoColor=black)

**Deployment & Infrastructure**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Khubaib8281&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khubaib8281&layout=compact&theme=tokyonight&hide_border=true" height="160" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Khubaib8281&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <sub>All published models, datasets, and libraries are available on this profile and at <a href="https://huggingface.co/Khubaib01">huggingface.co/Khubaib01</a></sub>
</p>
