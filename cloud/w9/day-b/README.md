# W9 Day B - Observability, SLO, SLI, and OpenTelemetry

Study date: Tuesday, 2026-06-09
Track: Self-study D2 Observability

This folder is a working package for the Tuesday self-study session. It is designed to help you study, produce clear outputs, and keep evidence of what you learned.

## Folder contents
- `plan-2026-06-09.md`: a time-boxed study plan for the day
- `tasks.md`: a checklist of required and optional tasks
- `evidence.md`: a structured evidence file for screenshots, notes, and outputs
- `otel/`: notes for OpenTelemetry SDK and Collector
- `prometheus/`: notes for metrics, scraping, and PromQL
- `grafana/`: notes for dashboards, visualization, and alerting
- `loki/`: notes for logs and log querying
- `alert-rules/`: notes for SLI, SLO, error budget, and burn-rate alerts
- `notes/`: summary notes and open questions

## Expected outcomes by the end of the day
1. Explain the observability flow: application -> OpenTelemetry SDK -> OpenTelemetry Collector -> Prometheus/Loki -> Grafana.
2. Explain the role of metrics, logs, and traces, and when each one is useful.
3. Write one availability SLI/SLO example and one latency SLI/SLO example.
4. Explain the purpose of a multi-window burn-rate alert, including:
   - fast detection with `1h x 5m`
   - slow and sustained detection with `6h x 30m`
5. Collect enough evidence to show both study effort and concrete outputs.

## Recommended usage
1. Start with `plan-2026-06-09.md`.
2. Work through `tasks.md`.
3. Write notes into the topic folders while studying.
4. Update `evidence.md` throughout the day instead of waiting until the end.
