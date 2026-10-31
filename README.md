# Vadim Vasilenko

Machine Learning Engineer / Data Scientist · Yandex School of Data Analysis (ML track)
4th-year B.S. student at MIPT (Biomedical Physics & Biotechnology) · Kaggle gold medalist

---

## About

ML engineer in Yandex Search Trust & Safety: production models against fake and generated
content, phishing, SEO spam, abusive redirects and content farms — from custom transformer
architectures and VLM / BERT / CatBoost modeling to distillation, inference at scale and
monitoring. Interested in ML for biology, sequential decision making and agents.
Russian (native), English (C1).

---

## Experience

**Yandex — Search, Trust & Safety — Data Scientist** *(Aug 2025 — present)*
Designed a transformer architecture from scratch for abusive-redirect detection and shipped
it to production (−10 % LogLoss vs the previous solution). Multimodal VLM + BERT page-quality
model over screenshots and text (+20 % F1). BERT ranking factor for fake content with
UGC-review summarization features (−43 % fake content on acceptance measurement). CatBoost
SEO-spam factor on 20+ traffic-graph features from billions of user transitions (−6 % LogLoss).
Content-farm detectors retrained and deployed on Yandex and Google streams (~90 % less
leakage). Screenshot labeling pipeline with YandexVLM (60–70 % of the stream filtered
automatically, >50 % lower annotation cost). VLM → BERT → DSSM knowledge distillation for
serving: 8B queries scored in ~2 days. Production integration, GPU profiling, monitoring
(data SLA cut from 12–16 h to 8 h).

**Yandex — Search, Trust & Safety — ML Intern** *(Apr 2025 — Aug 2025)*
End-to-end VLM pipeline for visual phishing detection, integrated alongside the main banning
model (+10 % more phishing caught daily).

**Vavilov Institute of General Genetics (RAS) — Research Project**
Recommender of suitable cell lines on top of the cell ontology (graph ML, recommender
systems); ML representations of biological data under academic supervision.

---

## Selected Projects

**[Kaggriculture agent](https://github.com/vasvadim/kaggriculture)** — Kaggle simulation competition, gold medal: 21st of 10,148 teams, peak #2, solo (2026)
Transformer imitation-learning agent for a two-player farming economy: 20.5 M-parameter
entity transformer with an autoregressive market decoder, daily re-training on the strongest
opponent's newest version, GPU-batched self-play evaluation, model soups.

**[AI Challenge 2026 — Digital Detective](https://github.com/vasvadim/aiijc-2026-image-forgery-localization)** — hackathon, Computer Vision track finalist, team «Амнямы» (2026)
Localisation of generative edits in photos: U-Net with an EfficientNet-B5 encoder, a soup of
14 fine-tunes distilled from a ViT-L teacher under a 100 GFLOPs budget.
[Weights](https://huggingface.co/OnlyOmNoms/aiijc_2026_detective) and
[demo service](https://huggingface.co/spaces/Kseniiashk/detective) on Hugging Face.

**[AI Challenge 2025 — Pharmacy track (NLP)](https://huggingface.co/spaces/Kseniiashk/apteka_aiijc)** — hackathon, 2nd place (student track, 2025)
Solution code and demo on Hugging Face Spaces.

**Smaller projects:**
- [arXiv article classifier](https://github.com/vasvadim/arxiv-article-classifier) — DistilBERT + Streamlit, YSDA course project.
- [Minecraft2Real](https://huggingface.co/spaces/vasvadim/minecraft2real) — CycleGAN demo on Hugging Face Spaces.
- [FineTrack Telegram bot](https://github.com/vasvadim/finetrack-telegram-bot) — MOEX stock tracker with charts and correlations.
- [Bioinformatics coursework](https://github.com/vasvadim/mipt-bioinformatics-course) — genome assembly, RNA-seq, differential expression.

---

## Education

**Yandex School of Data Analysis (YSDA)** — ML track *(Sep 2025 — Jun 2026)*
Highly selective graduate-level ML program (multi-stage entrance exams and interviews),
completed with excellent grades. Reinforcement Learning, NLP, LLM Agents, Data Collection
& Annotation for ML.

**Moscow Institute of Physics and Technology (MIPT)** — B.S., Faculty of Biomedical Physics & Biotechnology, 4th year *(2023 — present)*
Advanced mathematics, probability & statistics, algorithms & data structures, machine
learning, bioinformatics.

---

## Stack

**Languages** — Python (primary), SQL, C++, Linux, Docker, Git
**ML** — ranking & retrieval, classification, NLP, computer vision, multimodal (VLM), LLMs,
embeddings, knowledge distillation, graph ML, recommender systems, imitation and
reinforcement learning
**Frameworks** — PyTorch, Transformers, TensorFlow, CatBoost, scikit-learn, Pandas, NumPy, SciPy
**Production** — distributed inference, model deployment, data pipelines, GPU profiling,
monitoring, feature engineering, experiment design, statistical analysis

---

## Achievements

- Kaggle gold medal — Kaggriculture, agent-simulation competition by Kaggle and Google (2026)
- 2nd place, AI Challenge (AIIJC), NLP track (2025); finalist, Computer Vision track (2026)
- Winner, All-Russian School Olympiad in Chemistry, final stage (2023)
- Abramov Scholarship for academic results · ICPC Moscow Regional 2024 · 200+ LeetCode problems

---

## Contact

[vasvadiim@gmail.com](mailto:vasvadiim@gmail.com) · [LinkedIn](https://www.linkedin.com/in/vadim-vasilenko-1a81a7413/) · [Kaggle](https://www.kaggle.com/vadimvasilenko) · [Hugging Face](https://huggingface.co/vasvadim) · [OnlyOmNoms AI](https://huggingface.co/OnlyOmNoms)
