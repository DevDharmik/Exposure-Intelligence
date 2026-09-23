# Exposure-Intelligence

**A Machine Learning Framework for Sponsorship Exposure and ROI Valuation**

> Status: Thesis proposal approved — Phase 1 (Topic Selection) in progress · M.Sc. Data Science, University of Europe for Applied Sciences (UEAS), Potsdam · Winter 2026/27 thesis cycle

This repository is the working codebase for my final M.Sc. thesis, extending the Brand Value Index (BVI) methodology from my capstone project, [PitWall Intelligence](https://github.com/DevDharmik/Pitwall-intelligence), with a third dimension: **Exposure**.

## Background

PitWall Intelligence built a two-dimensional BVI (Performance 60% + Consistency 40%) to quantify Formula 1 constructor sponsorship value using Gradient Boosting Regression and SHAP explainability (GBR test R² = 0.976, podium-classifier AUC-ROC = 0.928). Live dashboard: https://nnx9pdbkj7agwwsbn2m7bb.streamlit.app/

That project deliberately excluded exposure data. This thesis adds it — and generalizes the methodology beyond motorsport so it applies to sponsorship valuation more broadly (e.g. automotive and brand marketing contexts).

## Research questions

1. How can sponsorship exposure be quantified in a standardised, data-driven way from available performance, broadcast, and digital engagement data?
2. Which machine learning approaches most effectively model the relationship between quantified exposure and sponsorship ROI, and how can SHAP-based explainability support that modelling?
3. How well does an Exposure-augmented Brand Value Index generalise beyond motorsport to other sponsorship-driven marketing contexts?

## Planned data sources

- Formula 1 Grand Prix dataset (Kaggle) — historical race, constructor and performance data
- OpenF1 API — live and historical telemetry/session data

## Planned methodology

Extends the PitWall Intelligence stack (Python, Pandas/NumPy, Scikit-learn, SHAP, Streamlit) with a third, Exposure dimension added to the existing BVI. Baseline models (Linear Regression, Decision Tree) will be compared against advanced models (Gradient Boosting Regression, Logistic Regression with Platt scaling), evaluated via 5-fold cross-validated RMSE/R² and held-out AUC-ROC.

## Supervision

- **Main supervisor:** Prof. Dr. Talha Ali Khan (Program Leader, VP of Research) — proposal reviewed and approved
- **Thesis coordinator:** Prof. Raja Hashim Ali (Digital Business and Data Science)

## Status

Proposal drafted and approved. Repository scaffolded; implementation to follow the thesis roadmap (topic finalization → proposal/dataset → experimentation → journal paper → thesis write-up).

## Related work

- [PitWall Intelligence](https://github.com/DevDharmik/Pitwall-intelligence) — the completed M.Sc. capstone this thesis extends

## Author

Dharmik Champaneri — M.Sc. Data Science, University of Europe for Applied Sciences (Berlin / Potsdam)

## License

MIT
