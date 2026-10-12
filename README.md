# Awesome-In-CRM-Predictive-Analytics

## Top In-CRM Predictive Analytics Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Sales Forecasting, Lead Scoring & Customer Churn Prediction*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **In-CRM Predictive Analytics Tools**. These tools embed machine learning and statistical models directly into CRM workflows — scoring leads, forecasting revenue, predicting churn, and surfacing next-best-actions without requiring separate data science pipelines or external BI platforms.



**Examples** include Salesforce Tableau CRM (Einstein Analytics), Clari Forecast, Gong Analytics, Aviso, BoostUp.ai, SugarPredict, Zoho Zia Analytics, Freshsales Freddy, Dynamics 365 Sales Insights, and Salesforce Einstein (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom predictive models, and transparent CRM analytics — ideal for revenue operations teams, data engineers, and developers building data-sovereign sales intelligence platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Tableau CRM (Einstein Analytics)](https://www.salesforce.com/)**  

  AI-powered analytics platform within Salesforce with predictive scoring, forecasting, and Einstein Discovery for automated insights. Rated a Leader in Gartner's Analytics and BI Platforms Magic Quadrant .



- **[Clari Forecast](https://www.clari.com/)**  

  Revenue operations platform with AI-powered forecasting, pipeline inspection, and risk detection for sales teams.



- **[Gong Analytics](https://www.gong.io/)**  

  Revenue intelligence platform analyzing sales conversations to predict deal outcomes, forecast revenue, and coach reps.



- **[Aviso](https://www.aviso.com/)**  

  AI-driven sales forecasting and pipeline management platform with predictive analytics and risk assessment.



- **[BoostUp.ai](https://www.boostup.ai/)**  

  Revenue operations and intelligence platform with forecasting, pipeline analytics, and deal risk prediction.



- **[SugarPredict](https://www.sugarcrm.com/)**  

  AI-powered predictive analytics within SugarCRM for lead scoring, opportunity forecasting, and customer insights. SugarCRM's platform integrates AI to assist with predictive analysis and personalized interactions .



- **[Zoho Zia Analytics](https://www.zoho.com/)**  

  AI assistant within Zoho CRM providing predictive lead scoring, best time to contact, and sales forecasting.



- **[Freshsales Freddy](https://www.freshworks.com/)**  

  AI engine within Freshsales CRM for lead scoring, deal insights, and next-best-action recommendations.



- **[Dynamics 365 Sales Insights](https://www.microsoft.com/en-us/dynamics-365)**  

  Microsoft's AI-powered sales analytics with predictive scoring, relationship analytics, and conversation intelligence.



- **[Salesforce Einstein](https://www.salesforce.com/)**  

  AI layer across Salesforce products providing predictive lead scoring, opportunity insights, and automated predictions.



## Open-Source GitHub Projects



- **[CRMlytics](https://wordpress.org/plugins/crmlytics/)**  

  Free WooCommerce CRM combining machine learning, customer management, and email campaigns in one unified system. Runs models on existing order history to calculate customer health scores (0-100 scale: Excellent, Healthy, Good, Weak, Critical), identify churn risk, predict future orders (30, 90, 180 days), and compute RFM (Recency, Frequency, Monetary) scores automatically. Everything runs locally — no external APIs, no monthly fees for number crunching. Includes email campaign manager targeting segments by health score or behavior .



- **[AI-Driven CRM Analytics System](https://github.com/Isha2605/AI-Driven-CRM-Analytics-System)**  

  Full-stack AI-powered CRM with sales tracking, event management, employee performance prediction, rewards, PyTorch chatbot, and lead-classification ML. Achieves 82% accuracy on lead scoring across 10,000+ customer records using KNN + Feedforward Neural Network. Built with Flask, MySQL, PyTorch, and scikit-learn. Includes conversational assistant for natural-language CRM queries. MIT licensed .



- **[b2b-revenue-forecasting](https://pypi.org/project/b2b-revenue-forecasting/)**  

  Python library for B2B revenue forecasting with hierarchical quota cascading, metric weighting via Pearson correlation, and brand-new IC detection. Features CommitReconciler for detecting and fixing forecasting bias (sandbagging/over-committing) with ML baseline blending. Exports to CSV, SQL, or interactive Chart.js HTML dashboards. Any numeric metric works — boolean and 0/1 sparse metrics auto-detected and excluded from zero-imputation .



- **[ChurnGuard AI](https://github.com/ShreyasDasari/churnguard-ai)**  

  Free, open-source churn prediction for SaaS. Plug in customer data via universal CSV schema and know who's leaving before they do. Features XGBoost primary model with LightGBM alternative, SMOTEENN resampling, PR-AUC evaluation, customer risk scoring with Critical/High/Medium/Low tiers, and revenue-weighted priority ranking. Outputs projected retention value ($5,952 MRR / $71,424 ARR recoverable in example). Supports Stripe, PostHog, HubSpot, and CSV imports .



- **[afrikana-analytics](https://pypi.org/project/afrikana-analytics/)**  

  Production-ready analytics toolkit covering churn prediction, customer lifetime value, financial modeling, site deployment optimization, and demand forecasting. Built from real analytical work across African markets. ChurnScorer uses Gradient Boosting for subscription/usage-based businesses. LTVCalculator provides discounted survival-adjusted CLV with Bronze/Silver/Gold tiers. Includes Monte Carlo simulation for NPV probability and break-even analysis .



- **[CallSense](https://github.com/aaron-seq/ML-voice-lead-analysis)**  

  Self-hosted conversation intelligence turning recorded sales calls into qualified leads with explainable scores. Features 0-100 lead scoring with every weighted component shown and transcript quote behind each one, 7 objection types flagged as addressed/unaddressed, 10 buyer intent signals mapped to BANT/MEDDIC, call outcome classification, next-best-action generation, and deal risk flags (no decision maker, no next step, budget unconfirmed, rep monologue). Runs on your infrastructure, no per-seat cost, no data leaving your network. Python 3.11+, no GPU required .



- **[lead-scoring-ai-mcp](https://www.npmjs.com/package/lead-scoring-ai-mcp)**  

  B2B lead scoring with engagement tracking and prioritization. Features score_lead based on firmographic data (company size, budget, engagement, decision maker contact, email verification, website traffic), add_lead tracking, update_lead_activity for email_open/click/demo_request/meeting_booked, predict_conversion probability, and track_engagement_trend. Free tier: 15 calls/day. MIT licensed .



- **[SalesIQ](https://github.com/badrr06/SalesIq)**  

  Modular Flask app for sales management and forecasting. Features CRUD for products, customers, and sales; dashboard with KPIs; monthly sales + 6-month forecast (ARIMA/SARIMAX or Linear Regression fallback); top products analysis; CSV export; MySQL or SQLite via SQLAlchemy; Bootstrap UI with Chart.js. Simple deployment for small businesses .



### Additional Strong Open-Source Options



- **[Horilla CRM](https://github.com/horilla/horilla-crm)** — Free and open-source HR and CRM software under LGPL-2.1+. Features role-based access control, REST API with Swagger documentation, webhooks, CSV/Excel import/export, internationalization (20+ languages), and Docker Compose deployment. Enterprise-grade security with CSRF protection, SQL injection protection, and API rate limiting .

- **[SalesIq](https://github.com/badrr06/SalesIq)** — Sales management with forecasting dashboard.

- **Lead Scoring Repositories** — 331+ public repos on GitHub covering XGBoost, CatBoost, LightGBM, WOE/SHAP feature selection, and Optuna hyperparameter tuning .

- **Revenue Intelligence** — Open-source alternatives to Pocus and Common Room detecting buying signals from PostHog + CRM data .

- **Churn Prediction Models** — Retail customer churn with GradientBoosting (84% accuracy, 0.88 ROC AUC) ; Expresso telecom churn with Random Forest + Streamlit .



**Frameworks for building custom systems**: Combine **CRMlytics** for WooCommerce-native predictive analytics, **AI-Driven CRM Analytics** for full-stack lead classification, **b2b-revenue-forecasting** for quota and forecast reconciliation, **ChurnGuard AI** for SaaS churn prediction, and **CallSense** for conversation intelligence to build a complete self-hosted in-CRM predictive analytics stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Predictive analytics tools must comply with data protection regulations (GDPR, CCPA), ethical AI guidelines, and explainability requirements for automated decisioning.

- Self-hosted open-source solutions require proper security hardening, model monitoring, and CRM data governance.



---



**Made for revenue operations teams, sales leaders, CRM administrators, and developers building predictive CRM analytics platforms.**  

Let's make in-CRM predictive analytics more open, explainable, and data-sovereign.
