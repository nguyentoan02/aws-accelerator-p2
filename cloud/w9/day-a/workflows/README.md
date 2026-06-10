# GitHub Actions Notes

## What you should understand
- GitHub Actions can validate changes before they are merged.
- A safe workflow separates verification on pull requests from deployment after merge.
- CI should block bad manifests early before ArgoCD or the cluster sees them.

## Key concepts to write down
- pull request trigger
- push or merge trigger
- branch protection
- validation jobs
- artifact or manifest checks

## Questions to answer in your notes
- Which checks should run on every pull request for W8 manifests?
- What should happen only after merge to the main branch?
- Which failures should block merge immediately?

## Expected output
- One draft PR workflow.
- One draft merge workflow or sync trigger explanation.
