# Evidence - Tuesday, 2026-06-09

Learner: ____________________
Date: 2026-06-09
Topic: D2 Observability - SLO, SLI, OpenTelemetry

## 1. Daily learning goals
- [ ] I understand what OpenTelemetry SDK and OpenTelemetry Collector do.
- [ ] I understand how Prometheus, Grafana, and Loki work together.
- [ ] I can write SLI/SLO examples for availability and latency.
- [ ] I can explain multi-window burn-rate alerting clearly.

## 2. Evidence of reading and reference study

| Topic | Source | Evidence | Done |
|---|---|---|---|
| OpenTelemetry concepts | opentelemetry.io/docs | screenshot / summary note | [ ] |
| Prometheus basics | prometheus.io/docs | screenshot / summary note | [ ] |
| Grafana basics | grafana.com/docs/grafana/latest | screenshot / summary note | [ ] |
| Loki basics | grafana.com/docs/loki/latest | screenshot / summary note | [ ] |
| SLO chapter | sre.google/sre-book/service-level-objectives | screenshot / summary note | [ ] |
| Burn-rate alerting | sre.google/workbook/alerting-on-slos | screenshot / summary note | [ ] |

## 3. Evidence of rewritten understanding

### 3.1 OpenTelemetry SDK and Collector
- [ ] I wrote a short summary in my own words.
- [ ] I created a flow diagram or written flow for `Application -> OTel SDK -> Collector -> Backend`.
- [ ] I explained the Collector pipeline components:
  - receiver
  - processor
  - exporter

Evidence:
- File or image:
- Short note:

### 3.2 Metrics, logs, and traces
- [ ] I created a comparison of the three telemetry signals.
- [ ] I explained when each signal is useful.

Evidence:
- File or image:
- Short note:

### 3.3 Prometheus, Grafana, and Loki
- [ ] I explained Prometheus for scraping, storing, and querying metrics.
- [ ] I explained Grafana for visualization and alerting.
- [ ] I explained Loki for log aggregation and querying.

Evidence:
- File or image:
- Short note:

## 4. Evidence of SLI and SLO work

### 4.1 Availability
- [ ] I wrote an availability SLI.
- [ ] I wrote an availability SLO.
- [ ] I explained the related error budget.

Write your example here:
```text
Availability SLI =
Availability SLO =
Error budget =
```

Evidence:
- File or image:
- Short note:

### 4.2 Latency
- [ ] I wrote a latency SLI.
- [ ] I wrote a latency SLO.
- [ ] I explained whether the latency measure uses p95, p99, or threshold-based success ratio.

Write your example here:
```text
Latency SLI =
Latency SLO =
Measurement window =
```

Evidence:
- File or image:
- Short note:

## 5. Evidence of burn-rate alert understanding
- [ ] I explained what burn rate means.
- [ ] I explained why two alert windows are used.
- [ ] I wrote notes for:
  - fast alert: `1h x 5m`
  - slow alert: `6h x 30m`

Write your explanation here:
```text
Burn rate =
Fast window alert =
Slow window alert =
```

Evidence:
- File or image:
- Short note:

## 6. Files created or updated today
- [ ] `README.md`
- [ ] `plan-2026-06-09.md`
- [ ] `tasks.md`
- [ ] `otel/README.md`
- [ ] `prometheus/README.md`
- [ ] `grafana/README.md`
- [ ] `loki/README.md`
- [ ] `alert-rules/README.md`
- [ ] `notes/README.md`

## 7. Questions to ask the mentor on Wednesday, 2026-06-10
1.
2.
3.

## 8. End-of-day reflection

### What I understand well
-

### What is still unclear
-

### What I should follow up on during Wednesday or Thursday
-
