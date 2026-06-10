# W9 Day A - GitOps and CI/CD

Study date: Monday, 2026-06-08
Track: Self-study D1 GitOps and CI/CD

This folder packages the Day A work for W9. The goal is to move from manual Kubernetes changes toward a Git-driven delivery flow using GitHub Actions and ArgoCD.

## Folder contents
- `plan-2026-06-08.md`: time-boxed study and implementation plan
- `tasks.md`: required and optional checklist
- `evidence.md`: record of commands, screenshots, notes, and outputs
- `workflows/README.md`: notes and draft workflow structure for GitHub Actions
- `argocd/README.md`: notes and draft structure for ArgoCD and app-of-apps
- `notes/README.md`: short summary, decisions, and open questions

## Expected outcomes by the end of the day
1. Explain GitOps in simple and practical language.
2. Explain the difference between plan-on-PR and apply-on-merge.
3. Describe when to use `git revert` and when `kubectl rollout undo` still matters.
4. Draft one GitHub Actions flow for validation on pull requests and sync/apply after merge.
5. Draft one ArgoCD layout that can manage the W8 platform from Git.

## Recommended usage
1. Start with `plan-2026-06-08.md`.
2. Work through `tasks.md`.
3. Fill `workflows/README.md` and `argocd/README.md` while studying.
4. Update `evidence.md` as you go instead of at the end.
