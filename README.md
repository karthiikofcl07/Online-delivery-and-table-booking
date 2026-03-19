# Cognifyz Technologies — Data Analytics Internship

## Price Range vs. Online Delivery & Table Booking

**Analyst:** Karthikeyan Thirunavukkarasu
**Organization:** Cognifyz Technologies
**Dataset:** Cognifyz Restaurant Dataset · 9,551 records · 21 features

---

## Project Overview

This project delivers a statistical analysis of the relationship between restaurant price tiers and the availability of online delivery and table booking services. The analysis answers whether higher-priced restaurants are more or less likely to offer these digital service capabilities — with results validated through formal hypothesis testing.

---

## Repository Structure

```
cognifyz_project/
├── price_range_analysis.ipynb   — Main analysis notebook (run this in VS Code)
├── cognifyz_dataset.csv         — Source dataset
├── README.md                    — This file
├── plot_overview.png            — Dataset overview charts (auto-generated)
├── plot_delivery.png            — Online delivery analysis charts
├── plot_booking.png             — Table booking analysis charts
├── plot_combined.png            — Heatmap and stacked comparison
└── plot_deepdive.png            — Cost and rating deep-dive charts
```

---

## Key Findings

| Price Tier | Restaurants | Online Delivery % | Table Booking % |
|---|---|---|---|
| Budget (Tier 1) | 4,444 | ~28.7% | ~5.6% |
| Moderate (Tier 2) | 3,113 | ~22.1% | ~10.2% |
| Premium (Tier 3) | 1,408 | ~11.0% | ~28.9% |
| Luxury (Tier 4) | 586 | ~6.3% | ~45.4% |

**Online Delivery** — adoption is highest in budget restaurants and declines monotonically with price tier. This is a volume-driven, budget-segment strategy.

**Table Booking** — adoption rises sharply with price, peaking at luxury tier. Premium dining experiences are strongly correlated with reservation capability.

**Statistical Tests** — Chi-Square tests confirm both relationships are statistically significant (p ≪ 0.05). Cramér's V confirms a moderate-to-strong association for table booking.

---

## Setup Instructions

### Prerequisites

- Python 3.8 or higher
- VS Code with the Jupyter extension installed

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter nbformat
```

### Run the Notebook

1. Open VS Code
2. Open the `cognifyz_project/` folder
3. Open `price_range_analysis.ipynb`
4. Select your Python interpreter (Python 3.8+)
5. Click **Run All** or execute cells sequentially

---

## Analysis Sections

**Section 1 — Exploratory Data Analysis**
Dataset profiling, price range distribution, and service availability class balance.

**Section 2 — Online Delivery vs. Price Range**
Grouped bar charts, percentage tables, and trend lines showing delivery adoption per tier.

**Section 3 — Table Booking vs. Price Range**
Equivalent analysis for table booking availability with directional comparison.

**Section 4 — Combined Heatmap and Stacked Analysis**
Side-by-side heatmap, stacked proportional bars for both services simultaneously.

**Section 5 — Statistical Significance Testing**
Chi-Square test of independence, p-values, degrees of freedom, and Cramér's V effect size.

**Section 6 — Average Cost and Rating Deep-Dive**
Violin plots of cost distributions, aggregate rating by tier, and service correlation with quality.

---

## Technologies Used

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Pandas | Data manipulation and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Primary visualization library |
| Seaborn | Heatmaps and statistical plots |
| SciPy | Chi-Square hypothesis testing |
| Jupyter | Interactive notebook environment |

---

## Analyst

**Karthikeyan Thirunavukkarasu**
Data Analytics Intern — Cognifyz Technologies

- LinkedIn: [linkedin.com/in/karthikeyan-thirunavukkarasu-2a2949305](https://www.linkedin.com/in/karthikeyan-thirunavukkarasu-2a2949305)
- GitHub: [github.com/karthiikofcl07](https://github.com/karthiikofcl07)

---

*This project is part of the Cognifyz Technologies Data Analytics Internship program.*
