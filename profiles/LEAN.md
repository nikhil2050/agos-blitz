# Lean Profile — roughly 50% depth

Choose for faster exploration and MVP delivery.

**When to use**
- You want to validate an idea quickly with minimal overhead
- You are building an MVP or prototype rather than a production-ready product
- You need to move fast and separate core scope from later ideas

**Focus areas**
- Target user and their urgent problem
- Current workaround the user already relies on
- Value hypothesis (why this solution is worth building)
- Focused competitor scan (not exhaustive research)
- Riskiest assumptions to test first
- Low-cost validation approach
- Simple business model
- One primary user journey (narrow MVP)
- Testable requirements with clear acceptance criteria
- Practical technology decision (no over-engineering)
- Essential architecture, security, and core tests only
- Launch and feedback loop

**Documentation**
- Keep documents concise
- Do not skip essential privacy, security, legal/regulatory, or safety checks
- Separate later ideas from MVP scope

**Prompt and phase format**
For each phase, give the agent the current context, one focused task, constraints, and the expected artifact or decision. 
Follow the phase order in `workflows/PRODUCT_LIFECYCLE.md`, but combine or skip phases only with explicit founder approval and a recorded consequence.

**Good and bad decisions**
- Good: choose the smallest practical solution that satisfies the MVP requirement and record the assumption being tested.
- Bad: over-engineer, silently expand scope, skip essential checks, or present an assumption as validated evidence.

**Lean completion checklist**
- [ ] MVP goal and non-goals are clear
- [ ] Requirements are testable and have acceptance criteria
- [ ] Riskiest assumptions and open questions are recorded
- [ ] Essential security, privacy, accessibility, and safety checks are complete
- [ ] Tests/checks and actual outcomes are documented
- [ ] The relevant approval gate is explicit

**Session continuity**
Before ending a session, update `docs/AI_CONTEXT.md` with decisions, assumptions/risks, current task status, files changed, tests, limitations, and next steps. At the next session, read it and inspect repository state before continuing. Do not rely on chat history alone.
