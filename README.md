<div align="center">

# 🎯 ROI Lens
### Advanced Marketing Attribution & Budget Optimization Intelligence Platform

Transforming fragmented customer journeys into measurable business impact through probabilistic attribution, behavioral analytics, and AI-driven budget optimization.

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Markov Chains](https://img.shields.io/badge/Attribution-Markov%20Chains-red)
![Shapley Value](https://img.shields.io/badge/Game%20Theory-Shapley-purple)
![Optimization](https://img.shields.io/badge/Budget-Optimization-success)

### 🚀 Attribution Intelligence for Modern Marketing Teams

ROI Lens is an advanced marketing attribution and budget optimization intelligence platform that uncovers the true impact of every marketing channel using Markov Chains, Shapley Attribution, and predictive budget allocation models.

Built to replace legacy last-click attribution, ROI Lens transforms complex customer journeys into actionable ROI insights, optimized campaign spending, and conversion-maximizing growth strategies.

</div>

---

## 📖 Overview

Modern consumers rarely convert through a single touchpoint.

A user may discover a product through Instagram, engage with an Influencer campaign, search for reviews on Google, watch a YouTube video, and finally purchase through an E-commerce marketplace.

Traditional **Last-Click Attribution** assigns 100% credit to the final interaction, creating significant blind spots in marketing performance measurement.

**ROI Lens** solves this challenge by introducing a probabilistic attribution framework that accurately quantifies the contribution of every marketing channel and recommends optimal budget allocation strategies.

---

## 🎯 Business Problem

A leading FMCG enterprise invests over **₹100 Crore** across:

- Instagram
- Google Search
- YouTube
- Influencer Networks
- E-Commerce Marketplaces

Yet critical questions remain unanswered:

❓ Which channels truly drive conversions?

❓ Which channels merely assist purchases?

❓ Where is marketing spend being wasted?

❓ How should future budgets be redistributed?

ROI Lens provides mathematically grounded answers.

---

## 🏗️ Solution Architecture

```text
                         ┌─────────────────────┐
                         │  Raw Campaign Data  │
                         └──────────┬──────────┘
                                    │
                                    ▼
                    ┌────────────────────────────┐
                    │ Data Cleaning & Validation │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │   Bot Traffic Detection    │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ Customer Journey Mapping   │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ Attribution Intelligence   │
                    │ Markov + Shapley Models    │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ True ROI & CPA Analysis    │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ Ad Fatigue & Saturation    │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ Budget Optimization Engine │
                    └──────────┬─────────────────┘
                               │
                               ▼
                    ┌────────────────────────────┐
                    │ Strategic Recommendations  │
                    └────────────────────────────┘
```

---

## ✨ Core Features

### 🔍 Intelligent Bot Detection

Automatically identifies and removes:

- Click Farms
- Timestamp Anomalies
- Non-Human Traffic
- Infinite Interaction Loops
- Fraudulent Conversion Patterns

---

### 🧭 Customer Journey Reconstruction

Rebuilds complete consumer journeys from raw interaction logs.

```text
Instagram
    ↓
YouTube
    ↓
Google Search
    ↓
Marketplace
    ↓
Purchase
```

Provides full-funnel visibility into customer behavior.

---

### ⚡ Multi-Touch Attribution Engine

#### Markov Chain Attribution

Measures channel importance through:

- Transition Probabilities
- Removal Effects
- Conversion Impact Analysis
- Path Dependency Mapping

---

#### Shapley Value Attribution

Uses Cooperative Game Theory to compute:

- Fair Credit Allocation
- Marginal Contribution Analysis
- Channel Synergies
- Revenue Contribution Weights

---

### 📊 True ROI Intelligence

Generates:

- ROI Scores
- Customer Acquisition Cost (CPA)
- Channel Efficiency Metrics
- Attribution Weights
- Conversion Contribution %

---

### 📈 Ad Fatigue Modeling

Models diminishing returns using non-linear saturation curves.

```math
y = α · (xⁿ / (Kⁿ + xⁿ))
```

Helps identify:

- Audience Saturation
- Frequency Caps
- Wasteful Spending Zones
- Budget Efficiency Thresholds

---

### 💰 Budget Optimization Engine

Uses constrained optimization to maximize conversions.

#### Objective Function

```math
Maximize:
Σ f(channel_spend)
```

#### Constraints

```math
Total Brand Budget = ₹10 Crore
```

```math
Channel Spend ≥ 0
```

#### Sample Output

```text
Brand A

Instagram         ₹2.4 Cr
Google Search     ₹3.1 Cr
YouTube           ₹1.7 Cr
Influencers       ₹1.5 Cr
Marketplace       ₹1.3 Cr
```

---

## 📊 Analytical Workflow

### Phase 1 — Attribution Framework

#### Data Engineering

- Data Cleaning
- Timestamp Parsing
- User Journey Construction
- Bot Traffic Removal

#### Attribution Modeling

- Last Click Benchmark
- Markov Attribution
- Shapley Attribution

#### Channel Classification

- Top Funnel Primers
- Mid Funnel Influencers
- Bottom Funnel Closers

---

### Phase 2 — Portfolio Reallocation

#### Diminishing Return Analysis

- Saturation Curves
- Ad Fatigue Detection
- Marginal Efficiency Calculation

#### Optimization

- Budget Constraints
- Conversion Maximization
- Spend Redistribution

#### Strategy Generation

- Channels to Scale
- Channels to Defund
- Frequency Cap Recommendations

---

## 📂 Repository Structure

```text
ROI-Lens/
│
├── data/
│   ├── touchpoints.csv
│   ├── user_profiles.csv
│   └── campaign_spend.csv
│
├── notebooks/
│   ├── attribution_analysis.ipynb
│   ├── roi_analysis.ipynb
│   └── budget_optimization.ipynb
│
├── src/
│   │
│   ├── preprocessing/
│   │   ├── clean_data.py
│   │   ├── bot_detection.py
│   │   └── journey_builder.py
│   │
│   ├── attribution/
│   │   ├── markov_model.py
│   │   ├── shapley_model.py
│   │   └── attribution_engine.py
│   │
│   ├── analytics/
│   │   ├── roi_calculator.py
│   │   ├── cpa_analysis.py
│   │   └── channel_scoring.py
│   │
│   ├── optimization/
│   │   ├── saturation_model.py
│   │   ├── fatigue_detection.py
│   │   └── budget_optimizer.py
│   │
│   └── visualization/
│       ├── dashboards.py
│       └── reporting.py
│
├── reports/
│   └── ROI_Lens_Strategy_Memo.pdf
│
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 📈 Example Insights

| Channel | Last Click Credit | ROI Lens Credit |
|----------|------------------|-----------------|
| Instagram | 8% | 24% |
| Google Search | 42% | 31% |
| YouTube | 11% | 19% |
| Influencers | 6% | 17% |
| Marketplace | 33% | 9% |

### 🔥 Key Discovery

Traditional attribution significantly undervalues top-of-funnel channels.

Instagram and Influencer campaigns appear weak under Last-Click attribution but emerge as major revenue drivers when evaluated using probabilistic attribution models.

---

## 🛠️ Technology Stack

### Data Engineering

- Python
- Pandas
- NumPy

### Attribution Modeling

- Markov Chains
- Shapley Values
- Network Analysis

### Machine Learning

- Scikit-Learn

### Optimization

- SciPy
- Non-Linear Programming

### Visualization

- Plotly
- Matplotlib
- Seaborn

### Development

- Jupyter Notebook
- Git
- GitHub

---

## 📌 Business Impact

ROI Lens empowers organizations to:

✅ Eliminate attribution blind spots

✅ Measure true channel contribution

✅ Reduce inefficient marketing spend

✅ Increase campaign ROI

✅ Optimize budget allocation

✅ Maximize conversions without increasing spend

---

## 🔮 Future Roadmap

### Version 2.0

- Real-Time Attribution Dashboard
- Automated Marketing Intelligence
- Reinforcement Learning Budget Allocation
- Predictive Campaign Recommendations
- Cross-Device Identity Resolution
- AI Marketing Copilot

---

## 📸 Sample Dashboard Preview

```text
┌──────────────────────────────────────────┐
│            ROI LENS DASHBOARD            │
├──────────────────────────────────────────┤
│ Total Spend          ₹100 Cr             │
│ Total Revenue        ₹385 Cr             │
│ Overall ROI          3.85x               │
├──────────────────────────────────────────┤
│ Top Primer           Instagram           │
│ Top Closer           Google Search       │
│ Most Efficient       Influencer Network  │
│ Highest ROI          YouTube             │
└──────────────────────────────────────────┘
```

---

## 👨‍💻 Author

### Aditya Ranjan

Product • Data • Strategy

Built as a Business Intelligence and Marketing Analytics platform focused on solving enterprise-scale attribution and budget optimization challenges through advanced probabilistic modeling and data-driven decision making.

---

<div align="center">

## ⭐ From Clicks to Conversions. From Attribution to Action.

If you found this project interesting, consider starring the repository.

</div>
