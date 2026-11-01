# Sources, glossary and SEO for UX

## Editorial criteria and evidence hierarchy

This documentation synthesizes knowledge from psychology, human-computer interaction, design, accessibility and research. There is no official standard that enumerates all “UX laws”. The popular label does not turn a hypothesis, metaphor or heuristic into a scientific law.

Prioritize, in this order:

1. **Original research and scientific reviews:** peer-reviewed articles, academic books and meta-analyses.
2. **Official standards and norms:** W3C/WCAG and ISO standards.
3. **Specialized institutions and authors:** Nielsen Norman Group, Design Council, NIST and academic labs.
4. **Secondary sources:** synthesis books and explanatory articles, used for context, not as substitutes for original research.

For each claim, record author, year, title, publication, DOI or stable URL and what the source actually supports. Distinguish experimental finding, theoretical interpretation, professional guidance and proposed interface application.

### Suggested editorial levels

- **Foundational:** original source or standard directly related to the concept.
- **Synthesis/review:** critical review, historical review or evidence synthesis.
- **Professional application:** guidance from an institution or specialist for UX practice.
- **Application hypothesis:** design recommendation that needs validation in the product context.

Do not use a professional-application source as proof of a psychological mechanism. Do not attribute causality when the study only shows association. Report sample, context, task and generalization limits when available.

## Bibliography by topic

### Usability, evaluation and human-centred design

