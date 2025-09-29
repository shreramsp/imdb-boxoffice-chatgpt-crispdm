# From Chat to Forecast: Predicting Box Office with ChatGPT (CRISP-DM, time-aware ML)

**Author:** Shreram Palanisamy  
**Mode:** Chat-only  
**Dataset:** Kaggle IMDB movie-level metadata

## TL;DR
HistGradientBoosting on `log1p(BoxOffice)` + Duan smearing beat baselines on **MAE/WAPE**.  
At **$100M**: **Accuracy ≈ 0.81**, **Precision ≈ 0.71**, **Recall ≈ 0.45** (future holdout).  
Recommendation: ship **HGB** for $ forecasts; threshold for hit/no-hit.

## Links
- **Medium article:** https://medium.com/@shrerampalanisamy/from-chat-to-forecast-predicting-box-office-with-chatgpt-crisp-dm-time-aware-ml-317b086eada3
- **Chat transcript (PDF):** `transcripts/chatgpt_session.pdf`
- **ChatGPT share link (txt):** `transcripts/chatgpt_share_link.txt`
- **Screenshots (figures):** `reports/figures/`

## Results (CSV)
- Regression — Validation: [artifacts/regression_validation.csv](artifacts/regression_validation.csv)  
- Regression — Test: [artifacts/regression_test.csv](artifacts/regression_test.csv)  
- Classification @ $100M — Validation: [artifacts/classification_100m_validation.csv](artifacts/classification_100m_validation.csv)  
- Classification @ $100M — Test: [artifacts/classification_100m_test.csv](artifacts/classification_100m_test.csv)

## CRISP-DM Summary
Business ✓ · Data Understanding ✓ · Data Prep ✓ · Modeling ✓ · Evaluation ✓ · Deployment ✓  
Leak-safe features, time-aware splits, log-target + smearing, and decision metrics (@$100M).

## What’s in this repo
- `reports/figures/` – screenshots from ChatGPT (EDA, importances, model comparisons, @$100M table)  
- `artifacts/` – CSV results for validation/test and classification @ $100M  
- `transcripts/` – SaveGPT export of the full chat + share link  
- `article_link.md` – Medium URL for grading

## License
MIT — see [LICENSE](./LICENSE).
