# Argo Rollouts Notes

## What you should understand
- Argo Rollouts extends Kubernetes deployment behavior for safer release strategies.
- A Rollout can shift traffic gradually instead of replacing all replicas immediately.
- Pause and analysis steps allow the system to inspect metrics before full promotion.

## Key concepts to write down
- Rollout CRD
- canary steps
- setWeight
- pause
- promote
- abort

## Questions to answer in your notes
- What should the canary step sequence look like for a W8 service?
- At which percentage should the first metric check happen?
- What should happen automatically when a metric crosses the failure threshold?

## Expected output
- One draft canary release sequence.
- One short explanation of Rollout behavior in your own words.
