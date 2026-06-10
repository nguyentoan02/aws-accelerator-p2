# W9 Lab - GitOps-ify W8 Platform and Bolt On Observability and Canary

This folder is for the Thursday-Friday lab work. It connects Day A, Day B, and Day C into one integrated platform outcome.

## Lab goal
Turn the W8 Kubernetes platform into a GitOps-managed system with observability signals and a canary release path that can auto-abort when metrics degrade.

## Folder contents
- `scope.md`: what the lab should include
- `tasks.md`: implementation checklist
- `deliverables.md`: expected outputs and demo points
- `evidence.md`: commands, screenshots, and proof of work

## End state to aim for
1. W8 manifests are managed by Git and reconciled through ArgoCD.
2. The platform has observable metrics, dashboards, and alert intent.
3. At least one release path is defined with canary and abort logic.
4. You can explain the full path from commit to cluster to monitoring to rollback.
