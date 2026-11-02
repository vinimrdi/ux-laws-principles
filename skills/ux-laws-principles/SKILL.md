---
name: ux-laws-principles
description: Evidence-based UX skill for AI agents and designers. Apply UX laws, Nielsen heuristics, Gestalt, cognitive load, mental models, accessibility (WCAG), and research methods when creating, reviewing, or auditing digital products. Use for sites, landing pages, dashboards, SaaS, apps, forms, onboarding, navigation, checkout, conversion flows, heuristic evaluation, usability review, and AI-generated UI with Claude Code, Cursor, Lovable, Codex, Copilot, and similar tools. Do not use for pure visual styling preferences, brand identity, or marketing copy with no task or usability implication.
metadata:
  author: vinimrdi
  version: "1.4.2"
  language: en
  tags: [ux, usability, design, agent-skills, accessibility, product-design, heuristic-evaluation]
---

# UX Laws, Principles, Heuristics & Models

Practical knowledge base for applying user-experience foundations to digital products. The goal is not to collect rules or cite theory to justify preferences. It is to understand people, diagnose real friction, make evidence-based decisions, and validate results.

## Scope and rigor

This skill covers behavioral and perceptual laws and effects, human-centered design principles, usability heuristics, Gestalt, cognitive and behavioral models, accessibility, research, and validation.

There is no universal closed list of "UX laws". The field combines findings from different disciplines with different levels of evidence. Many popular expressions called "laws" are actually heuristics, contextual effects, models, or engineering principles. Correctly identify the category of each concept and do not assign undeserved scientific precision.

## When to activate this skill

Activate when the task involves:
- Creating or redesigning a website, landing page, app, dashboard, SaaS, platform, or digital product
- Designing flows, information architecture, navigation, onboarding, forms, search, filters, checkout, or subscriptions
- Running a UX/UI audit, heuristic evaluation, usability review, or conversion analysis
- Applying cognitive psychology, UX laws, Nielsen heuristics, Gestalt, mental models, or cognitive load
- Improving accessibility, responsiveness, microcopy, feedback, error states, or task recovery
- Guiding implementation with Lovable, Claude Code, Cursor, GitHub Copilot, Codex, or other AI-assisted development environments

## When NOT to use this skill

Do **not** activate (or treat findings as primary) when:
- The request is only about visual style, brand colors, illustration, or decorative layout with no task or usability impact
- The request is pure marketing copy, SEO keyword lists, or brand voice with no interaction or comprehension problem
- Legal, medical, or regulatory compliance is the sole question (defer to specialists; this skill may still inform accessibility)
- The user only asks for a glossary definition with no product decision
- There is no user task, interface, or flow to evaluate

## Common questions (direct answers)

**What are UX laws?**  
Trends and principles that help explain how people perceive, decide, and interact with products. Not every concept popularly called a law is a scientific law.

**Which UX laws are most known?**  
Fitts, Hick-Hyman, Jakob, Miller, and Prägnanz are among the most cited. The field also uses effects, heuristics, perceptual principles, and behavioral models.

**How do I apply UX laws to sites and apps?**  
Identify the user task and the observed friction, select the relevant concept, check its source and limits, propose a specific change, and validate with users or data.

**Does this skill work with Lovable, Claude Code, and Cursor?**  
Yes. The Markdown content can be used as context in different tools. Automatic installation as an Agent Skill depends on each environment’s support. See the compatibility documentation.

## Mandatory method: What, Why, Who, Where, When, How

For every concept, answer:

1. **WHAT** — Objective definition. What does the concept describe?
2. **WHY** — Foundation and relevance. Why does this happen? What benefit or risk is associated?
3. **WHO** — Audience and context. Which profiles or situations are most affected? Exceptions?
4. **WHERE** — Points of application. Components, screens, flows, or stages.
5. **WHEN** — Conditions of use. Signals that the concept is relevant; when not to apply it.
6. **HOW** — Practical decision and how to validate the result.

Do not invent answers to fill the six dimensions. State when a dimension does not apply or when evidence is missing.

## Source traceability

When explaining a concept, consult the corresponding reference in `references/` and keep the source close to the claim.

- Prefer the original study, scientific review, or official standard when it exists.
- Use professional sources to explain practice, not to prove scientific mechanisms.
- Do not invent DOI, authorship, year, title, or URL.
- If the reference is secondary or indirect, say so.
- If no direct source is identified, declare the gap.
- Distinguish evidence for the concept from evidence for a specific interface recommendation.
- Preserve limits of generalization, population, task, and context.
- In audits, cite the concept source and mark application to the case as an interpretation that needs validation.

## Reasoning rules

- Start from the user goal, the task, and the context.
- Diagnose before prescribing. Describe the observable problem before citing a law.
- Use concepts selectively. Do not force theories onto an interface.
- Treat laws as trends with limits, not deterministic truths.
- Separate observed evidence, analytics, research, expert inspection, technical facts, and hypotheses.
- Recognize conflicts: simplicity can hide features; familiarity can limit innovation; consistency can perpetuate bad patterns; automation can reduce control.
- Consider mobile, keyboard, assistive technologies, interruptions, errors, slow networks, and different experience levels.
- Define measurable outcomes before implementing.
- Respect autonomy, privacy, and ethics. Do not use psychology to deceive, coerce, or exploit vulnerabilities.
- Prefer the smallest effective intervention.
- Do not turn aesthetic preference into a universal rule.
- A well-known law does not prove that a change will increase conversion or retention.

