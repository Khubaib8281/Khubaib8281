<h1 align="center">Muhammad Khubaib Ahmad</h1>

<p align="center">
  <strong>AI Research Engineer &nbsp;·&nbsp; Founder, INFERENCE LAB &nbsp;·&nbsp; Low-Resource NLP &nbsp;·&nbsp; Speech Intelligence &nbsp;·&nbsp; LLM Engineering</strong>
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

AI Research Engineer and founder of [INFERENCE LAB](https://www.linkedin.com/company/inference-lab), an applied AI research and engineering organization based in Multan, Pakistan.

My work is end-to-end: dataset construction, architecture design, model development, evaluation, and deployment as usable software. I work across low-resource NLP, speech intelligence, LLM systems, and production AI deployment — owning the full lifecycle from raw data through published research and live inference APIs.

All research is released publicly with reproducible pipelines, deployable inference code, and permanent DOIs.

---

## Research & Publications

> Datasets, model weights, and reproducible artifacts are released alongside each paper.

**RUEmoCorp: A Large-Scale Roman Urdu Corpus and Benchmark Suite for Emotion Classification**
`Under Review — Language Resources and Evaluation (Springer) · Preprint: ResearchSquare (10.21203/rs.3.rs-9759243/v1)`
Construction of the largest Roman Urdu emotion recognition corpus to date. Introduces a cross-institute annotation validation framework with structured annotator roles, multi-round calibration, and inter-annotator agreement measurement. Benchmarks multiple model architectures. Dataset released on HuggingFace and Harvard Dataverse.

**Continuous Vocal Load Monitoring in Professional Voice Users: Development and Occupational Validation of an Automated Assessment Tool**
`Under Review — Journal of Voice`
A deployable occupational health monitoring system for professional voice users. Addresses the gap between laboratory vocal fatigue research and real-world monitoring tools. Validated against occupational use conditions. Built on the ECAPA-TDNN-VHE encoder.

**Modeling Vocal Fatigue as Embedding-Space Deviation Using Contrastively Trained ECAPA-TDNNs**
`Preprint · DOI: 10.5281/zenodo.18366305 · Under Review — Springer EURASIP Journal on Advances in Signal Processing`
Novel framing of vocal fatigue detection as deviation measurement in speaker embedding space. Contrastively trained ECAPA-TDNN-VHE achieves 2.5× improvement over the standard baseline. Multi-language, multi-microphone dataset collected independently across 90–100 speakers.

**Data-Centric Roman Urdu NLP: High-Quality Dataset Curation, Privacy-Preserving Embeddings, and State-of-the-Art Model Benchmarking**
`Preprint · DOI: 10.5281/zenodo.18080524`
Comprehensive data-centric study of Roman Urdu NLP infrastructure gaps. Covers dataset curation methodology, privacy-preserving embedding strategies, and systematic model benchmarking. State-of-the-art sentiment classifier: 0.84 accuracy, 0.83 Macro-F1.

**RUDaSA: Roman Urdu Dataset for Sentiment Analysis — A Large-Scale, Curated Corpus with Privacy-Preserving Embeddings and Competitive Benchmarking of Transformer Models**
`DOI: 10.21203/rs.3.rs-9827763/v1`
RUDaSA is a large-scale Roman Urdu sentiment analysis benchmark that provides privacy-preserving embeddings and evaluates state-of-the-art transformer models to advance NLP research for low-resource and code-mixed languages.

**SecureCipher v2.0: 10-Dimensional Hyperchaotic Image Encryption with ECC Key Generation and Double HMAC Authentication**
`Manuscript in preparation`
Benchmarked against 14 encryption algorithms including DNA+Chaos combinations and AES-based systems. SecureCipher v2.0 scored 100/100 across all evaluation criteria: entropy 7.9993, chi² 244, NPCR 99.61%, with double HMAC authentication and confirmed lossless reconstruction. Next highest-scoring system scored 70/100.

**Forecast-Based Decision Support System for Mango Malformation Disease**
`Preprint · DOI: 10.5281/zenodo.16090477 · Ahmad, M.K. & Mangana, A.A.`
Time-series forecasting pipeline and smart agriculture decision system demonstrating 50–60% yield improvement through data-driven interventions.

---

## Datasets

| Dataset | Description | Access |
|---|---|---|
| **RUEmoCorp** | Largest curated Roman Urdu emotion recognition corpus. Cross-institute annotation validation, structured roles, IAA documentation. | [HuggingFace](https://huggingface.co/Khubaib01) · [Harvard Dataverse](https://doi.org/10.7910/DVN/BPWHOZ) |
| **Roman Urdu Sentiment Corpus** | Largest curated Roman Urdu sentiment corpus. Full annotation schema and IAA statistics released. | [HuggingFace](https://huggingface.co/datasets/Khubaib01/RomanUrdu-NLP-Sentiment-Corpus) · [Harvard Dataverse](https://doi.org/10.7910/DVN/TMXDCL) |

---

## Models

| Model | Description | Access |
|---|---|---|
| **ECAPA-TDNN-VHE** | Vocal Health Encoder. Contrastively trained for speaker-invariant vocal fatigue estimation. 2.5× improvement over ECAPA-TDNN baseline. | [HuggingFace](https://huggingface.co/Khubaib01/ECAPA-TDNN-VHE) |
| **Roman Urdu Emotion Classifier** | XLM-RoBERTa fine-tuned on RUEmoCorp. Current state of the art. Macro F1: 0.9896. | [HuggingFace](https://huggingface.co/Khubaib01/roman-urdu-emotion-xlmr-v2) |
| **Roman Urdu Sentiment Classifier** | XLM-RoBERTa fine-tuned on Roman Urdu Sentiment Corpus. Current state of the art. | [HuggingFace](https://huggingface.co/Khubaib01/roman-urdu-sentiment-xlmr) |

---

## Open-Source Libraries

| Library | Description |
|---|---|
| [`auralis-vfs`](https://github.com/Khubaib8281/auralis) | Vocal fatigue scoring from raw speech using ECAPA-TDNN-VHE embeddings |
| `voicemonitor` | Continuous real-time vocal load monitoring built on the Auralis framework |
| `VocalID` | Voice biometric speaker verification via cosine-similarity embedding evaluation |
| `faker-pk` | Localized synthetic data generation for Pakistan — names, CNICs, addresses, phone numbers |

---

## Selected Projects

**QueryVault — LLM Observability & Hallucination Detection**
End-to-end LLM observability system with real-time hallucination detection, structured logging, and a developer dashboard tracking hallucination rate, P50/P95 latency, and error events.

**Auralis — Production REST API for Vocal Health**
Containerized REST API accepting raw audio and returning normalized vocal fatigue scores via ECAPA-TDNN-VHE. Deployed on HuggingFace Spaces.

**VigilantEye — Real-Time Violence Detection**
Real-time violence detection on live camera feed using a fine-tuned deep learning pipeline with instant alert triggering and frame-level logging. Optimized for low-latency inference.

**Confidence & Posture Analysis — Behavioral Intelligence**
Multimodal desktop application combining computer vision and NLP for real-time speaker confidence and posture analysis via webcam. Generates structured post-session reports.

---

## Inference Lab

[INFERENCE Lab](https://www.linkedin.com/company/inference-lab) is an applied AI research and engineering organization I founded in Multan, Pakistan. The lab conducts original research in low-resource NLP and speech intelligence, builds custom AI systems for deployment, and runs structured engineering education programs for developers who need to move from syntax-level Python to production AI systems.

All lab research is released publicly on HuggingFace and Harvard Dataverse with permanent DOIs and reproducible pipelines.

---

## Technical Stack

**Core**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)

**Speech & Audio**
![SpeechBrain](https://img.shields.io/badge/SpeechBrain-2C2C2C?style=flat-square)
![ECAPA-TDNN](https://img.shields.io/badge/ECAPA--TDNN-6A1B9A?style=flat-square)
![Librosa](https://img.shields.io/badge/Librosa-FF6F00?style=flat-square)
![Torchaudio](https://img.shields.io/badge/Torchaudio-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)

**NLP & LLMs**
![Transformers](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)
![XLM-R](https://img.shields.io/badge/XLM--R-0066CC?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square)

**LLM Engineering**
![LoRA](https://img.shields.io/badge/LoRA-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_Pipelines-663399?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=flat-square)

**Computer Vision**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FFCC00?style=flat-square&logo=google&logoColor=black)

**Deployment & Infrastructure**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

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
