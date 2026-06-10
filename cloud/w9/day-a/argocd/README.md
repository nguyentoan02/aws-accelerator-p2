# ArgoCD Notes

## What you should understand
- ArgoCD continuously compares cluster state with Git state.
- The Application resource points ArgoCD to a Git path and target cluster or namespace.
- App-of-apps is a common way to manage multiple platform components from one root application.

## Key concepts to write down
- Application
- sync policy
- automated sync
- self-heal
- prune
- app-of-apps
- sync waves

## Questions to answer in your notes
- How would you split the W8 platform into ArgoCD applications?
- Which resources should be deployed earlier using sync waves?
- What is the minimum bootstrap step to let ArgoCD manage the rest?

## Expected output
- One draft ArgoCD structure for W8.
- One explanation of app-of-apps in your own words.
