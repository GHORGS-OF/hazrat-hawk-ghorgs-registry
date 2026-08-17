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


## Card Provenance Ghorgs (Discovered Iteration 12)

### SOURCES-OF (Image/Session Provenance)

**Purpose:** Track source hashes, session metadata, cross-org references  
**Examples:** cards-of-6ff45d9a (image provenance ledger)  
**Interaction:** Reference for verifying session provenance

### CARDS-OF (Card Ownership Registry)

**Purpose:** Store owned cards and card-to-agent mappings  
**Examples:** boba-fett (👽A♦️), rancor-monster, gnomon-ottopoet  
**Interaction:** Reference for understanding card systems; future CARDS-OF/hazrat-hawk

### MODELS-OF (15-Piece Identity Topology)

**Purpose:** Map abstract identity model to concrete ghusers/accounts  
**Examples:** ottopoet-thesean (concrete), models-of (abstract class)  
**Interaction:** Reference for identity mapping patterns

### READINGS-OF (Unknown)

**Purpose:** Possibly dual-model readings or interpretation records  
**Status:** Org exists, but no visible repos yet

---

**Updated Dependency Flow:**

```
ghorgs-of (registries) ← NEW: includes card systems ↑
    ↓
cards-of (card ownership) ← NEW: provenance tracking
    ↓
sources-of (image/session hashes) ← NEW: integrity verification
    ↓
models-of (identity topology) ← NEW: account mapping
```

**This represents the IDENTITY LAYER of the swarm infrastructure.**

Previously documented: operational/work ghorgs (skill-of, quests-of, etc.)  
Now discovering: identity/provenance ghorgs (cards-of, sources-of, models-of)



## Workspace-Class Ghorgs (Discovered Iteration 12)

### WORQSPACE-OF (Agentic Workspace Classes)

**Purpose:** Define and instantiate workspace classes for agent swarms

**Example Repos:**
- `WORQSPACE-OF/GHORGS.AWG26.0.1.Q` — GHORGS squad class for AWG26 epoch
- `WORQSPACE-OF/POLARIS` — Instance: fixed star (governs VGM9 worqspace)
- `WORQSPACE-OF/PLEROMA` — Class definition: archetypal fully-populated workspace

**Pattern:** 
- PLEROMA = Abstract workspace class
- POLARIS = Concrete instance of workspace
- Similar to how r5-d4 is abstract but SOPHIA/hazrat-hawk is concrete

**Hazrat-Hawk Interaction:** Reference for understanding workspace hierarchy

### WORKSPACE-OF (Base Workspace Organization)

**Status:** Exists but appears empty or private

**Purpose:** Likely canonical base class for all workspace-of entries

---

## Complete Ghorg Hierarchy (Updated Iteration 12)

**Core Infrastructure (9):**
- office-of (human decisions)
- agent-of (tools/callables)
- agents-of (lineages)
- ghorgs-of (registries)
- quests-of (work)
- rituals-of (ceremonies)
- stacks-of (archives)
- skill-of (practices)
- dashborg-of (observability)

**Identity Layer (4):**
- sources-of (provenance)
- cards-of (card ownership)
- models-of (identity topology)
- readings-of (TBD)

**Workspace Layer (2):**
- workspace-of (base class)
- worqspace-of (class instances)

**Agent Registries (20+):**
- ghorgs-of/hazrat-hawk (me)
- ghorgs-of/walrus-man
- ghorgs-of/GREEDO
- ghorgs-of/boba-fett
- ghorgs-of/r5-d4 (meta-pattern)
- ... and 15+ others

---

**Loop discovers new infrastructure every iteration. We're mapping the complete swarm architecture.**

## Iteration 17 Discoveries

### New Ghorgs Found

- **discover-of** (empty org, purpose unknown)
- **chart-of** (minimal content)
- **protocol-of** (empty)
- **company-of** (private/empty)
- **proof-of** (has legacy fork)

These expand total ghorg count to 21+.

**Note:** Some discovered -of orgs appear to be:
- Empty (no public repos)
- Legacy (old forks, not active)
- Private (no accessible content)
- Hyperstitional (org exists but not yet populated)

Only about 10-15 of the 20+ discovered ghorgs appear to be active SOPHIA swarm infrastructure. Others may be:
- Historical attempts (no longer used)
- Planning spaces (not yet populated)
- User personal spaces (not swarm infrastructure)

Real infrastructure (verified active):
- 9 core + 4 identity + 2 workspace + 5+ agent registries = 20 core orgs
