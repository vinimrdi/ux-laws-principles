# Compatibility and integrations with AI tools

## Purpose

This page explains how to use the UX Laws & Principles methodology with different assistants, coding agents and digital product builders.

**Compatibility is not binary.** A tool may run Agent Skills natively, load Markdown as context, or accept specific instructions without recognizing the skill format. Availability can change with plan, version, interface, extension and configuration.

Do not claim native support without confirmation in the tool’s official documentation.

## Integration categories

| Category | Meaning | What to expect |
|----------|---------|----------------|
| **Native** | The tool recognizes and loads the skill format directly. | May discover and invoke the skill according to its mechanism. |
| **Adapted** | The tool has its own rules, agents or instruction mechanism. | Convert or reference the methodology in that mechanism. |
| **Contextual** | The tool accepts files or text as context. | The model can consult the content during the conversation, without persistent installation. |

## Platform matrix

The classification below is operational guidance. Confirm current documentation and version before distributing installation instructions.

| Platform | Recommended approach | Initial category |
|----------|----------------------|------------------|
| Claude Code | Install the skill folder in the skills mechanism supported by Claude Code. | Native, when format and version are recognized. |
| OpenAI Codex | Make the skill folder available in the skills directory recognized by Codex. | Native, when enabled in the environment. |
| Lovable | Add the documentation as project context and use the specific guide below. | Adapted / contextual. |
| Cursor | Reference the files in agent rules and context; check Agent Skills support in the version used. | Adapted / contextual. |
| GitHub Copilot | Use instructions and context files supported by the Copilot environment; check skills support in the version used. | Adapted / contextual. |
| ChatGPT | Attach the files, configure GPT instructions, or use a compatible development environment. | Contextual; varies by product. |
| Gemini | Provide the files as context or use the extensions/instructions mechanism of the Gemini environment used. | Contextual / adapted. |
| Claude Desktop | Attach or make the files available through supported context features. | Contextual / adapted. |
| Windsurf, Cline, Roo Code and OpenCode | Check the rules, context and skills mechanism of the installed version. | Adapted / contextual. |

This table does not replace official vendor documentation. Absence of a native classification does not prevent use of the content.

## Skill structure

The main skill is in `skills/ux-laws-principles/SKILL.md`. References are separate Markdown files so agents can load only the content needed.

When integrating in another environment, preserve:
- The main file and its frontmatter.
- Relative paths to the references.
- The What, Why, Who, Where, When and How method.
- The rules of rigor, evidence, accessibility and ethics.

If the tool does not recognize skills, provide the full folder as context and instruct the agent to consult the main file before evaluating or proposing changes.

## Integration with Lovable

Lovable is a priority for this project because it enables creating sites, dashboards, platforms and applications with AI assistance. The recommended use is as a methodology for analysis and decision during development, not as authorization to change code indiscriminately.

### Preparation

1. Make the documentation available in project context by attaching relevant files or copying needed content into project instructions.
2. Keep the design system, tokens, components and approved decisions as the source of truth.
3. Request a read-only audit first.
4. Request implementation only after reviewing findings and approving scope.
5. Perform QA and validate the experience on relevant devices and flows.

### Read-only audit prompt

```text
Use the UX Laws & Principles methodology as a reference to audit this interface.

Analyze flows and components considering the user goal, the task and the context. Identify only observable problems or clearly classified hypotheses.

For each finding, present:
1. What was observed.
2. Evidence or limitation of the inspection.
3. Related law, effect, principle, heuristic or model.
4. What, Why, Who, Where, When and How.
5. Probable impact for user and product.
6. Trade-offs.
7. Recommendation and way to validate.
8. Confidence level: confirmed, probable or hypothesis.

Do not change files, code, database, settings or design system. Do not apply migrations, publish or run external operations. Preserve already approved visual and technical decisions. Deliver the diagnosis first.
```

### Implementation prompt after approval

```text
Implement only the approved findings from the UX Laws & Principles audit.

Respect the authorized scope and preserve the design system, tokens, components, naming and existing decisions. Before changing a shared structure, identify the impact. Do not perform additional refactors or improvements outside scope.

For each change, explain the problem fixed and the UX concept applied. Do not change database, secrets, paid integrations or publish without explicit authorization. At the end, report changed files, tests run, limitations and points that require visual QA.
```

### Prompt for reviewing a new screen

```text
Before implementing this screen, use the UX Laws & Principles methodology to evaluate information architecture, hierarchy, comprehension, states, accessibility and task flow.

Present a structured proposal and the trade-offs. Do not invent user needs or treat UX laws as deterministic rules. Preserve existing product patterns and wait for approval before implementing.
```

### Important limits in Lovable

- Documentation does not replace user research or real tests.
- The agent may not load all files automatically; explicitly indicate the skill path and references.
- Do not assume the model has access to the public repository in every session.
- Do not allow an audit to become an unsolicited refactor.
- Confirm current support for specific features in Lovable official documentation.

## Integration with Claude Code, Codex and coding agents

When the environment supports Agent Skills, place the `skills/ux-laws-principles` folder in the location recognized by the agent. Preserve relative paths of the references. Check official product documentation to determine directory, global or per-project scope and discovery policy.

When there is no direct support, use the `SKILL.md` file as the main instruction and keep the references accessible in project context.

## Maintaining this matrix

Compatibility should be reviewed when:
- A vendor announces support for Agent Skills.
- The format or frontmatter changes.
- The installation mechanism is altered.
- An integration is tested end-to-end.

Record date, tool version and evidence before promoting an integration from contextual to native.