- Nielsen, J. (1994; content revised 2024). [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/). Nielsen Norman Group. Reference source for the ten heuristics. General inspection principles, not technical rules or an automatic quality scale.
- Nielsen, J. & Molich, R. (1990). [Heuristic evaluation of user interfaces](https://doi.org/10.1145/97243.97281). CHI '90. Seminal work on heuristic evaluation.
- ISO. (2019). [ISO 9241-210:2019, Human-centred design for interactive systems](https://www.iso.org/standard/77520.html). Standard on human-centred design across the lifecycle of interactive systems.
- Gould, J. D. & Lewis, C. (1985). [Designing for usability: key principles and what designers think](https://doi.org/10.1145/317456.317459). Communications of the ACM, 28(3), 300–311. Classic principles of user focus, empirical measurement and iteration.
- Nielsen, J. (1993). [Iterative User Interface Design](https://www.nngroup.com/articles/iterative-design/). Nielsen Norman Group. Professional synthesis and case studies on evaluation-based iteration.
- Nielsen, J. (1997). [Discount Usability for the Web](https://www.nngroup.com/articles/web-discount-usability/). Nielsen Norman Group. Contextualizes economical evaluation methods; does not replace research planning.
- Norman, D. A. (2013, revised edition). *The Design of Everyday Things*. Basic Books. Broad reference for conceptual models, feedback, mapping, affordances and signifiers.

### Interaction and performance laws

- Fitts, P. M. (1954). [The information capacity of the human motor system in controlling the amplitude of movement](https://doi.org/10.1037/h0055392). Journal of Experimental Psychology, 47(6), 381–391. Original study on motor pointing; interface applications are adaptations to interaction context.
- Hick, W. E. (1952). [On the rate of gain of information](https://doi.org/10.1080/17470215208416600). Quarterly Journal of Experimental Psychology, 4(1), 11–26.
- Hyman, R. (1953). [Stimulus information as a determinant of reaction time](https://doi.org/10.1037/h0056940). Journal of Experimental Psychology, 45(3), 188–196. Together with Hick, grounds the relationship between choice uncertainty and reaction time. Does not authorize reducing every product decision to raw option count.
- Proctor, R. W. & Schneider, D. W. (2018). [Hick’s law for choice reaction time: A review](https://doi.org/10.1080/17470218.2017.1322622). Quarterly Journal of Experimental Psychology. Review discussing context, limits and challenges of the model.
- Miller, G. A. (1956). [The magical number seven, plus or minus two: Some limits on our capacity for processing information](https://doi.org/10.1037/h0043158). Psychological Review, 63(2), 81–97. The paper addresses different processing-capacity phenomena; it does not establish a universal seven-item limit for menus or interfaces.
- Cowan, N. (2001). [The magical number 4 in short-term memory: A reconsideration of mental storage capacity](https://doi.org/10.1017/S0140525X01003922). Behavioral and Brain Sciences, 24(1). Critical review discussing smaller capacity estimates in certain tasks.
- Cowan, N. (2015). [George Miller’s magical number of immediate memory in retrospect](https://doi.org/10.1037/a0039035). Psychological Review, 122(3), 536–541. Critical revisit of the legacy and interpretation of Miller’s work.
- Doherty, W. J. & Thadhani, A. J. (1982). *The Economic Value of Rapid Response Time*. IBM Technical Report GE20-0752-0. Technical report often associated with the so-called Doherty Threshold. The 400 ms figure should be treated as a historical/contextual reference, not a universal threshold or fixed goal for every interaction.
- Accot, J. & Zhai, S. (1997). [Beyond Fitts’ law: Models for trajectory-based HCI tasks](https://doi.org/10.1145/258549.258760). CHI '97. Complements discussion of trajectory tasks, where the simple Fitts formulation may not suffice.

### Memory, attention, perception and experience

- Zeigarnik, B. (1927). *Über das Behalten von erledigten und unerledigten Handlungen*. Psychologische Forschung, 9, 1–85. Original work associated with the Zeigarnik effect. Generalization to motivation, notifications and task completion should be treated with caution.
- von Restorff, H. (1933). *Über die Wirkung von Bereichsbildungen im Spurenfeld*. Psychologische Forschung, 18, 299–342. Original work associated with the isolation effect.
- MacLeod, C. M. (2020). [Zeigarnik and von Restorff: The memory effects and the stories behind them](https://doi.org/10.3758/s13421-020-01033-5). Memory & Cognition, 48, 1073–1088. Historical review and evaluation of the state of these effects. Important for not treating the effects as simple or universal laws.
- Johansson, B. S. (1970). [Attention and the von Restorff effect](https://doi.org/10.1111/j.2044-8295.1970.tb01234.x). British Journal of Psychology, 61(2), 163–170. Example of research examining explanations of the isolation effect.
- Kahneman, D., Fredrickson, B. L., Schreiber, C. A. & Redelmeier, D. A. (1993). [When More Pain Is Preferred to Less: Adding a Better End](https://doi.org/10.1111/j.1467-9280.1993.tb00589.x). Psychological Science, 4(6), 401–405. Study on retrospective evaluation of aversive experiences; does not prove that every digital journey will be evaluated by the same pattern.
- Kivetz, R., Urminsky, O. & Zheng, Y. (2006). [The Goal-Gradient Hypothesis Resurrected: Purchase Acceleration, Illusionary Goal Progress, and Customer Retention](https://doi.org/10.1509/jmkr.43.1.39). Journal of Marketing Research, 43(1), 39–58. Studies goal gradient in reward contexts; does not justify fabricating progress in interfaces.
- Kurosu, M. & Kashimura, K. (1995). [Apparent Usability vs. Inherent Usability: Experimental Analysis on the Determinants of the Apparent Usability](https://doi.org/10.1145/223355.223680). CHI '95 Conference Companion. Early research often cited in discussion of the aesthetic-usability effect.
- Tractinsky, N., Katz, A. S. & Ikar, D. (2000). [What is beautiful is usable](https://doi.org/10.1016/S0953-5438(00)00031-X). Interacting with Computers, 13(2), 127–145. Study on perception of aesthetics and usability.
- Moran, K. (2024; revised 2026). [The Aesthetic-Usability Effect](https://www.nngroup.com/articles/aesthetic-usability-effect/). Nielsen Norman Group. Useful professional synthesis for research and evaluation; does not replace the original studies.

### Gestalt, mental models and interaction patterns

- Koffka, K. (1935). *Principles of Gestalt Psychology*. Harcourt, Brace. Historical reference work for Gestalt psychology. Do not attribute every modern visual rule to a single study or author.
- Norman, D. A. (1988; later revised editions). *The Design of Everyday Things*. Basic Books. Reference for mental models, conceptual model, mapping, feedback, affordances and signifiers.
- Nielsen, J. (2000). [End of Web Design](https://www.nngroup.com/articles/end-of-web-design/). Nielsen Norman Group. Text in which Nielsen formulates the idea later known as Jakob’s Law in the context of web conventions.
- Nielsen, J. (2017). [Jakob’s Law of Internet User Experience](https://www.nngroup.com/videos/jakobs-law-internet-ux/). Nielsen Norman Group. Later explanation of the principle; treat as guidance on learned expectations, not an obligation to copy competitors.
- Nielsen, J. (2006). [Progressive Disclosure](https://www.nngroup.com/articles/progressive-disclosure/). Nielsen Norman Group. Design guidance to present essential features first and make secondary functions available on demand.
- Tesler, L. (c. 1984). [Adages and Coinages: Tesler’s Law of Conservation of Complexity](https://www.nomodes.com/larry-tesler-consulting/adages-and-coinages). Larry Tesler’s own record of the formulation, without an identified original academic paper. See also Yablonski, J. (2020), [*Laws of UX*, Tesler’s Law chapter](https://www.oreilly.com/library/view/laws-of-ux/9781098146955/ch09.html). An engineering/design practice principle, not an experimental psychological law.
- Postel, J. (1980). [RFC 761: Transmission Control Protocol](https://www.rfc-editor.org/rfc/rfc761). The robustness maxim belongs to protocol engineering. Do not classify it as a psychological or UX law; also discuss the risks of accepting ambiguous or invalid input.

### Behavioral models, processes and metrics

- Fogg, B. J. (2009). [A Behavior Model for Persuasive Design](https://doi.org/10.1145/1541948.1541999). Persuasive '09. Academic basis of the Fogg Behavior Model (Motivation, Ability, Prompt).
- Fogg Behavior Design Lab, Stanford. [Fogg Behavior Model](https://behaviordesign.stanford.edu/resources/fogg-behavior-model). Institutional source of explanation and materials for the model.
- Michie, S., van Stralen, M. M. & West, R. (2011). [The behaviour change wheel: A new method for characterising and designing behaviour change interventions](https://doi.org/10.1186/1748-5908-6-42). Implementation Science, 6, 42. Original paper presenting the Behaviour Change Wheel and the COM-B model.
- Rodden, K., Hutchinson, H. & Fu, X. (2010). [Measuring the User Experience on a Large Scale: User-Centered Metrics for Web Applications](https://doi.org/10.1145/1753326.1753687). CHI '10, 2395–2398. Origin work of the HEART framework.
- Design Council. [The Double Diamond](https://www.designcouncil.org.uk/resources/the-double-diamond/). Institutional source for the Discover, Define, Develop and Deliver phases. The Design Council itself clarifies that it is a process representation, not a rigid manual.
- Design Council. [History of the Double Diamond](https://www.designcouncil.org.uk/resources/the-double-diamond/history-of-the-double-diamond/). Historical context of the framework.
- AARRR / Pirate Metrics: treat as a practical growth metrics framework, not a scientific behavior model or universal UX framework. When citing a specific version, identify the author, original material and context; do not assign academic precision without a source.

### Accessibility, standards and human-centred design

- W3C. [Web Content Accessibility Guidelines (WCAG) 2.2](https://www.w3.org/TR/WCAG22/). Official standard with testable success criteria at levels A, AA and AAA.
- W3C WAI. [WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/). Overview of principles and accessibility resources.
- ISO. [ISO 9241-210:2019](https://www.iso.org/standard/77520.html). Human-centred design standard for interactive systems.
- NIST. [Human-Centered Design](https://www.nist.gov/itl/iad/human-factors-human-centered-design). Institutional materials on human factors and human-centred design.

WCAG 2.2 organizes guidelines under four principles: Perceivable, Operable, Understandable and Robust (POUR). An isolated automated check does not prove conformance. Evaluate full flows, content, states and assistive technologies.

## Editorial audit of concepts in the documentation

This section records classification care that should be preserved on conceptual pages:

| Concept | Recommended classification | Editorial care |
|---------|----------------------------|----------------|
| Fitts | Empirical motor-performance law | Application to interfaces depends on task and device. |
| Hick-Hyman | Law/model of choice reaction time | Do not use raw option count as sufficient diagnosis. |
| Jakob | Practical principle/law of learned expectations | Does not mean copying competitors or keeping harmful conventions. |
| Tesler | Principle of conservation of complexity | Not an experimental psychological law. |
| Postel | Engineering robustness principle | Not a UX law; permissiveness can create risks. |
| Prägnanz and Gestalt | Principles/laws of perceptual organization | Avoid attributing simplified modern laws directly to a single isolated source. |
| Miller | Classic paper on processing capacity | “7 ± 2” is not an interface item limit. |
| Recognition rather than recall | Design principle supported by memory and usability research | Not a law with a single formula. |
| Serial position | Memory effect | Depends on task, material and retrieval conditions. |
| Von Restorff | Isolation effect | Attention, surprise and memory should not be treated as a single explanation. |
| Zeigarnik | Effect/research line on interrupted tasks | Evidence and generalization to product motivation vary. |
| Peak-end | Retrospective evaluation pattern | Original research studied specific experiences; do not universalize to every journey. |
| Doherty | Historical system-performance heuristic | 400 ms is not a universal threshold or fixed goal. |
| Goal-gradient | Behavioral hypothesis/effect | Depends on goals, rewards and context; never fabricate progress. |
| Aesthetic-usability | Documented perceptual effect | Perceived ease is not the same as real effectiveness or efficiency. |
| Pareto | Empirical rule of unequal distribution | Not a UX law nor a guaranteed 80/20 proportion. |
| Choice overload | Contextual decision phenomenon | Results depend on context, variety, preference and complexity. |
| Endowment and sunk cost | Behavioral economics effects | Do not exploit to hinder cancellation, deletion or exit. |

## Glossary

- **UX:** experience of interacting with a product, service or system.
- **UI:** interface through which interaction occurs.
- **Usability:** the extent to which specified users achieve goals with effectiveness, efficiency and satisfaction in a specified context of use.
- **Accessibility:** the possibility for people with different abilities to perceive, understand, navigate and interact.
- **Heuristic:** general guidance for evaluation or design; not an exact technical requirement.
- **Mental model:** internal understanding of how something works.
- **Conceptual model:** explanation of how the product works, communicated through structure, language and behavior.
- **Affordance:** property or relationship that enables an action.
- **Signifier:** perceptible cue that indicates where and how to act.
- **Feedback:** the system’s response to an action.
- **Cognitive load:** mental demand involved in processing information and performing a task.
- **Progressive disclosure:** gradual presentation of secondary features or complexity.
- **Dark pattern:** pattern that deceives, pressures or hinders free choices.
- **Journey:** stages and touchpoints traversed to achieve a goal.
- **Usability testing:** observation of representative people performing relevant tasks.
- **Guardrail metric:** indicator tracked to detect adverse effects of a change.

## SEO, AEO and GEO: discovery in search engines and AI systems

Organic discovery should consider three complementary contexts. They overlap, but are not synonyms and do not guarantee ranking.

### SEO: Search Engine Optimization

**Goal:** make pages useful, accessible, crawlable and understandable for traditional search engines such as Google and Bing.

**Application in this project:**
- Use unique, descriptive titles that match search intent.
- Structure pages with a clear H1 and hierarchical H2/H3.
- Answer the main question without vague introductions.
- Use stable URLs, internal links and links to primary sources.
- Write original, up-to-date, readable and accessible content.
- Optimize performance, mobile experience, indexability and metadata.
- Avoid keyword stuffing, pages created only to rank, and repetitive content.

### AEO: Answer Engine Optimization

**Goal:** help answer engines find, understand and extract an accurate answer to a question.

**Application in this project:**
- Use real questions as subsection titles when that improves navigation.
- Start each section with a direct, self-contained definition.
- Explain concept, context, exceptions and limits right after the short answer.
- Include FAQs with objective answers without sacrificing accuracy.
- Use lists and tables when they help compare concepts.
- Clearly distinguish law, effect, principle, heuristic, model and hypothesis.
- Attach claims to identifiable sources, preferably primary ones.
- Do not create artificial answers only to chase featured snippets.

### GEO: Generative Engine Optimization

**Goal:** increase clarity, reliability and retrievability of content in generative AI systems and search engines with synthesized answers.

**Application in this project:**
- Present explicit definitions, full names, synonyms and original English terms on first occurrence.
- Keep each explanation understandable outside immediate context, without removing caveats.
- Identify authors, dates, publications, DOIs and stable links whenever available.
- Separate original evidence, review, professional guidance and application inference.
- Publish original examples, application criteria and concrete limitations.
- Keep Markdown files organized, readable and with working internal links.
- Identify authorship, maintainer, license, version and review date.
- Distribute content through legitimate, relevant channels, preserving links to the canonical source.

### Questions and terms the content should answer

Prioritize natural coverage of queries such as:
- What are UX laws?
- What are the main UX laws?
- What are Nielsen’s 10 heuristics?
- How to apply Fitts’s Law to buttons and interfaces?
- What is the Hick-Hyman Law and how to organize options?
- How to improve usability of a site or app?
- How to run a heuristic evaluation?
- How to apply UX to dashboards, SaaS and platforms?
- How to reduce cognitive load in forms and onboarding?
- How to improve digital accessibility according to WCAG 2.2?
- How to use UX laws with Lovable, Claude Code, Cursor and other AI tools?

These queries are search-intent hypotheses. Validate demand and language with Search Console, keyword tools, site data and real user questions. Do not assume search volume.

### Limits and transparency

No SEO, AEO or GEO practice guarantees indexing, prominence, inclusion in answers, citation by AI or traffic. External systems change their algorithms and criteria. Do not promise “ranking in ChatGPT”, “being cited by Google” or equivalent results. The controllable goal is to publish original, verifiable, technically accessible and easy-to-understand content.

## SEO and organic discovery

SEO helps content be found and understood. No technique guarantees fame, virality or a specific position in Google.

**Primary keyword:** UX laws.

**Secondary keywords:** UX principles; usability heuristics; usability laws; psychology applied to UX; interaction design; Nielsen heuristics; Gestalt in design; mental models in UX; cognitive load in interfaces; user experience in digital products; heuristic evaluation; digital accessibility; usability testing; UX for websites; UX for dashboards; UX for SaaS; UX for apps; UX in Lovable; UX with AI; AEO; GEO; answer engine optimization; generative engine optimization.

**Search intent:** informational and educational.

**Suggested SEO title:** UX Laws: Complete Guide to Usability, Principles and Heuristics.

**Suggested SEO description:** Learn the main UX laws, Nielsen heuristics, Gestalt principles and behavior models. Understand what they are, why they matter and how to apply them in digital products.

**Suggested slug:** ux-laws.

### Structure for web publication

A descriptive H1; H2 by category; H3 by concept; navigable table of contents; internal links; primary sources; original examples; review date; editorial owner; alternative texts; semantic tables.

### Good practices

Answer search intent at the start. Use English terms and common synonyms on first occurrence. Avoid artificial keyword repetition. Include original examples, verifiable sources and working links. Maintain stable URLs, speed, accessibility, readability and mobile experience.

### Authority and popularity

SEO does not guarantee fame. To broaden adoption, combine original content, examples, sources, clear license, versions, external contributions, community outreach and maintenance. Do not confuse vanity metrics with real usefulness.
