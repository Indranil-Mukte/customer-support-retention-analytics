# Customer Support & Retention Analytics

End-to-end data analytics project analyzing real-world customer support ticket data to evaluate operational performance, identify SLA bottlenecks, and provide actionable recommendations.

---

## Objective
To assess customer support efficiency by analyzing ticket volume, resolution time, SLA adherence, and operational drivers, and to communicate insights through a stakeholder-ready Power BI dashboard.

---

## Dataset
- Real-world helpdesk ticket data (publicly available, anonymized)
- ~66,000 support tickets across multiple issue types and priorities
- Includes ticket lifecycle timestamps, priority, status, and reassignment history

---

## Tools & Technologies
- **Python** (pandas, NumPy, Matplotlib)
- **Exploratory Data Analysis (EDA)**
- **Power BI** (dashboarding & KPI reporting)
- **GitHub** (version control & documentation)

---

## Project Workflow
1. Data auditing and quality assessment
2. Data cleaning and feature engineering
3. KPI definition and SLA rule formulation
4. Exploratory analysis to identify performance drivers
5. Power BI dashboard development
6. Business recommendations and documentation

---

## Key KPIs
- Tickets Created
- Tickets Resolved
- Median Resolution Time (hours)
- SLA Breach Rate
- Average Reassignments per Ticket

---

## Key Insights
- Tickets with missing or undefined priority labels showed the longest resolution times and highest SLA breach rates.
- Resolution time increased significantly as ticket reassignments increased, indicating handoff inefficiencies.
- Certain issue types consistently underperformed SLA targets, highlighting opportunities for targeted process improvements.

---

## Dashboard Overview
The Power BI dashboard provides a one-page operational view for support managers, enabling quick identification of workload trends, SLA risks, and root causes impacting resolution efficiency.

**Dashboard Highlights**
- Ticket volume trends over time
- SLA breach rates by priority and issue type
- Resolution time distribution across priorities
- Impact of ticket reassignments on resolution time

---

## Recommendations
- Enforce priority assignment at ticket intake to reduce delays caused by untriaged requests.
- Reduce unnecessary ticket reassignments through clearer ownership and routing rules.
- Focus process improvements on issue types with consistently high SLA breach rates.

Detailed recommendations are documented in `docs/05_recommendations.md`.

---

## Repository Structure
customer-support-retention-analytics/
├── README.md
├── requirements.txt
├── data/
│ ├── raw/ # raw data (not committed)
│ └── processed/ # cleaned, analysis-ready data
├── notebooks/
│ ├── 01_data_audit.ipynb
│ ├── 02_cleaning_and_features.ipynb
│ └── 03_eda_support_performance.ipynb
├── docs/
│ ├── 00_data_source.md
│ ├── 01_project_charter.md
│ ├── 02_data_dictionary.md
│ ├── 03_data_quality_checks.md
│ ├── 04_findings_summary.md
│ └── 05_recommendations.md
├── reports/
│ └── figures/
└── bi/
└── customer_support_dashboard.pbix

---

## Outcome
This project demonstrates the ability to perform end-to-end data analysis, translate insights into business recommendations, and communicate findings through effective dashboards for operational decision-making.
