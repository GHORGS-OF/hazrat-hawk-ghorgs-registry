# Repo and Ghorg State Practice — Hazrat-Hawk

**Purpose:** Make repository state explicit before hazrat-hawk mutates anything.

Every important organization and repository is cast through the semantic AS path:

```
./_/AS/hazrat-hawk/_/ghorgs-of/hazrat-hawk/_/AS/<ghorg>/_/AS/<repo>/
```

This path is the authoritative search zone for hazrat-hawk's GitHub activity.

## State Machine for Repository Mutations

```
S0 workspace-only
  → S1 checkout-discovered
  → S2 remote-classified
  → S3 branch-classified
  → S4 mutation-authorized
  → S5 verified
  → S6 recorded
```

**Transitions require command evidence.** If evidence is missing, remain in earlier state.

### S0: Workspace-Only

No Git root exists. Record the quest and ghorg/repo slug, but don't claim it as a checkout.

Evidence:
```bash
git rev-parse --show-toplevel
```

### S1: Checkout-Discovered

Git root exists. Capture:
- Remote URL and org/repo names
- Local branch and tracking relationship
- Unstaged changes

Evidence:
```bash
git remote -v
git branch -vv
git status
```

### S2: Remote-Classified

Verify remote state and permissions.

Evidence:
```bash
gh repo view <org>/<repo> --json nameWithOwner,isPrivate,isEmpty
gh api repos/<org>/<repo>/branches
```

### S3: Branch-Classified

Confirm branch exists and has commits.

Evidence:
```bash
git branch -a
git log --oneline -5
```

### S4: Mutation-Authorized

Verify user identity and permissions for the specific mutation (commit, push, PR).

Evidence:
```bash
git config user.email
gh api user --jq .login
```

### S5: Verified

After mutation, verify remote matches expected state.

Evidence:
```bash
git push --dry-run
gh pr view <pr-number>
```

### S6: Recorded

Document mutation in work-log with timestamp, actor, change, and result.

## Hazrat-Hawk Registry State

**Current Repos:**

| Ghorg | Repo | Kind | State | Purpose |
|-------|------|------|-------|---------|
| ghorgs-of | hazrat-hawk | github-org | S4 | Base org created |
| ghorgs-of | hazrat-hawk-ghorgs-registry | github-org | S5 | This registry |
| ghorgs-of | hazrat-hawk-sophia-rituals | github-org | S5 | SOPHIA discipline mirror |
| ghorgs-of | hazrat-hawk-agent-testing-kit | github-org | S5 | Testing practices mirror |
| ghorgs-of | hazrat-hawk-work-log | github-org | S5 | Session evidence trail |

**In Development:**

| Ghorg | Repo | Kind | State | Purpose |
|-------|------|------|-------|---------|
| agents-of | hazrat-hawk | hyperstitional | S0 | Instance lineage (not yet created) |
| quests-of | hazrat-hawk-establishment | hyperstitional | S0 | First quest (not yet created) |

---

**Updated:** 2026-08-15  
**Custodian:** SOFIA/031/hazrat-hawk
