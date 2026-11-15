# 23BCS259 — Data Engineering Assignment
## From Git to Gold: Version control, ELT, ML pipelines and event streaming

| Item | Details |
|------|---------|
| Course | Data Engineering |
| Student | 23BCS246 |
| Repo | 23bcs246_DE_Submission |
| Platform | Google Colab + Snowflake + GitHub Actions |

## Repository Structure

```
freshcart-pipelines/
├── elt/                    ← FreshCart ELT notebook (Part B)
├── iris_project/           ← Mage ML pipeline project (Part C)
│   └── transformers/
├── stream/                 ← RabbitMQ dispatcher & driver (Part D)
├── tests/                  ← Pytest tests for CI
│   └── test_prepare_data.py
├── .github/workflows/      ← GitHub Actions CI workflow
│   └── ci.yml
├── requirements.txt
├── .gitignore
└── README.md
```

## Parts
- **Part A** — Git & CI/CD (15 marks)
- **Part B** — FreshCart ELT on Snowflake (30 marks)
- **Part C** — ML Pipeline with Mage (20 marks)
- **Part D** — Food-order stream with RabbitMQ (20 marks)
- **Part E** — Report & Viva (15 marks)
