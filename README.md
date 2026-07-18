# Sean Smithurst

**Data scientist — MSc Data Science (Distinction), University of Salford. Former consultant ecologist.**

I came to data science by an unusual route: three years as a Consultant Ecologist producing statutory-compliance reports for UK planning authorities, then a full retrain in data science. That background sets how I work: hypotheses are pre-specified, uncertainty is quantified, pipelines are tested and CI-checked — and when a robustness check kills a result, the result goes, not the check.

## Portfolio

| Project | What it shows |
|---|---|
| [llm-fraud-detection](https://github.com/Smurfhurst/llm-fraud-detection) | Do LLM embeddings earn their carbon cost in fraud detection? Four hypotheses on UK open data (Companies House, Insolvency Service) at 0.11% fraud prevalence. Headline: they don't — ΔF2 = −0.020, 95% CI [−0.029, −0.010] — a negative result made rigorous with fold-level and Wilson confidence intervals, calibration evidence, a pre-registered follow-up experiment grid, and per-fold GPU energy measurement. 169 tests, CI on every push. |
| [uk-transport-telematics](https://github.com/Smurfhurst/uk-transport-telematics) | Five pre-specified hypotheses on UK transport (DVLA/DfT/STATS19): BEV infrastructure, HGV fleets, road-safety risk, insurance NPV, telematics-SaaS economics. Four supported at Bonferroni-corrected α = 0.010, backed by spatial (Moran's I, cluster-robust SEs), ordinal and sensitivity robustness checks; the fifth honestly retired after jackknife analysis exposed degenerate financial data driving the correlation. 30 tests, CI on every push. |

**Research:** my MSc dissertation (85/100) introduced a Carbon Efficiency Metric for ML model selection — XGBoost matched or beat a TabTransformer at every prediction stage while using 27–63× less energy — and demonstrated a 68% emissions reduction through carbon-aware scheduling against UK grid-intensity data. Adapted as a conference paper (Springer LNCS format) with my University of Salford supervisors.

**Currently building:** Learnamal — an interactive 3D education platform for zoos.

## Toolbox

Python (pandas, scikit-learn, XGBoost, LightGBM, PyTorch, sentence-transformers) · R (tidyverse) · SQL · Apache Spark · statsmodels · Power BI / DAX · pytest & GitHub Actions · Git

📫 seanmark2000@gmail.com
