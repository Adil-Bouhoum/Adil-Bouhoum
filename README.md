## Adil Bouhoum

AI & Data Science engineering student at **EMSI Marrakech**. I build machine-learning models and the software around them: I train them, measure them honestly (baselines, calibration, decision thresholds) and ship them behind an API or an interface people can use.

**[Portfolio with live demos](https://adilbouhoum.vercel.app/en)** · [CV (EN)](https://adilbouhoum.vercel.app/cv/Adil-Bouhoum-CV-EN.pdf) · [CV (FR)](https://adilbouhoum.vercel.app/cv/Adil-Bouhoum-CV-FR.pdf) · [LinkedIn](https://www.linkedin.com/in/adil-bouhoum-b83129232) · [adilbhm2003@gmail.com](mailto:adilbhm2003@gmail.com)

### AI & data projects

| Project | What it does | Result |
| --- | --- | --- |
| **[Aman](https://github.com/Adil-Bouhoum/Aman-Toxicity-Detector)**<br>Team of 4 | Multi-label toxicity detection for Moroccan Darija, in Arabizi and Arabic script. An XLM-R teacher distilled into a DistilBERT student. I trained the last two models and connected the API. | **F1 0.895** on DarLoad with a model ~4× smaller. [Live API](https://huggingface.co/spaces/BHM03/amane-api) and a [32-sentence audit](https://adilbouhoum.vercel.app/en#aman) of where it fails. |
| **[TrendRadar](https://github.com/Adil-Bouhoum/TrendRadar)**<br>Team of 4, lead implementation | Predicts whether a hashtag will go viral from its first 15 minutes, then keeps learning online from live Bluesky / Mastodon streams. | **ROC-AUC 0.921** on a held-out test set. [Run the model in your browser](https://adilbouhoum.vercel.app/en#trendradar). |
| **[Q-learning traffic lights](https://github.com/Adil-Bouhoum/Trafic-Control-Q-learning)** | Tabular Q-learning agent written from scratch for a 4-way junction, compared to a fixed cycle and a "longest queue" rule. | 4 traffic scenarios compared, Streamlit demo. |

### Software projects

- **[TravelMate](https://github.com/BADIAMOHAMEDAYMANE/Flight-Management)** (pair project): an AI travel advisor. I wrote the Flask + Gemini chatbot backend and its modular rewrite (15 of 23 commits). A local Mistral prototype lives in [TravelMateBeta](https://github.com/Adil-Bouhoum/TravelMateBeta).
- **[BabyCheck](https://github.com/Adil-Bouhoum/BabyCehck)**: React Native app on a Laravel 12 API that tracks a baby's growth, medical records and meals, with a vaccine schedule generated from Morocco's national immunisation programme.
- **[FirstFantasy](https://github.com/Adil-Bouhoum/FirstFantasy)**: a turn-based RPG in Java / JavaFX, [playable in the browser](https://adilbouhoum.vercel.app/en?view=dev#firstfantasy) through a TypeScript port.
- **Team contributions**: [Nezflix](https://github.com/Nezgova/Movie-App) (React / Node streaming app), [La Cagnotte](https://github.com/ili9141/Cagnotte) (PHP expense tracker), [CarRental](https://github.com/ili9141/CarRentalSystem) (ASP.NET Core MVC client portal).

### Skills

- **ML & AI**: Python, PyTorch, Hugging Face Transformers, PEFT / QLoRA, knowledge distillation, scikit-learn, XGBoost, River, Pandas, LangChain
- **MLOps & cloud**: Docker, FastAPI, Flask, AWS SageMaker, Hugging Face Spaces, Vercel
- **Web & data**: TypeScript, Next.js, React, React Native, Laravel, PostgreSQL, MySQL, Java, C#
