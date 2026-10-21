# The Minimalist Entrepreneur — Claude Code Skills

Claude Code skills based on [The Minimalist Entrepreneur](https://www.minimalistentrepreneur.com/) by Sahil Lavingia.

This is the LocalHighStreets copy of the skill collection. Attribution to Sahil Lavingia and the book is retained. The commands below select this repository rather than the upstream `slavingia/skills` repository.

## Completion and remaining work

Snapshot: **21 October 2026**.

| Measure | Status |
|---|---|
| Overall feature/release completion | **Not yet measurable** — no reconciled, acceptance-tested repository-wide baseline was established in this review |
| Tracked-work completion | **N/A** — no eligible GitHub issues in this repository |
| Open tracked work | 0 issues |
| Excluded closures | 0 cancelled/not-planned or unclassified closures |

The tracked percentage is `completed / (completed + open) × 100`, rounded to one decimal place. It counts repository GitHub issues equally; PRs and closures not marked `completed` are excluded. It is **not** a feature-completeness, effort, test-coverage or production-readiness percentage. Jira work, untracked requirements and upstream-project issues are outside this denominator. An empty tracker means unknown scope, not 100% completion.

### Remaining work and acceptance evidence

The following items identify implementation decisions, tracker reconciliation or validation still needed to establish completion; they are not all newly verified code defects.

- Define the LocalHighStreets-specific skill acceptance checklist and track any required adaptations.
- Verify installation and invocation of the declared plugin/skills in the intended host.
- Review skill outputs against representative business scenarios; absence of GitHub issues does not prove this validation is complete.

### Tracked backlog

No open GitHub issues were returned for this repository at the snapshot date. Establish an owner-approved scope and acceptance checklist before assigning an overall percentage.

[Review the current issue tracker](https://github.com/localhighstreets/minimalist-skills/issues?q=is%3Aissue). Reconcile old package scopes, route assumptions and duplicate/superseded tickets against current code before acting on them. Update this dated numerator/denominator and remaining-work list after acceptance changes.

## Installation

In Claude Code:

```
/plugin marketplace add localhighstreets/minimalist-skills
/plugin install minimalist-entrepreneur
```

The checked-in [plugin manifest](.claude-plugin/marketplace.json) declares the `minimalist-entrepreneur` plugin. The [skills](skills) directory contains the skill instructions. Successful installation depends on the host's plugin support.

<details>
<summary>Alternative: install from a local clone</summary>

```bash
git clone https://github.com/localhighstreets/minimalist-skills.git ~/.claude/plugins/skills
```

Then in Claude Code:

```
/plugin marketplace add ~/.claude/plugins/skills
/plugin install minimalist-entrepreneur
```

</details>

## Skills

| Skill | Command | When to use |
|-------|---------|-------------|
| **Find Community** | `/find-community` | Looking for a business idea, trying to find your community |
| **Validate Idea** | `/validate-idea` | Testing if a business idea is worth pursuing |
| **MVP** | `/mvp` | Ready to build your first product, struggling with scope |
| **Processize** | `/processize` | Have a product idea, want to deliver value by hand before writing code |
| **First Customers** | `/first-customers` | Have a product, need to find your first 100 customers |
| **Pricing** | `/pricing` | Setting prices, considering price changes |
| **Marketing Plan** | `/marketing-plan` | Have product-market fit, ready to scale with content |
| **Grow Sustainably** | `/grow-sustainably` | Making decisions about spending, hiring, or scaling |
| **Company Values** | `/company-values` | Defining culture, preparing to hire |
| **Minimalist Review** | `/minimalist-review` | Gut-checking any business decision |

## The Minimalist Entrepreneur Journey

The skills follow the book's progression:

1. **Community** — Start by finding your people
2. **Validate** — Make sure the problem is worth solving
3. **Build** — Ship a manual process, then productize it
4. **Processize** — Turn your product idea into a manual process you can deliver today
5. **Sell** — Get to 100 customers one by one
6. **Price** — Charge something from day one
7. **Market** — Build an audience through content
8. **Grow** — Stay profitable, grow sustainably
9. **Culture** — Build the house you want to live in
10. **Review** — Apply minimalist principles to every decision
