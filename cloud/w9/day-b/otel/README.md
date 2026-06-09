# OpenTelemetry Notes

## What you should understand
- OpenTelemetry is a standard framework for generating and transporting telemetry.
- The SDK usually lives inside the application and creates metrics, logs, and traces.
- The Collector is a separate service that receives, processes, and exports telemetry data.

## Key concepts to write down
- Signals:
  - metrics
  - logs
  - traces
- Collector pipeline:
  - receivers
  - processors
  - exporters
- End-to-end flow:
  - application -> SDK -> Collector -> backend

## Questions to answer in your notes
- Why would a team use a Collector instead of sending telemetry directly from the app to every backend?
- What is the difference between instrumentation and exporting?
- Which parts usually run inside the application, and which parts usually run outside it?

## Expected output
- One simple flow diagram or written flow.
- One short explanation of SDK vs Collector in your own words.
