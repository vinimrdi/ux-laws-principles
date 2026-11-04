<div align="center">

# UX Laws & Principles

**Evidence-based UX for agents that don’t invent laws.**

Laws, heuristics, Gestalt, cognitive models, and accessibility — applied with a method, not as slogans.

[![License: CC BY 4.0](https://img.shields.io/badge/docs-CC%20BY%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)
[![Skill](https://img.shields.io/badge/skill-v1.4.2-blue?style=flat-square)](skills/ux-laws-principles/SKILL.md)
[![Language](https://img.shields.io/badge/language-English-blue?style=flat-square)](#language)
[![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)

**No fake citations. No “this violates Hick’s Law” without a task. No dark patterns dressed as psychology.**

[Skill](skills/ux-laws-principles/SKILL.md) · [References](skills/ux-laws-principles/references/) · [Examples](examples/) · [Install](#install) · [Changelog](CHANGELOG.md)

</div>

---

## Why this exists

AI agents are great at listing UX laws and bad at applying them.

They cite Hick when the problem is hierarchy. They invent DOIs. They treat “7 ± 2” as a menu limit. They push conversion tricks that erode trust.

This skill is a portable methodology so agents (and humans) **diagnose friction before naming a law**, keep sources honest, and produce findings you can act on.

> The goal is not to collect rules. It is to understand the task, explain the problem, and validate the fix.

---

## Install

Works with hosts that load Agent Skills (Claude Code, Cursor, Codex, Copilot, and similar):

```bash
# Option A — skills CLI (when available for this repo)
npx skills add vinimrdi/leis-de-ux

# Option B — manual (always works)
git clone https://github.com/vinimrdi/leis-de-ux.git
cp -r leis-de-ux/skills/ux-laws-principles ~/.claude/skills/ux-laws-principles
# or: ~/.cursor/skills/  ·  ~/.agents/skills/  ·  project .claude/skills/
```

**Lovable / chat tools:** add `skills/ux-laws-principles/SKILL.md` and the needed files under `references/` as project context. Prefer a **read-only audit** first.

Full matrix: [Compatibility and integrations](docs/compatibility-and-integrations.md) · [Lovable](integrations/lovable/README.md)

---

## Ask your agent

```text
Audit this signup form with the UX Laws & Principles skill.
Read-only. For each finding: observation, evidence, concept,
What/Why/Who/Where/When/How, severity (0–4), confidence, validation.
Do not change code.
```

```text
Review this dashboard hierarchy. Are indicators grouped by decision?
Are period, unit, and comparison visible? Use Gestalt, cognitive load,
and visibility of system status only where they fit the task.
```

```text
Before implementing this onboarding, evaluate drop-off risk with
Zeigarnik, goal-gradient, and progressive disclosure. Propose the
smallest change set. Label hypotheses vs confirmed issues.
```

```text
Heuristic evaluation of this checkout. Flag dark patterns.
Severity and confidence on every finding. No conversion claims
without a validation plan.
```

---

## What you get

| Piece | Role |
|-------|------|
| **[SKILL.md](skills/ux-laws-principles/SKILL.md)** | When to activate, method, output format, severity, Definition of Done |
| **Laws & effects** | Fitts, Hick-Hyman, Jakob, Miller, Peak-end, Zeigarnik, … with limits |
| **Principles & Gestalt** | Nielsen heuristics, Norman, proximity, uniform connectedness, … |
| **Models** | Mental models, cognitive load, Fogg, COM-B, HEART, JTBD, … |
| **Practice** | Forms, onboarding, dashboards, checkout, mobile, ethical conversion |
| **Research** | Usability tests, analytics, experiments, accessibility |
| **Sources & glossary** | Evidence hierarchy, SEO/AEO/GEO notes |

---

## How findings look (the “screenshot” of this skill)

Agents should not stop at a slogan. A complete finding looks like this:

```text
Finding: Errors only after submit

Observation: Invalid fields appear only after the full form is sent.
Evidence: Inspection of the flow (no live user data).
Concept: Error prevention; visibility of system status (Nielsen).

What: Late feedback on validity.
Why: Raises rework and uncertainty.
Who: All users; harder for low digital literacy and assistive tech.
Where: Fields + validation summary.
When: Validation can run safely during entry.
How: Validate at the right moment; message next to the field;
     preserve values; announce errors accessibly.

Impact: Extra steps, possible abandonment.
Severity: 3 (serious — many users fail part of the task)
Trade-off: More inline validation can feel noisy if over-eager.
Validation: Task success, error rate, time, help requests; keyboard + SR.
Confidence: Confirmed (inspection); impact needs user or analytics data.
```

**Severity:** 0 cosmetic … 4 critical (blocks primary task or severe harm).  
**Confidence:** confirmed / probable / hypothesis — independent of severity.

Full rules: [SKILL.md — Analysis output format](skills/ux-laws-principles/SKILL.md)

---

## Method in one table

| Dimension | Question |
|-----------|----------|
| **What** | What does the concept describe? |
| **Why** | Which mechanism or problem does it help explain? |
| **Who** | Who is affected? Exceptions? |
| **Where** | Screens, components, stages |
| **When** | When is it relevant — and when not? |
| **How** | What to change, and how to validate? |

Diagnose before you cite. Prefer the smallest effective intervention. Do not turn aesthetics into universal rules.

---

## When to use / when not to

| Use when | Skip when |
|----------|-----------|
| Auditing or redesigning flows, forms, dashboards, onboarding | Pure visual style / brand with no task impact |
| AI UI that ignores task or invents UX rules | Marketing copy or SEO keywords only |
| Heuristic evaluation, accessibility-informed review | Glossary lookup with no product decision |
| Conversion moments that must stay ethical | No interface, flow, or user task to evaluate |

---

## Symptom → concept (starter map)

| Symptom | Start here |
|---------|------------|
| Hard to tap / click | Fitts |
| Too many choices | Hick-Hyman, choice overload |
| Unexpected patterns | Jakob |
| Complexity dumped on the user | Tesler |
| Clutter / weak hierarchy | Prägnanz, Gestalt |
| Related items look unrelated | Proximity, similarity, uniform connectedness |
| Forgotten context between screens | Miller, recognition over recall |
| Multi-step abandonment | Zeigarnik, goal-gradient |
| Frozen-feeling UI | Doherty threshold |
| Scope expands without value | Parkinson (project adage) |
| Extra chrome, no task benefit | Occam (simplicity heuristic) |

Always check fit to the **task** and the **evidence**. Index is a start, not a verdict.

---

## Compared to a random “UX laws” list

| Typical list | This skill |
|--------------|------------|
| Names a law | Names the **problem first** |
| Implies universal rules | States **limits and category** (law / effect / heuristic / adage) |
| Omits sources or invents them | Requires **traceable sources** |
| Stops at advice | Requires **severity, confidence, validation** |
| Silent on ethics | Explicit **anti–dark-pattern** stance |

---

## FAQ

**What are UX laws?**  
Trends and principles from psychology, HCI, and design. The popular label does not make every concept a scientific law.

**Do they guarantee conversion?**  
No. They support hypotheses and explanations. Validate with users, data, and metrics that also protect the user.

**Does this work with Claude Code, Cursor, Lovable, Codex?**  
Yes as Markdown context; native skill install depends on the host. See [compatibility](docs/compatibility-and-integrations.md).

**Is English required?**  
Yes for new contributions. Official documentation language is English.

---

## Language

**English** is the official language of this project.

---

## License

- **Documentation:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **Code** (when present): [MIT](LICENSE-CODE)

---

## Maintainers

Maintained by **Planner**. Educational material — does not replace research, expert review, standards, legal advice, or accessibility validation.

[Contributing](CONTRIBUTING.md) · [Code of conduct](CODE_OF_CONDUCT.md) · [Strategy](docs/strategy-and-governance.md) · [Sources](skills/ux-laws-principles/references/sources-and-glossary.md)

**Repository:** [github.com/vinimrdi/leis-de-ux](https://github.com/vinimrdi/leis-de-ux)  
*Recommended rename (Settings → General → Repository name):* `ux-laws-principles` — GitHub keeps a redirect from the old name.
