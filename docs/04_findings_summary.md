# Exploratory Data Analysis - Key Findings

## Overall Support Performance
- Among resolved tickets, the overall SLA breach rate is **~73%**, indicating significant opportunities to improve support efficiency.
- Resolution times exhibit a long-tailed distribution, with a small subset of tickets remaining unresolved for extremely long durations.

## Ticket Volume Trends
- Weekly ticket volume remains consistently high over time, suggesting a sustained operational workload rather than short-term spikes.
- This reinforces the need for structural process improvements rather than temporary capacity adjustments.

## Resolution Time by Priority
- Median resolution time varies significantly by priority:
  - **Critical:** ~82 hours
  - **High:** ~116 hours
  - **Medium:** ~222 hours
  - **Low:** ~187 hours
  - **Unknown:** ~728 hours
- Tickets with **Unknown priority take substantially longer to resolve**, highlighting gaps in triage and prioritization processes.

## SLA Breach Analysis
- SLA breach rates by priority:
  - **Unknown:** ~83%
  - Medium: ~70%
  - Critical: ~65%
  - High: ~63%
  - Low: ~61%
- Despite faster median resolution for Critical tickets, SLA breaches remain high across all categories, suggesting that current SLA thresholds may be misaligned with actual operational capacity.

## Reassignments and Resolution Time
- Tickets with multiple reassignments show a strong increase in median resolution time.
- Tickets reassigned more than 3–4 times take **several times longer** to resolve than tickets with fewer handoffs.
- This indicates that ownership clarity and routing efficiency are key drivers of support performance.

## Key Takeaways
- Missing or inconsistent priority assignment is a major contributor to delayed resolution and SLA breaches.
- Reducing unnecessary ticket handoffs could materially improve resolution times.
- Standardizing triage and enforcing priority assignment at ticket creation represent high-impact improvement opportunities.
