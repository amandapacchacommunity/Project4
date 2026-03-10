# Project4 – Advancement Compensation and Portfolio Analysis Repository

## Overview

This repository contains a synthetic, analysis-ready project designed to evaluate compensation competitiveness, fundraising staff retention, donor portfolio coverage, and role alignment within the Advancement function of a mission-driven nonprofit organization operating with an approximate **$5M annual budget**.

The project is structured to support **executive leadership decision-making** through comparative analysis across a **three-year period (FY2022–FY2024)**. It focuses on a lean advancement team responsible for donor cultivation, annual fundraising initiatives, grant support, foundation relations, membership stewardship, and emerging major gift development.

All data included in this repository is **synthetic** and created solely for demonstration, portfolio, and analytical workflow purposes. It does **not** represent any real organization, donor base, compensation record, or employee history.

---

## Project Purpose

The purpose of this repository is to provide decision-ready insights on:

- advancement compensation competitiveness
- fundraising staff retention and attrition risk
- donor portfolio distribution and staff coverage
- role alignment across fundraising functions
- relationship between staffing structure and fundraising expectations
- leadership recommendations grounded in comparative and operational analysis

This analysis is intended to help leadership assess whether the current Advancement structure is sustainable, competitive, and aligned with fundraising strategy.

---

## Core Questions

This repository is designed to answer the following questions:

1. **Compensation Competitiveness**
   - How do advancement salaries compare to similar nonprofit organizations with budgets between **$3M and $10M**?
   - Are donor-facing staff compensated in a way that aligns with portfolio complexity and fundraising expectations?

2. **Retention and Stability**
   - What are the three-year retention and attrition trends within the Advancement team?
   - Are there roles with elevated turnover risk?
   - Is compensation competitiveness associated with retention outcomes?

3. **Role and Portfolio Structure**
   - How are advancement roles distributed across major gifts, annual giving, grants, stewardship, membership, and operations?
   - Are portfolio sizes and donor assignments reasonable relative to staff capacity?
   - Is donor coverage consistent across gift tiers and engagement segments?

4. **Fundraising Strategy Alignment**
   - Does the current team structure support the organization’s fundraising model?
   - Are staffing expectations aligned with campaign participation, donor engagement, and revenue growth goals?

5. **Leadership Decision Support**
   - What changes to compensation, staffing, or portfolio allocation should leadership consider?
   - Where are the most significant structural risks and opportunities?

---

## Scope of Analysis

The repository includes four primary analytical components.

### 1. Advancement Compensation Benchmarking

This section evaluates salary and total compensation trends for advancement roles across FY2022–FY2024.

It includes:
- role-by-role salary comparisons
- synthetic market benchmarks for comparable nonprofits
- compensation growth over time
- comparison of salary positioning relative to fundraising responsibility
- review of alignment between portfolio size, role scope, and compensation

### 2. Fundraising Retention and Stability

This section reviews staffing continuity and turnover risk across the Advancement function.

It includes:
- three-year staff retention and attrition patterns
- average tenure by role type
- turnover concentration in donor-facing positions
- comparison of compensation positioning and retention outcomes
- identification of roles with elevated instability risk

### 3. Advancement Role and Portfolio Structure

This section examines staffing design and donor portfolio coverage.

It includes:
- distribution of roles across advancement functions
- portfolio segmentation by donor tier and engagement history
- donor coverage by assigned staff
- comparison of portfolio size against staff capacity
- review of role scope relative to fundraising strategy

### 4. Fundraising Strategy and Donor Engagement Alignment

This section evaluates whether the current Advancement structure supports the organization’s fundraising model.

The fundraising model represented in this repository includes:
- individual giving
- membership giving
- grant and foundation support
- small-scale donor events
- targeted donor cultivation
- stewardship of mid-level and emerging major donors

This component explores whether the team structure is positioned to support both ongoing fundraising operations and longer-term revenue growth.

---

## Repository Contents

```text
Project4-advancement-compensation-portfolio-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── synthetic_staff_roster.csv
│   │   ├── synthetic_compensation_history.csv
│   │   ├── synthetic_portfolio_assignments.csv
│   │   ├── synthetic_donor_summary.csv
│   │   ├── synthetic_retention_history.csv
│   │   └── synthetic_market_benchmark.csv
│   │
│   └── processed/
│       └── .gitkeep
│
├── notebooks/
│   ├── 01_data_validation_and_preparation.ipynb
│   ├── 02_compensation_benchmarking.ipynb
│   ├── 03_retention_and_turnover_analysis.ipynb
│   ├── 04_portfolio_structure_analysis.ipynb
│   └── 05_leadership_summary_outputs.ipynb
│
├── src/
│   ├── __init__.py
│   ├── config.py
│   ├── data_loader.py
│   ├── data_generation.py
│   ├── compensation_analysis.py
│   ├── retention_analysis.py
│   ├── portfolio_analysis.py
│   └── visualization.py
│
├── outputs/
│   ├── charts/
│   │   └── .gitkeep
│   ├── tables/
│   │   └── .gitkeep
│   └── reports/
│       └── .gitkeep
│
└── docs/
    ├── project_brief.md
    ├── methodology.md
    ├── data_dictionary.md
    └── leadership_recommendations_template.md
