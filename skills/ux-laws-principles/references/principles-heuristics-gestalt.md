# Principles, Heuristics and Gestalt in UX

## Jakob Nielsen’s 10 usability heuristics

Heuristics are general inspection principles, not exact technical requirements or a scoring formula. **Primary source:** [Nielsen, 10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/). **Historical basis:** [Nielsen & Molich (1990), Heuristic evaluation of user interfaces](https://doi.org/10.1145/97243.97281).

1. **Visibility of system status**
   - **What:** Inform what is happening through timely feedback.
   - **Why:** Without feedback, the person does not know whether the action was received or failed.
   - **Who:** Everyone, especially in lengthy operations.
   - **Where:** Loading, saving, upload, payment and navigation.
   - **When:** After actions or state changes.
   - **How:** Clear states, real progress and confirmation.

2. **Match between system and the real world**
   - **What:** Language and sequence understandable to the audience.
   - **Why:** Reduces mental translation.
   - **Who:** Novices and non-technical audiences.
   - **Where:** Labels, forms, reports and flows.
   - **When:** Jargon confuses.
   - **How:** Audience vocabulary, familiar units and comprehension testing.

3. **User control and freedom**
   - **What:** Exits, undo, back and correct.
   - **Why:** Errors and changes of intention are inevitable.
   - **Who:** Everyone, especially in irreversible actions.
   - **Where:** Modals, editing, checkout and deletion.
   - **When:** Accidental or hard-to-reverse action.
   - **How:** Cancel, back, undo, edit and preserve data.

4. **Consistency and standards**
   - **What:** Similar elements should have coherent language and behavior.
   - **Why:** Reduces relearning.
   - **Who:** Novices and returning users.
   - **Where:** Buttons, icons, navigation and fields.
   - **When:** The same action varies without reason.
   - **How:** Keep semantics and behavior coherent.

5. **Error prevention**
   - **What:** Avoid problems before correcting them.
   - **Why:** Prevention costs less effort.
   - **Who:** Everyone, especially in critical actions.
   - **Where:** Forms, payments, permissions and deletions.
   - **When:** Error is predictable or costly.
   - **How:** Valid formats, examples, contextual validation and confirmation.

6. **Recognition rather than recall**
   - **What:** Reduce the need to remember information across screens.
   - **Why:** Visible cues lower memory load.
   - **Who:** Novices and occasional users.
   - **Where:** Menus, filters, history and comparisons.
   - **When:** User needs to recall codes or data.
   - **How:** Visible options, examples and summaries.

7. **Flexibility and efficiency of use**
   - **What:** Serve both novices and experts.
   - **Why:** Experience and frequency vary.
   - **Who:** Heterogeneous audiences.
   - **Where:** Shortcuts, commands, filters and bulk actions.
   - **When:** Repeated tasks cost too much effort.
   - **How:** Clear basic paths and discoverable advanced features.

8. **Aesthetic and minimalist design**
   - **What:** Irrelevant information should not compete with the important.
   - **Why:** Noise makes priorities harder.
   - **Who:** Everyone, especially on dense screens.
   - **Where:** Dashboards, forms and reports.
   - **When:** Decoration diverts attention.
   - **How:** Remove what does not help without hiding essential context.

9. **Help users recognize, diagnose, and recover from errors**
   - **What:** Explain the problem and indicate recovery.
   - **Why:** Generic messages do not orient.
   - **Who:** Everyone, especially non-technical audiences.
   - **Where:** Authentication, payment, upload and integrations.
   - **When:** Operation fails.
   - **How:** Say what happened, what was preserved and how to correct.

10. **Help and documentation**
    - **What:** Support that is easy to find and task-focused.
    - **Why:** Not every operation can be self-explanatory.
    - **Who:** Novices and complex tasks.
    - **Where:** Contextual help, FAQ and onboarding.
    - **When:** Task requires specific knowledge.
    - **How:** Short instructions, examples and search.

## Don Norman’s principles

**Primary reference:** Norman, D. A., *The Design of Everyday Things* (revised edition, 2013). The work develops conceptual models, feedback, mapping, affordances and signifiers. Terminology was refined across editions; do not treat each term as an immutable taxonomy.
- **Discoverability:** Perceive possible actions and where to execute them. Use clear labels, states and signals.
- **Feedback:** Communicate the result of an action in a timely and proportional way.
- **Conceptual model:** Represent in an understandable way how the system works.
- **Affordances:** Properties that enable actions.
- **Signifiers:** Perceptible signals that indicate where and how to act, such as labels, icons and handles.
- **Mapping:** Relationship between control and effect; bring control and affected object closer.
- **Constraints:** Physical, logical, semantic or cultural limits that prevent invalid actions; explain the constraint and offer an alternative.

Affordance and signifier are not synonyms. In digital interfaces, signals help discover the real possibility of action.

## Gestalt

**Historical reference:** Koffka, K. (1935), *Principles of Gestalt Psychology*. The descriptions below are didactic syntheses of perceptual principles. Transposition to digital interfaces is a design application, not a list of normative testable criteria.
- **Proximity:** Nearby elements appear related. Bring labels, fields and help closer.
- **Similarity:** Similar elements appear to belong to the same category. Use coherent patterns.
- **Common region:** Elements in the same area appear grouped. Avoid excessive nested containers.
- **Uniform connectedness:** Elements that share a connected visual region (shared boundary, continuous surface, or explicit link) tend to be perceived as a single unit more strongly than by proximity or similarity alone. Use cards, shared backgrounds, connectors and clear group boundaries; do not rely only on spacing when grouping is critical.
  - **Reference:** [Palmer & Rock (1994), Rethinking perceptual organization: The role of uniform connectedness](https://doi.org/10.3758/BF03206880). Perceptual organization research; interface application is a design interpretation.
- **Continuity:** The eye follows alignments and sequences. Use grids and hierarchy.
- **Figure-ground:** Differentiate content and background; preserve contrast.
- **Closure:** Perception completes incomplete forms; do not make controls ambiguous.
- **Symmetry and order:** Balance can help, but do not force symmetry.
- **Common fate:** Elements that move together may appear related; use coordinated movement with meaning.

## Cross-cutting principles
Consistency; progressive disclosure; safe and reversible defaults; direct manipulation with accessible alternatives; error tolerance; user agency; proportional feedback; alignment between appearance and behavior; prefer the simplest adequate solution (**Occam’s Razor** as design heuristic, not scientific UX law—see laws reference); constrain open-ended work when time or scope expands without value (**Parkinson’s law** as project adage, not interaction law).

## Accessibility: WCAG POUR
- **Perceivable:** Information presented in ways people can perceive.
- **Operable:** Components and navigation usable, including by keyboard.
- **Understandable:** Content and operation clear and predictable.
- **Robust:** Content interpretable by different agents, including assistive technologies.

**Normative sources:** [W3C, WCAG 2.2](https://www.w3.org/TR/WCAG22/) and [W3C WAI, WCAG Overview](https://www.w3.org/WAI/standards-guidelines/wcag/). WCAG 2.2 has testable criteria and levels A, AA and AAA. Isolated automated checks do not prove conformance. Evaluate full pages and responsive states.

## Ethics and autonomy

The recommendations in this section are editorial and ethical design criteria of the project. For evaluation of manipulative patterns, also consult [FTC, Bringing Dark Patterns to Light](https://www.ftc.gov/reports/bringing-dark-patterns-light) and [OECD, Dark Commercial Patterns](https://www.oecd.org/en/publications/dark-commercial-patterns_44f5e846-en.html).
Show prices, renewal, fees and consequences before commitment. Keep cancellation and controls accessible. Do not fabricate scarcity, social proof, progress or urgency. Avoid hidden costs, forced continuity and obstructive cancellation. Optimize informed success, not only clicks.
