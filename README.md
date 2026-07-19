# Auto-Testing

Early-stage UX risk assessment for software teams—before development or release.

**For whom:** Product designers, UX generalists, design leads, product teams, and outsourced designers who must make consequential design decisions without enough time or research capacity to test every iteration.

**Product model:** A computational UX evaluation layer that analyzes interfaces, user flows, and task scenarios to identify likely usability risks.

**Core value:** Faster, more systematic pre-development assessment of cognitive load, confusion, memory demands, unnecessary actions, and task-completion difficulty.

**Evidence model:** Findings should be traceable, explainable, uncertainty-aware, and positioned as decision support—not as a replacement for representative users.

**Workflow:** Upload or describe a flow → define the user and task → receive prioritized risk findings → review explanations → revise the design or escalate selected risks to human testing.

**Platform:** Web product, followed by a responsive mobile experience.

**Tone:** Clear, credible, analytical, and supportive. The product should help teams make better decisions without pretending that simulated evidence is human evidence.

**Current screens:** 5 product screens.

**Status:** Research validation and early product design. The initial hypothesis, target audience, JTBDs, competitor coverage, unmet needs, and product-positioning direction have been documented.

## Repository Index

| Document | Description |
| --- | --- |
| [README.md](https://github.com/Vitalli-Liubinskiy/Auto-Testing/blob/main/README.md) | Project overview, current positioning, research summary, and next steps. |
| [research/research.md](research/research.md) | Full research report in Markdown: hypothesis development, audience profile, coded statistics, JTBD prioritization, competitor matrix, functionality patterns, review excerpts, and sources. |
| [research/research.html]([https://github.com/Vitalli-Liubinskiy/Auto-Testing/blob/main/research/research.html](https://research-eight-steel.vercel.app/)) | Interactive HTML version of the research report with charts, tables, source details, and light/dark appearance support. |
| [research/screens/](research/screens) | Screenshots and visual evidence collected during competitor and product research. |

**Live research report:** [https://research-eight-steel.vercel.app](https://research-eight-steel.vercel.app/)

## Research Summary

### Initial hypothesis

Designers—especially outsourced designers—lack the time, resources, participant access, or organizational support required to conduct user testing. A computational evaluation product could replace some unavailable testing and identify usability problems before development.

### How the hypothesis changed

The research supports the existence of a problem, but not the absolute claim that designers cannot test. Designers do conduct research when time, tools, participants, organizational support, and decision authority are available.

The stronger problem statement is:

> Teams make more consequential design decisions than they can validate with timely, credible evidence before development or release.

The proposed product should therefore be positioned as a **pre-development UX decision-risk assessment layer** that complements human research. It should identify likely risks, explain the reasoning, communicate uncertainty, and recommend where representative-user testing is still necessary.

### Target audience

**Primary users:** Product designers and UX generalists who make frequent pre-development decisions and have enough UX knowledge to review assessment results.

**Primary buyers:** Design leads, product leads, DesignOps, and ResearchOps owners responsible for decision quality, research capacity, rework, and stakeholder alignment.

**Secondary segment:** Agencies and outsourced designers who need fast, client-defensible evidence but may have limited control over budgets, participant access, or whether findings are implemented.

**Best-fit situation:** A consequential flow or concept is approaching development handoff, the design can still be changed, and representative research cannot fit the decision window.

### Competitors and substitutes

The research covers three groups:

- **Direct competitors:** Synthetic-user tools, AI UX review tools, and predictive attention products.
- **Indirect competitors:** Unmoderated and moderated user-testing platforms, prototype-testing tools, participant panels, and post-launch experience analytics.
- **Other substitutes:** Manual heuristic evaluation, cognitive walkthroughs, guerrilla testing, internal stakeholder review, launching and learning from production metrics, or conducting no formal evaluation.

Examples studied include Attention Insight, Versive AI Tests, synthetic-user products, Maze, UserTesting, Lyssna, Useberry, UXtweak, Microsoft Clarity, Hotjar, Fullstory, and Contentsquare.

### Method

The research combines evidence published primarily from 2025 through July 2026 with coded product reviews, practitioner discussions, competitor materials, market evidence, and analyst synthesis.

The competitor dataset contains:

- 50 coded feedback units;
- 14 JTBD categories;
- 19 competitors or substitute approaches;
- satisfaction coding of `2 = satisfied`, `1 = partially satisfied`, and `0 = not satisfied`;
- functionality, failure-reason, competitor-category, evidence-quality, and source-category codes;
- verbatim excerpts linked to public sources.

Frequency represents coverage in the collected evidence—not market prevalence. Missing evidence in the competitor matrix is left blank and is not treated as dissatisfaction.

### Main finding

Existing alternatives satisfy narrow jobs well:

- Real-user platforms provide credible evidence about task failure and early design choices.
- Predictive-attention tools assess visual hierarchy before traffic exists.
- Post-launch analytics reveals real friction, bugs, and drop-offs at scale.
- Manual heuristic reviews provide a fast, inexpensive, and explainable baseline.

However, no reviewed competitor category combines:

- pre-development speed;
- multi-step cognitive-risk explanation;
- credible and traceable reasoning;
- explicit uncertainty;
- calibration against later human or production outcomes;
- clear escalation to representative-user testing.

This is the strongest current opportunity for differentiation.

### Priority jobs to be done

The highest-priority jobs, based on coded frequency and dissatisfaction, are:

1. Find where users are likely to fail a task.
2. Reach or account for representative users within the decision window.
3. Make a defensible design decision.
4. Reduce analysis and synthesis effort.
5. Test frequently within a constrained budget.
6. Reduce study-setup effort.
7. Explain multi-step cognitive risk.

The most structurally unmet jobs are explaining memory, comprehension, and decision demands across a flow; discovering unknown user needs without authentic users; and calibrating predictions against later observed outcomes.

## Current Product Scope

The product currently has **5 screens**. They represent the initial experience needed to communicate and test the core assessment workflow.

The next design iteration should ensure that the screens clearly support:

1. Starting a new UX assessment.
2. Providing the interface, user-flow, task, and audience context.
3. Reviewing prioritized usability and cognitive-risk findings.
4. Understanding the evidence, explanation, severity, and uncertainty behind each finding.
5. Deciding whether to revise the design, share the result, or escalate a risk to human testing.

## Next Steps

- Finalize the screen map for the five existing screens.
- Document the primary and alternative user flows.
- Test whether designers understand and trust the risk explanations.
- Compare model findings with expert walkthroughs and representative-user tests.
- Measure whether assessments change design decisions, reduce synthesis time, or improve research prioritization.
- Run segment-specific buyer interviews with in-house design/product leads, DesignOps/ResearchOps leads, and agency owners.
- Validate willingness to pay and identify the budget or existing workflow the product would replace or protect.
- Create design folders such as `wireframes/`, `concept/`, `tokens/`, `components/`, `design-system/`, and `handoff/` only when real design content is ready.
