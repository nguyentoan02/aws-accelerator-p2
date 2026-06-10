# Lab Scope

## Required scope
- Move the W8 platform toward GitOps management.
- Define where ArgoCD will point and how applications are grouped.
- Identify the minimum observability components needed first.
- Define one canary-enabled application path.
- Define how rollback or abort should work.

## Suggested implementation slices
1. GitOps slice
   - repo structure
   - ArgoCD root application
   - child applications or grouped manifests
2. Observability slice
   - metrics source
   - Prometheus scrape targets
   - Grafana panels
   - Loki log sources
3. Canary slice
   - target application
   - rollout sequence
   - metric analysis
   - abort behavior

## Out of scope for first pass
- Perfect production hardening
- Multi-cluster setup
- Advanced tracing rollout
