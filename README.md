## Adil Bouhoum

AI & Data Science engineering student at **EMSI Marrakech**, looking for a **6-month end-of-studies internship (PFE) from February 2027** in data science, ML engineering or MLOps.

**[Portfolio with live demos](https://adilbouhoum.vercel.app/en)** · [CV (EN)](https://adilbouhoum.vercel.app/cv/Adil-Bouhoum-CV-EN.pdf) · [CV (FR)](https://adilbouhoum.vercel.app/cv/Adil-Bouhoum-CV-FR.pdf) · [LinkedIn](https://www.linkedin.com/in/adil-bouhoum-b83129232) · [adilbhm2003@gmail.com](mailto:adilbhm2003@gmail.com)

I train models, measure them honestly (baselines, calibration, decision thresholds) and ship them, with a soft spot for models that know when to stay quiet.

### AI & data

| Project | What it does | Result |
| --- | --- | --- |
| **Payer-email reader**<br>Lama Healthcare internship, 2026<br><sub>code is private</sub> | Fine-tuned Qwen3-8B (QLoRA) that updates healthcare credentialing records from insurer emails, and abstains when it isn't sure. | **94.7% accuracy** at a 0.8 confidence threshold (59.8% zero-shot), calibration error 0.34 → 0.06. Deployed on AWS SageMaker. |
| **[Aman](https://github.com/Adil-Bouhoum/Aman-Toxicity-Detector)**<br>Team of 4, 2026 | Multi-label toxicity detection for Moroccan Darija, in Arabizi and Arabic script. An XLM-R teacher distilled into a DistilBERT student. I trained the last two models and connected the API. | **F1 0.895** on DarLoad with a model ~4× smaller. [Live API](https://huggingface.co/spaces/BHM03/amane-api) and a [32-sentence audit](https://adilbouhoum.vercel.app/en#aman) of where it fails. |
| **[TrendRadar](https://github.com/Adil-Bouhoum/TrendRadar)**<br>Team of 4, lead implementation, 2026 | Predicts whether a hashtag will go viral from its first 15 minutes, then keeps learning online from live Bluesky / Mastodon streams. | **ROC-AUC 0.921** on a held-out test set. [Run the model in your browser](https://adilbouhoum.vercel.app/en#trendradar). |
| **[Q-learning traffic lights](https://github.com/Adil-Bouhoum/Trafic-Control-Q-learning)** | Tabular Q-learning agent written from scratch for a 4-way junction, compared to a fixed cycle and a "longest queue" rule. | 4 traffic scenarios compared, Streamlit demo. |

### Software engineering

- **HIPAA-compliant SaaS platform** (Lama Healthcare, team of 3, private): owned security and infrastructure. 130 API routes, 60 tables under row-level security, AES-256-GCM encryption, rate limiting, audit logs, 17 test suites. Next.js, TypeScript, PostgreSQL.
- **Airport access-badge app** (ONDA internship, sole developer, 2025): multi-level approval workflow (requester → DGSN → GRM → issuing office) with role-based auth and PDF badges. Laravel + Sanctum, React, MySQL.
- **[TravelMate](https://github.com/BADIAMOHAMEDAYMANE/Flight-Management)** (pair project): I wrote the Flask + Gemini chatbot backend and its modular rewrite (15 of 23 commits). A local Mistral prototype lives in [TravelMateBeta](https://github.com/Adil-Bouhoum/TravelMateBeta).
- **[BabyCheck](https://github.com/Adil-Bouhoum/BabyCehck)**: React Native app on a Laravel 12 API, with a vaccine schedule generated from Morocco's national immunisation programme.
- **Team contributions**: [Nezflix](https://github.com/Nezgova/Movie-App) (React / Node streaming app), [La Cagnotte](https://github.com/ili9141/Cagnotte) (PHP expense tracker), [CarRental](https://github.com/ili9141/CarRentalSystem) (ASP.NET Core MVC client portal).
- **[FirstFantasy](https://github.com/Adil-Bouhoum/FirstFantasy)**: a turn-based RPG in Java / JavaFX, [playable in the browser](https://adilbouhoum.vercel.app/en?view=dev#firstfantasy) through a TypeScript port.

### Tools I've used in these projects

- **ML & AI**: Python, PyTorch, Hugging Face Transformers, PEFT / QLoRA, scikit-learn, XGBoost, River, Pandas, LangChain
- **MLOps & cloud**: AWS SageMaker, Docker, FastAPI, Flask, Hugging Face Spaces, Vercel
- **Web & data**: TypeScript, Next.js, React, Laravel, PostgreSQL, MySQL, Redis, Java, C#
