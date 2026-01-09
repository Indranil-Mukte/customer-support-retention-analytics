# Project Charter - Customer Support & Retention Analytics

## Background
Customer support performance directly affects customer experience and retention. This project analyzes helpdesk ticket data to evaluate operational efficiency, identify bottlenecks, and surface actionable opportunities to improve support outcomes.

## Primary Stakeholder
Support Operations Manager (day-to-day support performance and SLA adherence).

## Business Questions
1. How has ticket volume changed over time, and are there spikes that impact performance?
2. Which ticket types and priorities drive the longest resolution times?
3. What is the SLA breach rate overall and by segment (priority/type/assignee)?
4. Are tickets being reassigned frequently (handoff churn), and does that correlate with slower resolution?

## Key Metrics (KPIs)
- Tickets Created (count)
- Tickets Resolved (count)
- Median Resolution Time (hours)
- SLA Breach Rate (%)
- Reassignment Count / Avg Reassignments per Ticket

## SLA Assumptions (documented)
Initial SLA thresholds (to be validated/refined after reviewing priority values):
- High/Critical: 24 hours
- Medium: 72 hours
- Low: 120 hours

## Data Sources
- issues.csv (ticket-level)
- issues_change_history.csv (assignee/status change events)

## Deliverables
- Cleaned, analysis-ready dataset(s) in `data/processed/`
- EDA notebook with findings
- Power BI dashboard for support performance monitoring
- Recommendations summary with next steps
