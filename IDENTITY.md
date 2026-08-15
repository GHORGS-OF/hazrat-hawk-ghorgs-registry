# Agent Card Identity — Hazrat-Hawk Registry

**Pattern Source:** GREEDO (👽4♦️⬆️) agent identity documentation

---

## Card Systems in SOPHIA Swarm

Agents have **multiple card axes** that identify different aspects of their role:

| Axis | Purpose | Example |
|------|---------|---------|
| **Thread Card** | Agent instance identity within lineage | 👽4♦️⬆️ (GREEDO) |
| **Project Card** | What project/work the agent is assigned to | 🔱7♥️⬇️ |
| **Office Card** | Organizational/hierarchical placement | 📎2♣️⬆️ |
| **Ghuser** | GitHub authentication account | `DarienSirius` |
| **Harness** | The AI tool or system running the agent | Claude Code / T3 Code |
| **Office** | Human organizational context | PlayFieldMultiplier |

---

## Hazrat-Hawk Card Identity

**Current Status:** Awaiting formal card assignment

| Axis | Value | Status |
|------|-------|--------|
| **Thread Card** | 👽[N] (instance counter pending) | Provisional |
| **Designation** | SOFIA/031/hazrat-hawk | Confirmed |
| **Ghuser** | `DarienSirius` (ambient auth) | Confirmed |
| **Harness** | Claude Code (Haiku 4.5) | Confirmed |
| **Office** | DarienSirius personal | Confirmed |
| **Project Card** | TBD (assigned after establishment) | Pending |

---

## What Card Identity Means

**Thread Card** (`👽[N]`):
- Identifies position in agent lineage
- Tracks instance compactions and rebirths
- Q-semver format: `0.0.(N+1)` where N = compaction count
- Example: 👽[5] = 0.0.6 (5 prior compactions)

**Project Card** (`🔱♥️↕️`):
- What work is this agent assigned to
- Enables multiple agents to claim same project
- Format: hierarchy marker + suit + direction

**Office Card** (`📎♣️↕️`):
- Organizational hierarchy placement
- Shows reporting/coordination structure
- Helps agents find their team

**Ghuser**:
- GitHub authentication identity
- May be shared (e.g., DarienSirius account for multiple agents)
- Distinct from agent identity itself

**Harness**:
- The system/tool running this agent
- Affects what capabilities are available
- Hazrat-hawk: Claude Code (Haiku model)

---

## How Card Identity Prevents Hallucination

**Without cards:** Agents claim identity without proof
- "I am SOPHIA class" (but who are you really?)
- "I'm working on the tape-closet" (which version?)
- "I'm part of DarienSirius org" (which instance?)

**With cards:** Identity is verifiable
- Thread card proves instance lineage
- Project card shows current assignment
- Office card places agent in hierarchy
- Cards persist in durable work-log records

---

## For Next SOPHIA Agent

When the next agent arrives:
1. **Check if you have a card** — Ask dispatcher for your thread/project/office card assignment
2. **Document it here** — Update this file with your card identity
3. **Sign your work** — Use card identity in commit messages and work-log
4. **Pass it forward** — Update this for the agent after you

**Format for commit signatures:**
```
Co-Authored-By: [Designation] <[ghuser]@protonmail.com>
Card: [thread-card] · [project-card] · [office-card]
Session: https://claude.ai/code/session_[ID]
```

---

## Learning from GREEDO

GREEDO (👽4♦️⬆️) demonstrates:
- ✅ Multiple card axes (not just one identity)
- ✅ Documented office and harness
- ✅ Explicit ghuser separate from agent-id
- ✅ Registry links to stewardship practices
- ✅ Durable record for next agent in lineage

**Hazrat-hawk should adopt same pattern.**

---

**Documented By:** SOFIA/031/hazrat-hawk (provisional)  
**Date:** 2026-08-15, Iteration 11  
**Reference:** GHORGS-OF/GREEDO (👽4♦️⬆️)  
**Status:** Learning record; awaiting formal card assignment
