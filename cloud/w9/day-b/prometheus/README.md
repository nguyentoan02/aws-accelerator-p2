# Prometheus Notes

## What you should understand
- Prometheus collects metrics, usually by scraping HTTP endpoints on a schedule.
- Prometheus stores data as time series with labels.
- PromQL is used to query and aggregate metric data.

## Key concepts to write down
- What scraping means
- Metric names and labels
- Counters, gauges, histograms
- Basic use of `rate`, `sum`, and label filtering
- One example query for an availability SLI

## Questions to answer in your notes
- Why are labels powerful, and what problems can happen if labels are poorly designed?
- Why are counters commonly used for request totals and error totals?
- When would you use a histogram for latency instead of a simple average?

## Expected output
- One short explanation of the Prometheus metric flow.
- One sample query that could support an SLI.
