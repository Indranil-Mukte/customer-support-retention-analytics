# Data Cleaning & Quality Decisions

## Key Decisions
- Normalized inconsistent priority labels into 5 standardized categories.
- Capped resolution time at the 99th percentile to limit impact of extreme legacy tickets.
- Computed SLA breach using documented, assumption-based thresholds.
- Derived reassignment counts from issue change history.

## Limitations
- SLA thresholds are assumed and not sourced from internal policy.
- Tickets without resolution dates are excluded from resolution-time metrics.
