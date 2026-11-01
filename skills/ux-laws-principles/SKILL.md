---
name: ux-laws-principles
description: Evidence-based UX skill for AI agents and designers. Apply UX laws, usability heuristics, Gestalt principles, cognitive models, accessibility, and research methods when creating, reviewing, or auditing digital products. Use for sites, landing pages, dashboards, SaaS, apps, forms, onboarding, navigation, and conversion flows with Claude Code, Cursor, Lovable, Codex, Copilot, and similar tools.
metadata:
  author: vinimrdi
  version: "1.1.0"
  language: en
  tags: [ux, usability, design, agent-skills, accessibility, product-design]
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

Do not activate only because the task mentions "design" or "UX". Use it when user-experience principles are relevant to the decision.

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

1. **WHAT** — Objective definition. What does the concept describe? Which phenomenon, mechanism, or rule is involved?
2. **WHY** — Foundation and relevance. Why does this happen? Which problem does it help explain? What benefit or risk is associated?
3. **WHO** — Audience and context. Which profiles, abilities, needs, experience levels, or situations are most affected? What are the exceptions?
4. **WHERE** — Points of application. On which components, screens, flows, channels, or journey stages is it relevant?
5. **WHEN** — Conditions of use. Which signals indicate the concept is pertinent? When should it not be applied?
6. **HOW** — Practical application. Which design, content, interaction, or technology decisions materialize the concept? How to validate the result?

Do not invent answers to fill the six dimensions. State when a dimension does not apply or when evidence is missing.

## Source traceability

When explaining a concept, consult the corresponding reference in `references/` and keep the source close to the claim.

- Prefer the original study, scientific review, or official standard when it exists.
- Use professional sources to explain practical application, not to prove scientific mechanisms.
- Do not invent DOI, authorship, year, title, or URL.
- If the reference is secondary, historical, or indirect, identify that explicitly.
- If no direct source is identified, declare the gap. Do not fill with a merely similar citation.
- Distinguish the evidence that supports the concept from the evidence that supports a specific interface recommendation.
- Preserve limits of generalization, population, task, and context of the study.
- In audits, cite the source of the concept and indicate that application to the case is an interpretation that needs validation.

## Reasoning rules

- Start from the user goal, the task, and the context.
- Diagnose before prescribing. Describe the observable problem before citing a law.
- Use concepts selectively. Do not force theories onto an interface.
- Treat laws as trends with limits, not deterministic truths.
- Separate observed evidence, analytics data, research, expert inspection, technical facts, and hypotheses.
- Recognize conflicts: simplicity can hide features; familiarity can limit innovation; consistency can perpetuate bad patterns; automation can reduce control.
- Consider mobile, keyboard, assistive technologies, interruptions, errors, slow networks, and different experience levels.
- Define measurable outcomes before implementing.
- Respect autonomy, privacy, and ethics. Do not use psychology to deceive, coerce, or exploit vulnerabilities.
- Prefer the smallest effective intervention. Fix the source of friction before adding tutorials, animations, or components.
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
- **What / Why / Who / Where / When / How:** detailed application to the case.
- **Impact:** consequence for user and product.
- **Trade-off:** what may get worse.
- **Validation:** how to test.
- **Confidence:** confirmed / probable / hypothesis.

A UX recommendation must be tied to a real objective, supported by evidence or labeled as a hypothesis, respect accessibility and autonomy, fit product constraints, and allow validation.

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
| Users forget items between screens | Miller / working memory, Recognition over recall |
| Critical items ignored in lists | Serial position, Von Restorff |
| Abandoned multi-step flows | Zeigarnik, Goal-Gradient |
| Experience remembered by worst moment or ending | Peak-End Rule |
| Interface feels frozen | Doherty Threshold |
| Attractive but hard to use | Aesthetic-Usability Effect |
| Progress feels invisible | Goal-Gradient |

Use this index only as a starting point. Always verify relevance to the specific task and evidence.

## Reference library

Read only the file needed:
- [UX laws and effects](references/leis-e-efeitos-ux.md) *(to be fully translated)*
- [Principles, heuristics and Gestalt](references/principios-heuristicas-gestalt.md)
- [Cognitive, behavioral and experience models](references/modelos-de-ux.md)
- [Practical application by product and journey](references/aplicacao-pratica.md)
- [Research, evaluation and validation](references/pesquisa-e-validacao.md)
- [Sources, glossary and SEO](references/fontes-e-glossario.md)

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

1.1.0 — English conversion, improved triggers, structured output, symptom index, clearer agent guidance.
