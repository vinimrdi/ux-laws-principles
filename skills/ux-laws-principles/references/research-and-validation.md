# UX research, evaluation and validation

Choose methods by the question. No single method explains the whole experience.

| Question | Methods |
|----------|---------|
| Does the person complete the task? | Usability testing, task analysis |
| Why is there difficulty? | Interviews, contextual observation, support |
| Can they find information? | Tree testing, first-click testing, search analysis |
| How do they group concepts? | Card sorting and interviews |
| What happens at scale? | Analytics, funnels and cohorts |
| Which variant works better? | Controlled experiment |
| Is the interface accessible? | Automated check and manual evaluation |
| Is it fast? | Field data, lab, network and devices |
| What does the person expect? | Interviews, concept tests and prototypes |

## Usability testing
**References:** [Nielsen & Molich (1990), heuristic evaluation](https://doi.org/10.1145/97243.97281) is a distinct technique from testing with participants; Nielsen Norman Group, [Discount Usability](https://www.nngroup.com/articles/web-discount-usability/); ISO 9241-210:2019, [human-centred design](https://www.iso.org/standard/77520.html). For planning and moderation, see Rubin & Chisnell, *Handbook of Usability Testing* (2nd ed., 2008).
- **What:** Observe representative people attempting relevant tasks.
- **Why:** Reveals problems of comprehension, execution, feedback and recovery.
- **Who:** Current or potential representative users.
- **Where:** Prototypes, existing interfaces and critical flows.
- **When:** Before important decisions, after changes or when facing difficulties.
- **How:** Define tasks and criteria; ask for real goals; observe completion, errors and hesitation; avoid leading questions; record limitations.
- **Measures:** Success, time, errors, help requests, deviations and confidence.

## Interviews and qualitative research
**Methodological reference:** ISO 9241-210:2019, [Human-centred design for interactive systems](https://www.iso.org/standard/77520.html). The standard describes activities for understanding and specifying the context of use; it does not prescribe a single interview script.
Understand context, motivations, language, alternatives and expectations. Ask about real and recent experiences. Avoid leading answers and do not generalize an isolated opinion.

## Analytics
**Complementary reference:** Rodden, Hutchinson & Fu (2010), [Measuring the User Experience on a Large Scale](https://doi.org/10.1145/1753326.1753687), for user-centered metrics in web applications. Observational analytics does not establish causality by itself.
- **What:** Aggregated data of events and behavior.
- **Why:** Reveal frequency, sequence and distribution.
- **Who:** Product and business.
- **Where:** Funnels, events, cohorts, search and errors.
- **When:** Questions about volume, frequency and abandonment.
- **How:** Define meaningful events, validate instrumentation, segment by context, respect privacy and combine with research.
Analytics shows what occurred, not necessarily why.

## Experiments and A/B tests
**References:** Kohavi, Tang & Xu, *Trustworthy Online Controlled Experiments* (Cambridge University Press, 2020), methodological reference for online experimentation; [Kohavi et al. (2013), Online Controlled Experiments at Large Scale](https://doi.org/10.1145/2433396.2433413).
- **What:** Controlled comparison between variants.
- **Why:** Estimates effects under comparable conditions.
- **Who:** Products with adequate volume and instrumentation.
- **Where:** Content, flows and interfaces.
- **When:** Clear hypothesis and acceptable risk.
- **How:** Falsifiable hypothesis; primary metric and guardrails; sample and duration; randomization; monitoring of adverse effects.

## Heuristic evaluation
**References:** [Nielsen & Molich (1990)](https://doi.org/10.1145/97243.97281), seminal work on heuristic evaluation; [Nielsen, 10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/).
- **What:** Expert inspection based on heuristics.
- **Why:** Finds potential problems quickly.
- **Who:** Design, product and quality.
- **Where:** Screens, flows and prototypes.
- **When:** Discovery and continuous review.
- **How:** Inspect tasks; record problem, heuristic and impact; estimate severity with criteria. Absence of findings does not prove absence of problems.

## Accessibility
**Normative references:** [W3C, WCAG 2.2](https://www.w3.org/TR/WCAG22/) and [W3C WAI, WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/). Use manual evaluation and assistive technologies; automated tools cover only part of the criteria.
Combine automation, keyboard, visible focus, screen reader, zoom, reflow, contrast, reduced motion, labels and alternatives to gestures. An automated tool alone does not prove WCAG conformance.

## Level of evidence
- **Direct:** Observed behavior, validated data, reproducible bug or measurement.
- **Corroborated:** Independent signals support the conclusion.
- **Expert inspection:** Plausible problem not yet validated with users.
- **Hypothesis:** Explanation or solution to test.

Report sample, method, platform, date and limitations. Do not inflate confidence. Define success before redesign: completion, fewer errors, findability, recovery, accessibility and abandonment due to unexpected costs. Combine business metrics with user outcomes.
