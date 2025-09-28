# From Chat to Forecast: Predicting Box Office with ChatGPT (CRISP-DM, time-aware ML)

**Author:** Shreram Palanisamy  
**Mode:** Chat-only (all work done in ChatGPT)  
**Dataset:** Kaggle IMDB movie-level metadata

## 
HistGradientBoosting on log(BoxOffice) + Duan smearing beat baselines on MAE/WAPE.  
At $100M: Accuracy ≈ 0.82, Precision ≈ 0.75, Recall ≈ 0.49 (future holdout).  
Recommendation: ship HGB for $ forecasts; threshold for hit/no-hit.

## Links
- **Medium article:** https://medium.com/@shrerampalanisamy/from-chat-to-forecast-predicting-box-office-with-chatgpt-crisp-dm-time-aware-ml-317b086eada3
- **Chat transcript (PDF):** `transcripts/chatgpt_session.pdf`
- **Screenshots (figures):** `reports/figures/`

## CRISP-DM Summary
Business ✓ · Data Understanding ✓ · Data Prep ✓ · Modeling ✓ · Evaluation ✓ · Deployment ✓  
Leak-safe features, time-aware splits, log-target + smearing, and decision metrics (@$100M).

## What’s in this repo
- `reports/figures/` – screenshots from ChatGPT (EDA, importances, model comparisons, @$100M table)
- `transcripts/` – SaveGPT export of the full chat
- `article_link.md` – Medium URL for grading

## License
MIT — see [LICENSE](./LICENSE).
