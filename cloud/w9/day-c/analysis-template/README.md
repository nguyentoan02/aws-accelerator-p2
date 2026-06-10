# AnalysisTemplate Notes

## What you should understand
- AnalysisTemplate defines how rollout analysis reads metrics and decides pass, fail, or inconclusive.
- Prometheus queries are commonly used to evaluate error rate or latency during canary.
- Good thresholds should reflect service health, not arbitrary numbers.

## Key concepts to write down
- metric provider
- query
- interval
- count
- success condition
- failure condition
- abort criteria

## Questions to answer in your notes
- Which metric is the safest first gate for W8: error rate, latency, or another signal?
- What threshold would count as a failed canary?
- How long should the system observe before making a promotion decision?

## Expected output
- One draft analysis template idea.
- One pseudo query and threshold set.
