# Global AI Regulation Divergence Index
### Analysing AI regulatory divergence across 30 countries · 8 parameters · April 2026

![World Map Preview](visualisations/global_ai_regulation_map.html)

## Overview
Primary research project scoring 30 countries across 6 regions against 8 AI 
governance parameters on a 0–2 scale (0 = absent · 1 = voluntary/partial · 
2 = binding/enforced). The result is a Divergence Index revealing which countries 
are Regulatory Hawks, Developing Frameworks, or Regulatory Doves.

## Key findings
- **13 Regulatory Hawks · 13 Regulatory Doves · 4 Developing Frameworks** — the world is evenly split
- **Europe leads** at 14.0/16 average · Americas lags at 5.4/16 — a 2.6× gap
- **93.5%** of countries have a national AI strategy · only **38.5%** have an enforcement mechanism
- **13 of 30 countries** have published an AI strategy but built zero enforcement capacity
- **Brazil (13/16)** outscores the United States (4/16) and United Kingdom (5/16)

## Interactive map
[View interactive choropleth world map →](visualisations/global_ai_regulation_map.html)

## Methodology
Binary-to-scaled scoring (0–2) across 8 parameters:

| Parameter | Description |
|---|---|
| has_binding_legislation | Legally binding AI legislation in force |
| has_risk_based_approach | Risk-tiered regulatory framework |
| has_enforcement_mechanism | Designated authority with power to sanction |
| has_transparency_oblig | Mandatory disclosure of AI use |
| has_human_oversight | Legal requirement for human review of AI decisions |
| has_penalty_framework | Financial or criminal penalties for non-compliance |
| has_national_ai_strategy | Formal national AI strategy with funded implementation |
| has_prohibited_practices | Legally banned AI use cases |

## Regulatory clusters
| Cluster | Score | Countries |
|---|---|---|
| Regulatory Hawk | 12–16 (75%+) | EU, Germany, France, South Korea, China, Brazil, Vietnam, Kazakhstan + more |
| Developing Framework | 7–11 (40–74%) | Switzerland, Canada, Singapore, Israel |
| Regulatory Dove | 0–6 (<40%) | United States, United Kingdom, Japan, India, UAE, African nations |

## Repository structure
global-ai-regulation-index/
├── data/
│   ├── global_ai_compliance_raw.csv
│   └── Global_AI_Regulation_Divergence_Index.xlsx
├── notebooks/
│   └── global_ai_regulation.ipynb
├── visualisations/
│   └── global_ai_regulation_map.html
└── README.md

## Tools
Python (pandas · plotly) · Tableau Public (coming soon) · GitHub

## Status
- [x] Dataset built — 30 countries, 8 parameters, April 2026
- [x] Python analysis — regional, parameter and cluster findings
- [x] Interactive choropleth world map — published
- [x] Jupyter notebook — documented with markdown
- [ ] Tableau dashboard — in progress
- [ ] LinkedIn post — coming soon

## About
Angkuran Dey · Google Data Analytics Professional Certificate (March 2026)
MSc Gender & International Relations, University of Bristol
[LinkedIn](https://www.linkedin.com/in/angkurandey/) · 
[EU AI Act Companion Project](https://github.com/angkuran-dey/eu-ai-act-compliance-tracker)

