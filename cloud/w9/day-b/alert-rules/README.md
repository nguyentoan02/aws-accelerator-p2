# Alert Rules, SLI, SLO, and Burn Rate Notes

## Availability SLI and SLO
```text
Sample SLI:
successful requests / total requests

Sample SLO:
99.9% availability over 30 days
```

## Latency SLI and SLO
```text
Sample SLI:
percentage of requests completed under 300 ms

Sample SLO:
95% of requests complete under 300 ms over 30 days
```

## Error budget
- Error budget is the amount of unreliability a service is allowed before it violates the SLO.
- A stricter SLO gives a smaller error budget.
- Burn-rate alerts help detect when the budget is being consumed too quickly.

## Burn rate concepts to understand
- Burn rate shows how fast the service is spending its error budget.
- A fast alert is useful for severe, sudden incidents.
- A slow alert is useful for long-running or gradually worsening problems.

## Questions to answer in your notes
- Why is alerting on raw error count weaker than alerting on SLO burn rate?
- Why do teams often use more than one alert window?
- What kind of outage would trigger the fast alert but not the slow alert, and vice versa?

## Expected output
- Two clear SLI/SLO examples.
- One plain-language explanation of burn-rate alerting.
- One pseudo alert rule or pseudo query that shows the idea.
