# Project4 – Advancement Portfolio and Fundraising Stability Analysis Repository

## Overview

This repository contains a synthetic, analysis-ready project focused on evaluating **donor profile structures, portfolio coverage, fundraising staff retention, and campaign and membership retention indicators** within the Advancement function of a mission-driven nonprofit organization.

The analysis is designed to support **executive leadership decision-making** through a comparative review across a **three-year period (FY2022–FY2024)**. It reflects a lean advancement function responsible for donor cultivation, annual fundraising activity, grant support, foundation support, membership stewardship, and targeted donor engagement.

All data included in this repository is **synthetic** and created solely for demonstration, portfolio, and analytical workflow purposes. It does **not** represent any real organization, donor base, employee history, campaign, or fundraising performance record.

---

## Project Purpose

The purpose of this repository is to provide decision-ready insights on:

- donor portfolio structure and segmentation
- portfolio coverage across fundraising staff
- fundraising staff retention and stability
- campaign and membership retention indicators
- donor engagement patterns across a three-year period
- leadership recommendations grounded in operational analysis

This project is intended to help leadership assess whether the current Advancement structure is sustainable, whether donor coverage is appropriately distributed, and where retention or engagement risks may exist.

---

## Core Questions

This repository is designed to answer the following questions:

1. **Portfolio Coverage**
   - How are donor portfolios structured across the Advancement function?
   - Are donors distributed appropriately across fundraisers and engagement tiers?
   - Are there signs of uneven coverage, over-assignment, or unmanaged segments?

2. **Donor Profile Structure**
   - How are donors segmented by contribution level, giving history, and engagement profile?
   - What portion of the donor base is actively assigned, stewarded, or at risk of limited engagement?

3. **Fundraising Staff Retention and Stability**
   - What are the three-year retention and attrition trends among fundraising staff?
   - Are there donor-facing functions with elevated turnover risk?
   - Where might staffing instability affect donor continuity?

4. **Campaign and Membership Retention**
   - How have campaign participation and membership retention changed across the three-year period?
   - Are there patterns in renewal, lapse, or re-engagement that leadership should monitor?
   - How do donor engagement patterns connect to retention outcomes?

5. **Leadership Decision Support**
   - Where are the most significant risks in donor coverage and fundraising continuity?
   - What structural or operational adjustments should leadership consider?
   - What indicators should be monitored going forward?

---

## Scope of Analysis

The repository includes four primary analytical components.

### 1. Donor Profile and Portfolio Structure

This section evaluates how donor records are segmented and assigned across the Advancement function.

It includes:
- donor segmentation by giving tier
- engagement history categories
- portfolio assignment structure
- assigned versus unassigned donor coverage
- portfolio distribution across fundraising staff
- concentration of donors within key giving segments

### 2. Portfolio Coverage Analysis

This section reviews whether donor portfolios appear balanced and adequately managed.

It includes:
- donor counts by assigned fundraiser
- donor coverage by contribution tier
- active portfolio versus unmanaged donor segments
- portfolio concentration patterns
- staff-to-portfolio coverage summaries
- identification of possible coverage gaps

### 3. Fundraising Retention and Stability

This section examines staffing continuity and turnover patterns within the Advancement team.

It includes:
- three-year staff retention and attrition trends
- tenure patterns across donor-facing functions
- continuity risks affecting stewardship and cultivation
- identification of roles or functions with elevated turnover patterns
- summary indicators relevant to operational sustainability

### 4. Campaign and Membership Retention Indicators

This section evaluates fundraising participation and retention patterns over time.

It includes:
- membership renewal and lapse trends
- campaign participation trends
- donor re-engagement indicators
- retention by donor segment
- year-over-year comparisons in participation stability
- summary metrics supporting leadership review

---

## Repository Contents

```text
Project4-advancement-portfolio-fundraising-stability-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   │   ├── synthetic_staff_roster.csv
│   │   ├── synthetic_retention_history.csv
│   │   ├── synthetic_donor_summary.csv
│   │   ├── synthetic_portfolio_assignments.csv
│   │   ├── synthetic_membership_retention.csv
│   │   └── synthetic_campaign_participation.csv
│   │
│   └── processed/
│       └── .gitkeep
│
├── notebooks/
│   ├── 01_data_validation_and_preparation.ipynb
│   ├── 02_donor_profile_and_portfolio_structure.ipynb
│   ├── 03_portfolio_coverage_analysis.ipynb
│   ├── 04_fundraising_retention_and_stability.ipynb
│   └── 05_campaign_and_membership_retention.ipynb
│
├── src/
│   ├── __init__.py
│   ├── config.py
│   ├── data_loader.py
│   ├── data_generation.py
│   ├── donor_analysis.py
│   ├── portfolio_analysis.py
│   ├── retention_analysis.py
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
