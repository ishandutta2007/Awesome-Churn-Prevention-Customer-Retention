# Awesome-Churn-Prevention-Customer-Retention

## Top Churn Prevention & Customer Retention Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Customer Health Scoring, Proactive Engagement & Automated Retention Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Churn Prevention & Customer Retention**. These tools help customer success and revenue teams identify at-risk accounts, automate health scoring, trigger playbooks, and orchestrate win-back campaigns—reducing revenue leakage and extending customer lifetime value.

**Examples** include Chargebee Retention, ChurnZero, Gainsight, Planhat, Totango, Vitally, Custify, ProfitWell Retain, ProsperStack, and Upsort (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted churn prediction, customer health scoring, and retention automation—ideal for data teams, customer success engineers, and developers building transparent, vendor-neutral retention infrastructure without per-seat enterprise pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Chargebee Retention](https://www.chargebee.com/)** | Retention module within Chargebee's subscription management suite; provides cancel-flow insights, session-based churn analytics, and retention offer orchestration [citation:1]. | $250/month for 50–149 sessions/month [citation:1] | No free tier; trial available via Chargebee platform signup |
| **[ChurnZero](https://churnzero.com/)** | Customer success platform with real-time health scoring, automated playbooks, in-app engagement, and renewal management for subscription businesses [citation:2][citation:12]. | $12,000/year (~$1,000/month) [citation:2] | No free version; free trial available [citation:2] |
| **[Gainsight](https://www.gainsight.com/)** | Enterprise customer success platform with health scores, journey orchestration, and product experience analytics; requires sales engagement for pricing [citation:3]. | Quote-only (custom pricing) [citation:3] | No self-serve trial for Customer Success tier; implementation typically ~5 months [citation:3] |
| **[Planhat](https://www.planhat.com/)** | Flexible customer success platform with customer portals, usage dashboards, and success plans; positioned for mid-market and enterprise [citation:4][citation:13]. | Custom pricing (Enterprise tier only) [citation:4] | No free tier; 14–30 day free trial typically offered [citation:4] |
| **[Totango](https://www.totango.com/)** | Customer success platform with health scores, early warning insights, journey optimizer, and automated playbooks [citation:5][citation:14]. | Custom pricing for paid tiers | Free Community Edition: up to 3 seats, 100 accounts, core CS features, 1,000 emails/month [citation:5] |
| **[Vitally](https://www.vitally.io/)** | Customer success platform with AI Copilot, account intelligence, meeting notes, and lifecycle playbooks for scaling SaaS teams [citation:6][citation:15]. | $299/month [citation:6] | No free version; free trial available (accessed via sales motion) [citation:6][citation:15] |
| **[Custify](https://www.custify.com/)** | Mid-market customer success platform with health scoring, playbooks, and automation; no published pricing or self-serve trial [citation:7]. | Custom pricing (demo required) [citation:7] | No published free tier or self-serve trial [citation:7] |
| **[ProfitWell Retain](https://www.profitwell.com/)** | Pay-for-performance retention service that recovers failed payments and cancellations using subscription expertise and algorithms; guarantees recovered customers stay ≥2 months [citation:8]. | Pay-for-performance (varies based on revenue recovered) [citation:8] | ProfitWell Metrics (analytics) is free forever; Retain itself has no free tier [citation:8] |
| **[ProsperStack](https://prosperstack.com/)** | Customer retention and churn management platform with cancellation flows, dynamic offers, and retention analytics. | $200/month [citation:9] | No free version; no free trial [citation:9] |
| **[Upsort](https://upsort.com/)** | Retention and churn prevention platform (limited public pricing information available; positioned as an emerging player in the retention space). | Contact sales | Contact vendor |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Churn Risk Detection Agent](https://github.com/AdityaKuranjekar/Churn-risk-detection-agent)** | [![Stars](https://img.shields.io/github/stars/AdityaKuranjekar/Churn-risk-detection-agent?style=social&color=white)](https://github.com/AdityaKuranjekar/Churn-risk-detection-agent/stargazers) | AI-powered Customer Success Agent that detects at-risk customers via dual-method risk scoring (XGBoost + SHAP and deterministic health score), retrieves matching playbooks via RAG, and drafts personalized retention outreach through a human-in-the-loop approval flow. FastAPI backend with vanilla JS SPA; test AUC 0.881 on 10,000 training rows [citation:10]. |
| **[ChurnShield](https://github.com/bijay-odyssey/ChurnShield-App)** | [![Stars](https://img.shields.io/github/stars/bijay-odyssey/ChurnShield-App?style=social&color=white)](https://github.com/bijay-odyssey/ChurnShield-App/stargazers) | Flask web app predicting customer churn with a Random Forest ML pipeline (scikit-learn) and generating personalized retention strategies. Includes admin dashboard, user authentication, EDA visualizations, and CSV export of prediction history; deployable on Railway . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Telemetry](https://github.com/topics/churn-prediction)** | — | Community topic page aggregating churn prediction projects, notebooks, and ML pipelines for further exploration. |
| **[Customer Churn Prediction (scikit-learn)](https://github.com/topics/customer-churn)** | — | Collection of customer churn classification notebooks and models using standard ML libraries. |

**Frameworks for building custom systems**: Combine **Churn Risk Detection Agent** for LLM-assisted risk scoring and outreach drafting, **ChurnShield** for a lightweight Flask-based prediction dashboard, and **scikit-learn/XGBoost** pipelines for custom model training—deployed via Docker or Railway with PostgreSQL for customer data storage.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Churn prevention tools process sensitive customer data; ensure compliance with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies.
- Open-source churn prediction models require validation on your own customer data before operational use; model drift and false positives should be monitored continuously.

---

**Made for customer success leaders, revenue operations teams, data scientists, and developers building retention infrastructure.**  
Let's make churn prevention more open, data-driven, and proactive.