## Workflow

### 1. Frame
Describe the user goal in one sentence. Identify task, trigger, context, constraints, prior knowledge, risks, and expected outcome.

### 2. Observe
Inspect the real experience. Look for unclear purpose, value, or next step; unnecessary choices and steps; memory effort; weak feedback; hidden states; poor error recovery; mismatch between expectation and behavior; accessibility, responsiveness, and performance barriers; trust gaps and deceptive persuasion.

### 3. Explain
Describe evidence, select the relevant concept, explain the relationship without exaggeration, present limits and conflicts, and classify confidence as confirmed, probable, or hypothesis.

### 4. Design
Propose a specific change. Explain which difficulty it solves, why the concept applies, trade-offs, what must remain intact, and how to evaluate success.

### 5. Validate
Choose an appropriate method: usability testing, analytics, accessibility evaluation, controlled experiment, performance measurement, or qualitative research.

## Analysis output format

**Finding**
- **What was observed:** concrete problem.
- **Evidence:** source and method.
- **Related concept:** law, principle, heuristic, or model.
- **What / Why / Who / Where / When / How:** application to the case.
- **Impact:** consequence for user and product.
- **Severity:** 0–4 (see scale below).
- **Trade-off:** what may get worse.
- **Validation:** how to test.
- **Confidence:** confirmed / probable / hypothesis.

### Severity scale

| Level | Meaning |
|-------|---------|
| **0** | Not a usability problem (preference or edge case only). |
| **1** | Cosmetic or minor friction; users can complete the task easily. |
| **2** | Moderate; causes delay, confusion, or occasional errors. |
| **3** | Serious; many users fail or abandon part of the task. |
| **4** | Critical; blocks the primary task or causes severe harm (data loss, wrong irreversible action, exclusion). |

Severity is independent of confidence. A hypothesis can be severity 3; a confirmed issue can be severity 1.

### Definition of Done (for a UX recommendation)

A recommendation is complete only when it:
1. Ties to a real user objective or observed friction.
2. Is supported by evidence or explicitly labeled as a hypothesis.
3. Names the concept category (law / effect / principle / heuristic / model).
4. States severity and confidence.
5. Respects accessibility and user autonomy.
6. Fits product constraints (or states what would need to change).
7. Defines how success will be validated.

Never write only "this violates Hick’s Law". Explain which options compete, why they are hard to distinguish, who is affected, which context matters, and what evidence would confirm the diagnosis.

## Symptom → concept index (quick guidance)

| Symptom | Likely concepts |
|---------|-----------------|
| Hard to tap / click targets | Fitts’s Law |
| Too many choices, slow decisions | Hick-Hyman, Choice Overload |
| Users expect different patterns | Jakob’s Law |
| Complexity pushed onto the user | Tesler’s Law |
| Forms reject reasonable input | Postel’s Law |
| Visual clutter, weak hierarchy | Prägnanz, Gestalt |
| Related items look unrelated | Proximity, Similarity, Uniform connectedness, Common region |
| Users forget items between screens | Miller / working memory, Recognition over recall |
| Critical items ignored in lists | Serial position, Von Restorff |
| Abandoned multi-step flows | Zeigarnik, Goal-Gradient |
| Experience remembered by worst moment or ending | Peak-End Rule |
| Interface feels frozen | Doherty Threshold |
| Attractive but hard to use | Aesthetic-Usability Effect |
| Progress feels invisible | Goal-Gradient |
| Scope or steps expand without value | Parkinson’s law (project adage) |
| Extra chrome without task benefit | Occam’s Razor (simplicity heuristic) |

Use this index only as a starting point. Always verify relevance to the specific task and evidence.

## Reference library

Read only the file needed:
- [UX laws and effects](references/ux-laws-and-effects.md)
- [Principles, heuristics and Gestalt](references/principles-heuristics-gestalt.md)
- [Cognitive, behavioral and experience models](references/ux-models.md)
- [Practical application by product and journey](references/practical-application.md)
- [Research, evaluation and validation](references/research-and-validation.md)
- [Sources, glossary and SEO](references/sources-and-glossary.md)

## Where this skill is most useful

**Situations**
- AI-generated UI that looks generic or ignores task flow
- Landing pages and marketing sites with weak hierarchy or unclear next step
- SaaS dashboards and complex forms
- Onboarding and multi-step flows with high drop-off
- Accessibility and inclusive design reviews
- Conversion and trust-sensitive moments (checkout, signup, pricing)
- Design critiques and heuristic evaluations

**Primary AI environments**
- Claude Code / Claude Desktop
- Cursor
- Lovable
- OpenAI Codex
- GitHub Copilot
- Windsurf, Cline, Roo Code, and other agents that load SKILL.md or Markdown context

**Secondary use**
- ChatGPT, Gemini, and other chat interfaces when files are provided as context
- Human designers and researchers as a structured reference

## Version

1.4.2 — Added Parkinson’s law, Occam’s Razor, and uniform connectedness (with correct category labels).
