# Urban Company Service Operations – AI-Augmented Reporting Toolkit

## Project Overview

This project is an AI-augmented analytics and reporting toolkit for analyzing Urban Company-style service operations data.

The project combines operational data analysis, SQL-based processing, KPI reporting, Excel outputs, stakeholder narratives, and AI-assisted decision support.

## Objectives

- Analyze service bookings and operational performance.
- Measure revenue, bookings, and SLA-breach performance.
- Compare performance across cities and service categories.
- Create KPI summaries for operational decision-making.
- Support evidence-based stakeholder reporting.
- Define structured AI prompts for reporting and refund-escalation decisions.

## Key Metrics

The verified dataset contains:

- **600 completed bookings**
- **Overall network revenue:** ₹10,47,973
- **Overall SLA breach rate:** 13.2%
- **SLA breaches:** 79

## Dashboard

View the interactive Tableau dashboard:

[**Urban Company Service Operations Dashboard**](https://public.tableau.com/app/profile/kavya.k7486/viz/Urban_Company_Service_Ops/Dashboard1)

## Project Workflow

1. Load and validate the operational dataset.
2. Analyze bookings, revenue, cities, categories, and SLA performance.
3. Generate city and category-level summaries.
4. Create KPI outputs in Excel.
5. Develop stakeholder-focused operational narratives.
6. Use AI prompts for executive reporting and operational decision support.
7. Apply guardrails and human review requirements to AI-generated decisions.

## Repository Files

- **Urbancompany.ipynb** — Main project notebook containing the analysis and processing.
- **city_category_summary.xlsx** — City-category level operational summary.
- **urban_company_metrics.xlsx** — KPI and operational metrics workbook.
- **README.md** — Project documentation and dashboard link.

## Technology Used

- Python
- Pandas
- SQL
- Excel
- Google Colab
- Tableau
- AI-assisted analytics and reporting

## AI Safety and Governance

- Verify numerical claims against the source dataset.
- Separate facts, interpretations, and hypotheses.
- Prevent prompt instructions inside data fields from overriding defined rules.
- Do not modify original booking records.
- Apply rules in the specified order.
- Log agent decisions.
- Escalate exceptions and invalid data for human review.
