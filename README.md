<!--
╔═════════════════════════════════════════════════════════════════════════════╗
║         ABINA SELVAMURUGAN — AI SYSTEMS & LLM ARCHITECT PROFILE             ║
║            MINIMALIST OBSIDIAN & TITANIUM · SELF-CONTAINED EDITION          ║
╚═════════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

<img src="https://raw.githubusercontent.com/AbinaSelvamurugan/AbinaSelvamurugan/main/header.svg" width="100%" alt="Abina Selvamurugan — AI Systems Engineer" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Plus+Jakarta+Sans&weight=700&size=19&duration=2800&pause=900&color=f1f5f9&center=true&vCenter=true&multiline=false&repeat=true&width=820&height=45&lines=Building+verifiable+LLM+%26+RAG+architectures;LLM-as-a-Judge+evaluation+%26+rubric+scoring;Neural+speech+enhancement+%26+acoustic+noise+suppression;LLM+Red-Teaming%2C+safety+%26+hallucination+guardrails;Production+model+observability+%26+drift+dashboards;Deep+Audio+AI+%7C+FastAPI+%7C+PyTorch+%7C+Anthropic+Claude)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-AbinaSelvamurugan-111827?style=for-the-badge&logo=github&logoColor=f8fafc&labelColor=030712)](https://github.com/AbinaSelvamurugan)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abina--selvamurugan-111827?style=for-the-badge&logo=linkedin&logoColor=f8fafc&labelColor=030712)](https://www.linkedin.com/in/abina-selvamurugan/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-abinaselvamurugan%40gmail.com-111827?style=for-the-badge&logo=gmail&logoColor=f8fafc&labelColor=030712)](mailto:abinaselvamurugan@gmail.com)

</div>

<br/>

---

### ✦ Architectural Philosophy

> *"Engineering verifiable AI systems where retrieval is strictly bound to source evidence, evaluation is anchored against human ground truth, and real-time audio inference is bounded by deterministic latency."*

I design and build **production-ready AI systems** with a focus on three core pillars:
- **LLM Alignment & Evaluation:** Calibrating automated LLM judges against human consensus using strict schema-validated rubric scoring and bias mitigation.
- **Citation-Grounded Retrieval (RAG):** Eliminating hallucinations by enforcing claim-by-claim citation verification over dense and hybrid vector indexes.
- **Neural Speech & Edge Systems:** Building causal convolutional-recurrent networks for real-time audio noise suppression and embedded edge models.

---

### ✦ System Identity & Research Directives

```typescript
export const engineer: AISystemsProfile = {
  name: "Abina Selvamurugan",
  role: "AI Systems Engineer & Applied Researcher",
  focusAreas: [
    "LLM-as-a-Judge Rubric Benchmarking",
    "Citation-Grounded Technical RAG",
    "Neural Audio & Real-Time Speech AI",
    "LLM Red-Teaming, Safety & Hallucination Guardrails"
  ],
  flagshipSystems: {
    evaluation: "JudgeBench (Anthropic Claude Structured Output)",
    speechAI: "ClearVoice AI (PyTorch Causal CRN + WebSockets)",
    retrieval: "TechnicalDocs AI (ChromaDB + Groq Accelerated Inference)",
    observability: "RAGBench Studio (DeepEval + Trace Telemetry)"
  },
  principles: ["Strict Provenance", "Empirical Calibration", "Zero Unsupported Claims"],
  status: "Available for High-Impact AI Engineering & Applied Research Roles"
};
```

---

### ✦ Technology Ecosystem

<div align="center">

| Domain | Core Stack & Infrastructure |
| :--- | :--- |
| **AI, LLMs & Deep Learning** | PyTorch · TensorFlow · Hugging Face · Anthropic Claude · LangChain · Scikit-Learn · OpenCV · ChromaDB · DeepEval |
| **Audio & Real-Time Signal Processing** | Torchaudio · Librosa · SciPy · DSP Spectral Gating · WebSockets · PESQ / STOI Audio Telemetry |
| **Backend, APIs & Cloud Systems** | FastAPI · Flask · Django · Docker · Kubernetes · AWS · GCP · Linux · Bash · SQLite · PostgreSQL · Redis · MongoDB |
| **Languages, Frontend & DevOps** | Python · TypeScript · JavaScript · C++ · React · Next.js · Tailwind CSS · Git · GitHub Actions · Postman · VS Code |

<br/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,scikitlearn,opencv,fastapi,flask,django,postgres,redis,mongodb,sqlite,docker,kubernetes&theme=dark" alt="AI & Infrastructure Stack" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp,git,github,githubactions,linux,bash,ts,js,cpp,react,nextjs,tailwind,postman&theme=dark" alt="Cloud, Languages & Tooling" />
</p>

</div>

---

### ✦ Flagship Architectures

#### ⚖️ [JudgeBench — Rubric-Based LLM Evaluation Against Human Judgments](https://github.com/AbinaSelvamurugan/llm-as-judge-scoring-system)
> **Empirical Calibration · Structured Outputs · Inter-Rater Reliability**

An automated benchmarking system that evaluates task/answer pairs using explicit, criterion-specific score anchors. Built to investigate and eliminate position bias, length bias, and judge generosity.
- **Structured Output Grading:** Powered by the Anthropic Claude API (`client.messages.parse` with Pydantic JSON schema).
- **Inter-Rater Analytics:** Measures human-judge agreement with sample counts, confidence intervals and Cohen's kappa, reporting `null` rather than a fabricated value when no independent human annotations exist.
- **Auditability:** Retains immutable adjudication histories and rubric versions in SQLite.
- **Stack:** `Python 3.12` · `Anthropic Claude SDK` · `FastAPI` · `SQLite` · `Pydantic`

---

#### 🎙️ [ClearVoice AI — Real-Time Neural Speech Enhancement](https://github.com/AbinaSelvamurugan/ai-noise-suppression-for-online-consultations)
> **Causal Convolutional-Recurrent Network (CRN) · Spectral Gating · Streaming Over WebSockets**

A speech-enhancement platform pairing classical spectral gating with a trainable compact deep causal CRN to reduce acoustic noise in live consultations without clipping quiet consonants.
- **Deep Acoustic Pipeline:** Dual-stage enhancement processing 16 kHz mono streams.
- **Full-Duplex Streaming:** Live microphone monitoring over FastAPI WebSockets and React AudioWorklet.
- **Objective Evaluation:** Reports SI-SDR improvement, STOI, log-spectral distance, processing latency and real-time factor, with FFT spectrogram comparisons. PESQ is left `null` because no licensed evaluator is redistributed.
- **Stack:** `PyTorch` · `SciPy` · `FastAPI` · `React 19` · `TypeScript` · `WebSockets`

---

#### 📚 [TechnicalDocs AI — Citation-Grounded Question Answering](https://github.com/AbinaSelvamurugan/rag-chatbot-over-technical-documents)
> **Persistent ChromaDB Vectors · Groq Inference · Claim-by-Claim Evidence Verification**

A full-stack RAG application for technical PDFs, Markdown, and HTML documentation that rejects unverified model claims and ensures absolute documentation provenance.
- **Strict Evidence Checking:** Answers are generated claim by claim; claims lacking direct citations or failing textual verification are rejected before display.
- **Deterministic Embeddings:** Persistent ChromaDB vector database with sentence transformer embeddings and cosine similarity telemetry.
- **High-Throughput Generation:** Accelerated inference via the Groq Llama-3 API.
- **Stack:** `ChromaDB` · `Groq` · `SentenceTransformers` · `FastAPI` · `Docker`

---

#### 📊 [RAGBench Studio — Evaluation & Observability Dashboard](https://github.com/AbinaSelvamurugan/rag-evaluation-dashboard)
> **DeepEval Judge Metrics · Precision-Recall Telemetry · Experiment Versioning**

An interactive observability application that captures retrieval and generation traces, computes deterministic retrieval metrics, and monitors performance drift across vector index configurations.
- **Judge Metrics:** DeepEval Faithfulness, Answer Relevancy and Contextual Precision/Recall, reported with valid counts rather than zero-filled placeholders.
- **Deterministic Curves:** Precision-recall curves and MRR computed from annotated retrieval ground truth.
- **Experiment Tracking:** Compares versioned index runs and monitors data drift inside a Streamlit analytics dashboard.
- **Stack:** `DeepEval` · `Streamlit` · `SQLite` · `Pandas` · `Scikit-Learn`

---

### ✦ Open-Source Systems Directory

A catalog of all 11 specialized machine learning and AI repositories in my portfolio:

| System | Specialization | Core Stack | Architecture Highlights | Source |
| :--- | :--- | :--- | :--- | :--- |
| **JudgeBench** | LLM Evaluation | Claude Sonnet 4.6, SQLite | Rubric calibration & inter-rater metrics | [Repository →](https://github.com/AbinaSelvamurugan/llm-as-judge-scoring-system) |
| **ClearVoice AI** | Speech AI | PyTorch, FastAPI, React | Causal CRN neural noise suppression | [Repository →](https://github.com/AbinaSelvamurugan/ai-noise-suppression-for-online-consultations) |
| **TechnicalDocs AI** | RAG Systems | ChromaDB, Groq | Claim-level citation verification | [Repository →](https://github.com/AbinaSelvamurugan/rag-chatbot-over-technical-documents) |
| **RAGBench Studio** | RAG Observability | DeepEval, Streamlit | Automated judge metrics & drift tracking | [Repository →](https://github.com/AbinaSelvamurugan/rag-evaluation-dashboard) |
| **CareGuide AI** | Safety & Triage | Pydantic, FastAPI | Safety-first healthcare symptom triage assistant | [Repository →](https://github.com/AbinaSelvamurugan/healthcare-symptom-triage-assistant) |
| **HalluBench** | Model Faithfulness | Python, Benchmark Suite | Hallucination detection & factual consistency — HaluEval QA, 20,000 examples; best detector F1 0.592 | [Repository →](https://github.com/AbinaSelvamurugan/hallucination-detection-benchmark) |
| **ModelWatch** | MLOps & Monitoring | SQLite, Python Telemetry | Production data & concept drift detection | [Repository →](https://github.com/AbinaSelvamurugan/model-monitoring-and-drift-dashboard) |
| **FairAudit** | Bias & Fairness | Scikit-learn, Python | Bias and fairness assessment of ML datasets — RAND HIE audit: ROC-AUC 0.667, demographic-parity difference 0.351 | [Repository →](https://github.com/AbinaSelvamurugan/bias-and-fairness-audit) |
| **SpeechBench** | Audio Benchmarking | PESQ, STOI, Librosa | Speech enhancement benchmark — 200 real LibriSpeech × DEMAND mixtures; PESQ 1.79 → 2.28, SNR +7.72 dB | [Repository →](https://github.com/AbinaSelvamurugan/speech-enhancement-evaluation-benchmark) |
| **AnnotaFlow** | Data Curation | Active Learning, Python | Data annotation and quality assurance pipeline | [Repository →](https://github.com/AbinaSelvamurugan/data-annotation-and-quality-pipeline) |
| **SensorBench** | Edge AI & Sensors | PyTorch, Python | Reproducible inertial-sensor activity classification — UCI HAR held-out macro-F1 0.954 across 9 unseen subjects | [Repository →](https://github.com/AbinaSelvamurugan/sensor-classification-benchmark) |

---

### ✦ Contribution Activity & Telemetry

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AbinaSelvamurugan/AbinaSelvamurugan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AbinaSelvamurugan/AbinaSelvamurugan/output/github-contribution-grid-snake.svg">
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/AbinaSelvamurugan/AbinaSelvamurugan/output/github-contribution-grid-snake-dark.svg" width="100%" />
</picture>

</div>

<br/>

<div align="center">

<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td align="center" valign="middle">
<img src="https://github-readme-stats.vercel.app/api?username=AbinaSelvamurugan&show_icons=true&theme=dark&bg_color=090d16&title_color=ffffff&text_color=94a3b8&icon_color=f1f5f9&border_color=1e293b&hide_border=false" alt="GitHub Stats" />
</td>
<td align="center" valign="middle">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbinaSelvamurugan&layout=compact&theme=dark&bg_color=090d16&title_color=ffffff&text_color=94a3b8&border_color=1e293b&hide_border=false" alt="Top Languages" />
</td>
</tr>
</table>

<br/>

<img src="https://streak-stats.demolab.com?user=AbinaSelvamurugan&theme=dark&background=090d16&border=1e293b&stroke=f1f5f9&ring=ffffff&fire=ffffff&currStreakNum=ffffff&sideNums=ffffff&currStreakLabel=94a3b8&sideLabels=64748b&dates=64748b&hide_border=false" alt="Contribution Streak" />

</div>

<br/>

---

<div align="center">

<img src="https://raw.githubusercontent.com/AbinaSelvamurugan/AbinaSelvamurugan/main/footer.svg" width="100%" alt="Footer Banner" />

<sub>
Engineered by <a href="https://github.com/AbinaSelvamurugan">@AbinaSelvamurugan</a> · Systems Architect &amp; AI Engineer
</sub>

</div>
