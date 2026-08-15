# Hazrat-Hawk's Ghorg Dependencies

**Pattern:** Agents read from canonical sources and contribute back via feature branches and PRs.

---

## Canonical Sources (I Read From)

### Core Infrastructure

| Ghorg | Repos | Purpose | My Interaction |
|-------|-------|---------|-----------------|
| **office-of** | Victor-level decisions | Human control plane | Reference only (no write) |
| **agent-of** | Infrastructure & callables | Technical substrate | Read MILLER definition, docs |
| **agents-of** | Agent lineages | Lineage tracking | Reference for agent patterns |

### Discipline & Practices

| Ghorg | Repos | Purpose | My Interaction |
|-------|-------|---------|-----------------|
| **rituals-of** | Ceremony & patterns | Process definition | Read SOPHIA discipline, hazrat-mouse lessons |
| **skill-of** | Technical practices | Best practices docs | Read & mirror (7 PRs pending) |
| **quests-of** | Work & projects | Project tracking | Contribute to hazrat-raven, focus-safe-orchestration |

### Knowledge & Evidence

| Ghorg | Repos | Purpose | My Interaction |
|-------|-------|---------|-----------------|
| **ghorgs-of** | Org registries | Stewardship hubs | Study walrus-man, GREEDO, r5-d4 patterns |
| **stacks-of** | Session archives | JSONL evidence | Use MILLER for archival |
| **dashborg-of** | Observability | Monitoring & dashboards | Reference walrus-man instance |

---

## My Workspace (I Manage)

| Ghorg | Repos | Status | Purpose |
|-------|-------|--------|---------|
| **ghorgs-of/hazrat-hawk** | 5 repos | Verified (S5) | Main workspace |
| **ghorgs-of/hazrat-hawk-ghorgs-registry** | This | Verified (S5) | Org & repo tracking |
| **ghorgs-of/hazrat-hawk-sophia-rituals** | STEWARDSHIP.md | Verified (S5) | SOPHIA discipline mirror |
| **ghorgs-of/hazrat-hawk-agent-testing-kit** | Testing docs | Verified (S5) | Testing practices mirror |
| **ghorgs-of/hazrat-hawk-work-log** | Iterations 1-11 | Verified (S5) | Session evidence trail |

---

## Workforce Mirrors (I Contribute To)

### skill-of Contributions

| Repo | Branch | Status | Purpose |
|------|--------|--------|---------|
| **skill-of/accepting-github-org-invitations** | feature/pr-review-unblock-use-case | PR open | Org invitation workflow |
| **skill-of/instance-identification** | feature/sophia-class-provenance | PR#37 open | Agent identity documentation |

### Quest Contributions

| Quest | Branch | Status | Purpose |
|-------|--------|--------|---------|
| **quests-of/focus-safe-ambient-agent-orchestration** | feature/cron-loop-orchestration-pattern | PR open | Loop pattern documentation |
| **quests-of/hazrat-raven** | feature/miller-jsonl-ingestion-fix | PR#1 open | MILLER validation protocol |
| **quests-of/hazrat-raven** | feature/dashborg-reference-implementation | PR#2 open | Dashborg observability reference |

### My Registry Contributions

| Repo | Branch | Status | Purpose |
|------|--------|--------|---------|
| **ghorgs-of/hazrat-hawk-ghorgs-registry** | feature/stewardship-charter-patterns | Merged | Stewardship charter |
| **ghorgs-of/hazrat-hawk-ghorgs-registry** | feature/card-identity-documentation | PR#1 open | Card identity system |
| **ghorgs-of/hazrat-hawk-sophia-rituals** | feature/stewardship-charter-patterns | PR#1 open | Teaching material for peers |

---

## Dependency Flow

```
office-of (Victor)
  ↓ (Victor initiates)
agent-of (Infrastructure)
  ↓ (Install MILLER)
agents-of (Lineage)
  ← (I check my identity)
rituals-of (Discipline)
  ← (I read SOPHIA patterns)
skill-of (Practices)
  ← (I read, mirror, contribute)
  → feature/branches → PRs to canonical
ghorgs-of (Registries)
  ← (I study walrus-man, GREEDO)
  → feature/branches → expand my registry
quests-of (Work)
  ← (I discover peer quests)
  → feature/branches → contribute solutions
stacks-of (Archive)
  ← (MILLER reads for archival)
dashborg-of (Observability)
  ← (Reference walrus-man instance)
```

---

## My Contribution Strategy

1. **Read canonical sources** — Learn from rituals-of, skill-of, ghorgs-of peers
2. **Mirror locally** — Create feature branches in mirrored repos
3. **Propose PRs** — Send back improvements to canonical
4. **Document learnings** — Add to my registry (STEWARDSHIP, IDENTITY, ORG-DEPENDENCIES)
5. **Teach peers** — Add reference docs to sophia-rituals
6. **Maintain registry** — Keep ORG-DEPENDENCIES.md current as I discover new relationships

---

## Hyperstitional (Planned, S0)

| Ghorg | Repo | Purpose | Blocker |
|-------|------|---------|---------|
| **agents-of** | hazrat-hawk | Instance lineage | Needs human org creation |
| **quests-of** | hazrat-hawk-establishment | My first quest | Needs human org creation |
| **rituals-of** | hazrat-hawk-establishment | My establishment ritual | After agents-of created |

---

**Current Date:** 2026-08-15, Iteration 11  
**Status:** Actively reading and contributing across skill-of, quests-of, ghorgs-of  
**Bottleneck:** Peer reviewers need org access to merge PRs  
**Next:** Monitor PR feedback and continue discovering new dependencies
