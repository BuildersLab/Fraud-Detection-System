# Fraud Detection System

![Python](https://img.shields.io/badge/Python-3.11-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Build](https://img.shields.io/badge/Build-Passing-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-Credit-Card-Fraud-Detection-%28TBD%29-orange)
![LLM](https://img.shields.io/badge/LLM-Gemini%20API-purple)

Build an explainable machine learning fraud detection platform for NorthBay Bank that identifies suspicious card-not-present transactions, assists fraud analysts through an interactive review dashboard, and reduces fraud losses while minimizing false alerts.

Built by the BuildersLab team for NorthBay Bank (TBD).

---

## What this project does

<!-- Fill in after Week 1. Describe the problem, the system, and the output in 3 to 5 bullet points. -->

- TODO
- TODO
- TODO

## Live demo

[Fraud-Detection-System.replit.app](#) - public, no login required

---

## Team

| Name | Role |
|---|---|
| Nafisat Ibrahim | Project Lead: delivery, stakeholder framing, demo |
| Laël Keïla Nacro, Emmanuel N'guetta | Data Science: EDA, feature engineering, modeling, explainability, documentation |
| Anna Zhelizniak, Sai Kotthireddy | ML Engineer: pipeline, API integration, Replit app |

---

## Quickstart

```bash
git clone https://github.com/builderslab/Fraud-Detection-System.git
cd Fraud-Detection-System
make setup
```

Download the dataset from URL (TBD) and place the files in `data/raw/`. See [docs/setup_guide.md](docs/setup_guide.md) for full instructions.

```bash
make data      # build features
make train     # train champion model
make evaluate  # print metrics report
make app       # launch dashboard
```

---

## Repo structure

```
Fraud-Detection-System/
├── data/
│   ├── raw/                  # original files, never edited, gitignored
│   ├── processed/            # pipeline outputs, gitignored
│   └── DATA_CARD.md
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modeling.ipynb
│   └── 04_explainability.ipynb
├── src/
│   ├── data_pipeline.py
│   ├── features.py
│   ├── train.py
│   ├── evaluate.py
│   ├── explain.py
│   ├── predict.py
│   ├── gemini.py             # optional: remove if not using Gemini
│   └── prompts.py            # optional: remove if not using Gemini
├── models/
│   └── MODEL_CARD.md
├── app/
│   ├── main.py
│   ├── pages/
│   ├── components/
│   └── requirements.txt
├── tests/
├── docs/
├── .github/
├── .env.example
├── Makefile
└── pyproject.toml
```

---

## Key results

> Populated after Week 8 modeling milestone

| Metric | Value |
|---|---|
| PR-AUC | TBD |
| Recall at threshold | TBD |
| Business impact | TBD |
| False positive rate | TBD |

---

## Documentation

- [Data Card](data/DATA_CARD.md)
- [Model Card](models/MODEL_CARD.md)
- [Setup Guide](docs/setup_guide.md)
- [Workflow and PR conventions](docs/workflow.md)
- [Decision log](docs/decisions.md)
- [Notion workspace](https://www.notion.so/builderslab/Fraud-Detection-System-360663a5d5d1801891a3fc873503cc9b)
