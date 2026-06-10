# Evidence - Monday, 2026-06-08

Learner: ____________________
Date: 2026-06-08
Topic: D1 GitOps and CI/CD

## 1. Daily learning goals
- [ ] I understand GitOps and why Git becomes the source of truth.
- [ ] I understand PR validation versus merge-based deployment.
- [ ] I understand how ArgoCD reconciles cluster state from Git.
- [ ] I can explain rollback options clearly.

## 2. Evidence of reading and reference study

| Topic | Source | Evidence | Done |
|---|---|---|---|
| GitOps principles | opengitops.dev | screenshot / summary note | [ ] |
| GitHub Actions basics | docs.github.com/en/actions | screenshot / summary note | [ ] |
| ArgoCD basics | argo-cd.readthedocs.io | screenshot / summary note | [ ] |
| App of Apps | argo-cd.readthedocs.io | screenshot / summary note | [ ] |

## 3. Evidence of rewritten understanding

### 3.1 GitOps
- [ ] I wrote a short explanation in my own words.
- [ ] I described pull-based reconciliation.
- [ ] I noted one benefit over manual `kubectl apply`.

Evidence:
- File or image:
- Short note:

### 3.2 GitHub Actions flow
- [ ] I drafted one PR validation flow.
- [ ] I drafted one merge-based deployment or sync flow.
- [ ] I identified the checks that must pass before merge.

Evidence:
- File or image:
- Short note:

### 3.3 ArgoCD structure
- [ ] I explained Application and sync policy.
- [ ] I described app-of-apps.
- [ ] I wrote one draft layout for W8.

Evidence:
- File or image:
- Short note:

## 4. Rollback notes
- [ ] I compared `git revert` and `kubectl rollout undo`.
- [ ] I explained which action restores desired state in GitOps.

Write your comparison here:
```text
git revert =
kubectl rollout undo =
When to use which =
```

## 5. Files created or updated today
- [ ] `README.md`
- [ ] `plan-2026-06-08.md`
- [ ] `tasks.md`
- [ ] `workflows/README.md`
- [ ] `argocd/README.md`
- [ ] `notes/README.md`

## 6. Questions to ask the mentor
1.
2.
3.

## 7. End-of-day reflection

### What I understand well
-

### What is still unclear
-
