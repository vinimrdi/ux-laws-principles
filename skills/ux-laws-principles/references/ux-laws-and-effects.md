# UX Laws and Effects

UX laws are behavioral or perceptual trends, not deterministic formulas. For each concept: **What** (definition), **Why** (mechanism), **Who** (audience), **Where** (application), **When** (condition) and **How** (practical decision).

## Fitts’s Law
- **What:** Selection time depends on target size and distance; larger and closer targets tend to be easier.
- **Why:** Small targets demand higher motor precision.
- **Who:** Everyone, especially touch users and people with motor limitations.
- **Where:** Buttons, links, icons, menus and controls.
- **When:** Touch errors, imprecise clicks or hard-to-reach targets.
- **How:** Increase clickable area, spacing and comfortable reach; separate destructive actions.
- **Limit:** Does not mean everything must be huge; hierarchy and accessibility criteria also matter.
- **Reference:** [Fitts (1954), original study](https://doi.org/10.1037/h0055392); [Accot & Zhai (1997), trajectory tasks](https://doi.org/10.1145/258549.258760).

## Hick-Hyman Law
- **What:** Decision time tends to grow with the number of plausible alternatives and the uncertainty among them.
- **Why:** Comparing options requires attention and uncertainty reduction.
- **Who:** Novices, users with low familiarity or under pressure.
- **Where:** Menus, navigation, filters, plans, onboarding and settings.
- **When:** Slow choice, similar alternatives or abandonment.
- **How:** Group by meaning, differentiate options, use safe defaults and reveal complexity gradually.
- **Limit:** Do not reduce every list; experts may prefer more visible options.
- **Reference:** [Hick (1952)](https://doi.org/10.1080/17470215208416600); [Hyman (1953)](https://doi.org/10.1037/h0056940); [Proctor & Schneider (2018), review and limitations](https://doi.org/10.1080/17470218.2017.1322622).

## Jakob’s Law
- **What:** Users bring expectations learned from other products.
- **Why:** Familiar conventions reduce learning and surprise.
- **Who:** New users and people who switch between products.
- **Where:** Navigation, search, login, forms and common controls.
- **When:** New patterns cause hesitation or errors.
- **How:** Respect useful conventions and teach innovations at the point of use.
- **Limit:** Does not mean copying competitors or perpetuating bad patterns.
- **Reference:** [Nielsen (2000), formulation of Jakob’s Law](https://www.nngroup.com/articles/end-of-web-design/).

## Tesler’s Law
- **What:** The inherent complexity of a system does not disappear; it is distributed between system and user.
- **Why:** Domain rules and decisions continue to exist.
- **Who:** Users of complex processes, SaaS and professional tools.
- **Where:** Sign-up, import, configuration, automation and approval.
- **When:** The user faces technical details the system could handle.
- **How:** Automate repetition, request data at the right moment and expose important decisions.
- **Limit:** Automation can remove transparency and control.
- **Reference:** [Tesler’s Law, historical synthesis and secondary sources](https://designatlas.org/en/disciplines/ux-design/teslers-law/). There is no known original experimental paper that establishes this formulation as a psychological law.

## Postel’s Law (robustness principle)
- **What:** Engineering principle: be conservative in what you send and liberal in what you accept.
- **Why:** Systems need to handle data variation.
- **Who:** Product/engineering teams and users who enter data.
- **Where:** Fields, dates, phone numbers, imports and integrations.
- **When:** Benign variations cause failures.
- **How:** Accept safe variations, normalize, validate and produce consistent outputs.
- **Limit:** Excessive permissiveness creates ambiguity and risk; it is not a universal UX law.
- **Reference:** [Postel (1980), RFC 761](https://www.rfc-editor.org/info/rfc761/). Protocol engineering source, not UX research.

## Law of Prägnanz (good form)
- **What:** Perception tends to organize ambiguous stimuli into simple and stable forms.
- **Why:** Coherent structures are easier to interpret.
- **Who:** Everyone, especially in dense interfaces.
- **Where:** Composition, dashboards, groupings and charts.
- **When:** Weak hierarchy or excessive visual competition.
- **How:** Use alignment, grouping and hierarchy; remove decoration that competes.
- **Limit:** Simplicity is not absence of information.
- **Reference:** [Koffka (1935), Principles of Gestalt Psychology](https://www.routledge.com/Principles-Of-Gestalt-Psychology/Koffka/p/book/9781315009292). Historical Gestalt psychology reference; specific application to interfaces is a design interpretation.

## Miller’s Law and working memory
- **What:** Classic research on immediate memory; “7 ± 2” is not a universal limit of items in an interface.
- **Why:** Working memory is limited and varies by task, knowledge and grouping.
- **Who:** People facing new information or long tasks.
- **Where:** Forms, menus, tables and onboarding.
- **When:** Users forget data between screens or lose context.
- **How:** Group, keep instructions next to the action, show summaries and allow resuming.
- **Limit:** Do not limit menus to seven items.
- **Reference:** [Miller (1956)](https://doi.org/10.1037/h0043158); [Cowan (2001), critical review of short-term memory capacity](https://doi.org/10.1017/S0140525X01003922); [Cowan (2015), retrospective](https://doi.org/10.1037/a0039035).

## Recognition rather than recall
- **What:** Recognizing visible options usually requires less effort than remembering them without cues.
- **Why:** Cues help identify alternatives.
- **Who:** Novices and occasional users.
- **Where:** Menus, filters, forms, history and settings.
- **When:** The person forgets codes, requirements or options.
- **How:** Show options, examples, recent choices and summaries.
- **Limit:** Do not expose so many options that overload is created.
- **Reference:** [Nielsen (1994), recognition rather than recall heuristic](https://www.nngroup.com/articles/ten-usability-heuristics/).

## Serial position effect
- **What:** Items at the beginning and end may be better remembered.
- **Why:** Primacy and recency influence memory.
- **Who:** People who scan lists and sequences.
- **Where:** Menus, onboarding, lists and presentations.
- **When:** Order influences recall.
- **How:** Give clear position to critical information and reinforce points in summaries.
- **Limit:** Context and relevance can dominate the effect.
- **Reference:** [Murdock (1962), serial position effect in free recall](https://doi.org/10.1037/h0045106).

## Von Restorff effect (isolation)
- **What:** An element that differs from the set can receive more attention and be remembered.
- **Why:** Contrast attracts relative attention.
- **Who:** Users who need to identify priority.
- **Where:** CTA, alerts, recommendations and selected states.
- **When:** There is real priority without sufficient hierarchy.
- **How:** Reserve emphasis for priorities and justify recommendations.
- **Limit:** If everything stands out, nothing stands out; do not induce choices deceptively.
- **Reference:** [von Restorff (1933), original study; historical synthesis by MacLeod (2020)](https://doi.org/10.3758/s13421-020-01033-5); [Johansson (1970), attention and isolation effect](https://doi.org/10.1111/j.2044-8295.1970.tb01234.x).

## Zeigarnik effect
- **What:** Incomplete tasks can remain cognitively salient in certain contexts.
- **Why:** Pending goals continue to occupy attention.
- **Who:** Users in long or interruptible tasks.
- **Where:** Onboarding, forms, projects and drafts.
- **When:** The person needs to pause and resume.
- **How:** Save, show what remains and allow resuming.
- **Limit:** Do not fabricate anxiety or pressure; evidence varies.
- **Reference:** [Zeigarnik (1927), original study; historical evaluation by MacLeod (2020)](https://doi.org/10.3758/s13421-020-01033-5).

## Peak-end rule
- **What:** Retrospective evaluation can be influenced by intense moments and by the ending.
- **Why:** Memory is not a perfect average of every instant.
- **Who:** Users evaluating journeys, purchases and support.
- **Where:** Checkout, support, onboarding and completion.
- **When:** A task needs to be closed or a difficult experience recovered.
- **How:** Confirm results, explain next steps and preserve work.
- **Limit:** A pleasant ending does not compensate for a bad journey.
- **Reference:** [Kahneman et al. (1993), Adding a Better End](https://doi.org/10.1111/j.1467-9280.1993.tb00589.x). Study of specific aversive experiences, not digital journeys in general.

## Doherty threshold
- **What:** Fast responses favor continuity; 400 ms is a historical reference, not a universal modern budget.
- **Why:** Delays without feedback generate uncertainty.
- **Who:** Users in frequent or sequential tasks.
- **Where:** Search, save, generation and navigation.
- **When:** The interface seems frozen or actions are repeated.
- **How:** Immediate feedback, real progress and latency optimization.
- **Limit:** Feedback does not make a slow operation fast; measure.
- **Reference:** [Doherty & Thadhani (1982), The Economic Value of Rapid Response Time](https://www.ibm.com/support/pages/system/files/inline-files/EconomicValueofResponseTime.pdf). IBM technical report; the 400 ms reference is not a universal standard.

## Response-time limits and Core Web Vitals
- **Category:** Engineering/performance guidance grounded in perception research — **not** a psychological law. Complements the Doherty threshold.
- **What:** Perceived speed shapes whether an interface feels responsive. Two reference sets are used in practice: Nielsen’s three response-time limits (about 0.1 s feels instant, about 1 s keeps flow without special feedback, about 10 s is the limit of attention) and Google’s Core Web Vitals field thresholds.
- **Why:** Delay without feedback creates uncertainty and abandonment; layout that shifts under the user causes mis-taps and lost trust.
- **Who:** All users, worse on slow networks and low-end devices.
- **Where:** Page load, navigation, search, generation, any state transition.
- **When:** The interface feels slow, frozen, or jumps while loading.
- **How:** Give immediate feedback and real progress; reserve space so content does not shift; measure with field data, not only lab. Current “good” Core Web Vitals thresholds (verify against web.dev; they can change): Largest Contentful Paint (LCP) ≤ 2.5 s; Interaction to Next Paint (INP) ≤ 200 ms; Cumulative Layout Shift (CLS) ≤ 0.1. INP replaced First Input Delay as a Core Web Vital in March 2024.
- **Limit:** Fast metrics do not fix an unclear task or a wrong flow; a good score is not a good experience. These are field guidance, not a universal interaction law.
- **Reference:** [Nielsen, Response Times: The 3 Important Limits](https://www.nngroup.com/articles/response-times-3-important-limits/); [web.dev, Web Vitals](https://web.dev/articles/vitals); [LCP](https://web.dev/articles/lcp); [INP](https://web.dev/articles/inp); [CLS](https://web.dev/articles/cls).

## Goal-gradient effect
- **What:** Motivation can increase when the person perceives proximity to the goal.
- **Why:** Progress makes completion more concrete.
- **Who:** Users in tasks with clear steps.
- **Where:** Onboarding, configuration, courses and publishing.
- **When:** Long task and measurable progress.
- **How:** Show real steps, milestones and remaining items.
- **Limit:** Do not invent progress or apply pressure.
- **Reference:** [Kivetz, Urminsky & Zheng (2006), Goal-Gradient Hypothesis](https://doi.org/10.1509/jmkr.43.1.39). Studies in reward programs and purchase behavior.

## Aesthetic-usability effect
- **What:** An attractive interface can be perceived as easier even without objective usability gain.
- **Why:** Aesthetics influence expectation and trust.
- **Who:** Everyone, especially on first impressions.
- **Where:** Landing pages, onboarding and dashboards.
- **When:** Quality perception affects trust.
- **How:** Care for hierarchy and legibility; evaluate aesthetics and task separately.
- **Limit:** Beauty does not prove usability.
- **Reference:** [Kurosu & Kashimura (1995)](https://doi.org/10.1145/223355.223680); [Tractinsky, Katz & Ikar (2000)](https://doi.org/10.1016/S0953-5438(00)00031-X).

## Pareto principle
- **What:** Pattern of unequal distribution popularized as 80/20.
- **Why:** Impacts can concentrate on few factors.
- **Who:** Teams prioritizing problems and resources.
- **Where:** Analytics, support and backlog.
- **When:** There is data to identify concentration.
- **How:** Analyze real distribution; prioritize frequency, severity and value.
- **Limit:** Do not assume a fixed proportion; it is not a UX law.
- **Reference:** There is no single primary source that supports universal application of 80/20 to UX. Use Pareto only as a distribution hypothesis to test with the product’s own data.

## Choice overload
- **What:** Many alternatives can make decisions harder under certain conditions.
- **Why:** Comparing requires attention and criteria.
- **Who:** People with low familiarity or unclear criteria.
- **Where:** Plans, catalogs, filters and settings.
- **When:** The user cannot compare or justify a choice.
- **How:** Organize, highlight differences and allow comparison.
- **Limit:** Variety can be valued; results depend on context.
- **Reference:** [Iyengar & Lepper (2000), When Choice Is Demotivating](https://doi.org/10.1037/0022-3514.79.6.995). Do not generalize results to any number of options or situation.

## Endowment effect
- **What:** People may value more highly something they feel they own.
- **Why:** Psychological ownership and loss aversion.
- **Who:** Users who create and personalize digital assets.
- **Where:** Projects, libraries and collections.
- **When:** Perceived ownership favors care.
- **How:** Allow personalize, export and delete.
- **Limit:** Do not make cancellation or deletion difficult.
- **Reference:** [Kahneman, Knetsch & Thaler (1990), Experimental Tests of the Endowment Effect](https://doi.org/10.1086/261737).

## Sunk cost effect
- **What:** Irrecoverable investment can influence future decisions.
- **Why:** People try to justify past effort.
- **Who:** Users in long flows, subscriptions and purchases.
- **Where:** Onboarding, renewal and cancellation.
- **When:** Past effort is used to pressure continuation.
- **How:** Allow exit without artificial penalty and explain real losses.
- **Limit:** Do not exploit the effect for retention.
- **Reference:** [Arkes & Blumer (1985), The Psychology of Sunk Cost](https://doi.org/10.1016/0749-5978(85)90049-4).

## Parkinson’s law
- **Category:** Adage / project principle — **not** an experimental psychological or interaction law.
- **What:** Work tends to expand to fill the time available for its completion (popular formulation of C. Northcote Parkinson, 1955).
- **Why:** Without clear constraints, scope, effort and duration often grow.
- **Who:** Product, design and engineering teams; users facing open-ended setup or configuration tasks.
- **Where:** Project planning, feature scope, onboarding length, forms, settings and research cycles.
- **When:** Deadlines, scope or stopping rules are vague and work keeps expanding without proportional value.
- **How:** Define timeboxes, MVP criteria, explicit non-goals and done conditions; constrain optional steps in flows.
- **Limit:** Do not use it to justify cutting necessary complexity (see Tesler). It does not predict user behavior with a formula and is not a substitute for prioritization evidence.
- **Reference:** Parkinson, C. N. (1955), “Parkinson’s Law,” *The Economist* (popular essay). Treat as management folklore applied carefully to product work, not as HCI research.

## Occam’s Razor (simplicity principle)
- **Category:** Philosophical / design heuristic — **not** a UX scientific law.
- **What:** Prefer the simplest adequate explanation or solution; do not multiply entities beyond necessity (medieval principle associated with William of Ockham; applied in science and design as a preference for simplicity).
- **Why:** Extra options, steps and decoration increase cost of comprehension and maintenance without guaranteed benefit.
- **Who:** Teams choosing between design alternatives; users facing dense interfaces.
- **Where:** Information architecture, flows, UI chrome, copy and feature sets.
- **When:** Two solutions achieve the same task outcome and one is clearly simpler to understand and operate.
- **How:** Remove steps, fields and visuals that do not support the task; keep essential complexity visible when the domain requires it.
- **Limit:** Simplicity is not the same as incompleteness. Occam does not authorize hiding required domain complexity (Tesler) or accessibility affordances. Beauty alone is not simplicity.
- **Reference:** Historical philosophical principle (William of Ockham). In design, treat as a cross-cutting preference aligned with minimalist heuristics, not as empirical UX law. Compare with Nielsen’s aesthetic and minimalist design heuristic and Tesler’s Law.

Not every popular concept called a “law” is a scientific law. Identify whether it is an empirical trend, psychological effect, principle, heuristic, model or metaphor. Do not invent authorship or date.
