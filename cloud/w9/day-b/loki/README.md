# Loki Notes

## What you should understand
- Loki is used for centralized log aggregation and querying.
- Loki is commonly used with Grafana for operational log analysis.
- Loki indexes labels efficiently and keeps the log content model simpler than some full-text systems.

## Key concepts to write down
- Log streams
- Labels
- Basic filtering and querying
- Why logs are still necessary even when metrics already exist

## Questions to answer in your notes
- What kinds of production problems are easier to debug with logs than with metrics alone?
- Which labels are useful for logs, and which labels could create unnecessary cardinality?
- Which application or platform logs from W8 would be most important to collect first?

## Expected output
- One short explanation of Loki in your own words.
- One example of a log source you would send into Loki.
