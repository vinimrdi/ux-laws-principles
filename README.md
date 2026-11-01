# UX Laws & Principles

**Open, evidence-based guide to UX laws, usability heuristics, Gestalt principles, cognitive models, accessibility, and research methods for digital products — designed for designers, product teams, and AI coding agents.**

[![License: CC BY 4.0](https://img.shields.io/badge/Documentation-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Language: en](https://img.shields.io/badge/Language-English-blue.svg)](#language-and-scope)
[![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

**UX Laws & Principles** brings together behavioral and perceptual laws and effects, design principles, usability heuristics, Gestalt, cognitive and behavioral models, accessibility, and research methods. Its purpose is to turn UX knowledge into practical criteria for building better digital products.

Maintained by **Planner** and published as an open project for the community.

> This is not a list of rules to justify visual preferences. It is a methodology for understanding tasks, diagnosing friction, making grounded decisions, and validating results.

## What you get

- **Knowledge base** — laws, effects, principles, heuristics, models, and glossary
- **Application method** — structured analysis: What, Why, Who, Where, When, How
- **Practice** — guidance for navigation, onboarding, forms, search, dashboards, checkout, mobile, and ethical conversion
- **Research & validation** — usability testing, interviews, analytics, experiments, accessibility
- **AI agent integration** — ready-to-use skill for Claude Code, Cursor, Lovable, Codex, Copilot, and similar tools
- **Examples** — materials to apply and teach the concepts

## Quick start

1. Read the main [skill](skills/ux-laws-principles/SKILL.md)
2. Browse the [reference library](skills/ux-laws-principles/references/)
3. Check [practical examples](exemplos/)
4. See [compatibility and integrations](docs/compatibilidade-e-integracoes.md)
5. Read [how to contribute](CONTRIBUTING.md)

### Install as an Agent Skill

**Claude Code / compatible agents**
```bash
# Clone or copy the skill folder into your skills directory
git clone https://github.com/vinimrdi/leis-de-ux.git
cp -r leis-de-ux/skills/ux-laws-principles ~/.claude/skills/ux-laws-principles
```

**Cursor / other agents that support skills**  
Copy `skills/ux-laws-principles` into the location your agent expects for skills, or provide the folder as project context.

**Lovable / chat-based tools**  
Add the skill and relevant reference files as project context. Prefer a read-only audit first, then implement only approved findings.

## Frequently asked questions

### What are UX laws?
Trends and principles drawn from cognitive psychology, perception, human-computer interaction, and design. The popular label "UX law" does not make every concept a scientific law. This guide distinguishes empirical laws, effects, principles, heuristics, models, and engineering principles.

### Which are the main UX laws?
Among the most known: Fitts, Hick-Hyman, Jakob, Miller, and Prägnanz. The field also uses effects such as Von Restorff and Zeigarnik, Nielsen heuristics, Gestalt principles, and models such as cognitive load and Fogg B=MAP. Relevance depends on the task and context.

### How do I apply UX laws to a site or app?
Start from the task and the observed problem. Identify the relevant concept, check its source and limits, propose a specific change, and validate with usability testing, analytics, or accessibility evaluation. Do not apply a law only to justify a visual preference.

### How can I improve dashboard usability?
Organize indicators around the decisions they support, make units and periods explicit, group related information, prioritize visual hierarchy, and provide context for interpretation. Test whether people can find and understand what they need.

### Can I use this skill with Lovable, Claude Code, Cursor, and other AIs?
Yes. Markdown content can be supplied as context across tools. Native Agent Skill support varies by platform. See the [compatibility matrix](docs/compatibilidade-e-integracoes.md).

### Do UX laws guarantee higher conversion?
No. They help form hypotheses and explain interaction patterns, but they do not guarantee conversion, retention, or satisfaction. Changes should be evaluated with evidence and metrics that also protect user interests.

## How the methodology works

Every concept should be applied through six dimensions:

| Dimension | Question |
|-----------|----------|
| **What** | What does the concept describe? |
| **Why** | Which mechanism or problem does it help explain? |
| **Who** | Which people and contexts are affected? |
| **Where** | On which screens, components, or stages does it apply? |
| **When** | Which conditions make its application relevant? |
| **How** | What practical decision can be implemented and validated? |

The methodology also requires separating observed evidence, data, expert inspection, and hypotheses. Laws and effects describe trends, not guaranteed outcomes.

## Where this skill is especially useful

| Situation | Why it helps |
|-----------|--------------|
| AI-generated UI that feels generic or task-blind | Grounds decisions in task, friction, and evidence |
| Landing pages & marketing sites | Hierarchy, next step, and trust |
| SaaS dashboards & complex forms | Cognitive load, recognition, progressive disclosure |
| Onboarding & multi-step flows | Goal-gradient, Zeigarnik, recovery |
| Accessibility reviews | Inclusive criteria alongside UX laws |
| Conversion-critical moments | Ethical application of psychology |
| Design critiques & heuristic evaluations | Structured findings with confidence levels |

**Primary AI targets:** Claude Code, Cursor, Lovable, Codex, GitHub Copilot, Windsurf and similar agents that load SKILL.md or Markdown context.

## SEO, AEO and GEO notes

Content is written for people first, then for discovery:

- Clear, question-oriented headings
- Direct definitions at the start of sections
- Explicit distinction between law, effect, principle, heuristic, model, and hypothesis
- Primary sources kept close to claims
- Stable structure that agents and answer engines can parse

## Language and scope

Documentation is in **English**. Original Portuguese materials remain in the repository history and selected folders during transition.

The UX field has no universal closed list of laws. This work differentiates laws, effects, principles, heuristics, models, and engineering principles. It does not assign undeserved scientific precision to popular concepts.

## License

Documentation is available under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. You may share and adapt the material, including commercially, provided you give appropriate credit and indicate changes.

Code examples and software tools, when identified as such, are available under the MIT license. See [LICENSE](LICENSE) and notices in each directory.

## Maintenance and responsibility

Maintained by **Planner**. This documentation is educational and does not replace user research, expert evaluation, technical standards, legal advice, or accessibility validation.

- [How to contribute](CONTRIBUTING.md)
- [Code of conduct](CODE_OF_CONDUCT.md)
- [Changelog](CHANGELOG.md)
- [Sources and glossary](skills/ux-laws-principles/references/fontes-e-glossario.md)

**Project:** [github.com/vinimrdi/leis-de-ux](https://github.com/vinimrdi/leis-de-ux)  
**Maintaining organization:** Planner
