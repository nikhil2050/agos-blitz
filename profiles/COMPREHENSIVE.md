# Comprehensive Profile

Choose for detailed, high-confidence product development.

**When to use**
- You are building a production-bound product where mistakes are costly
- You need high confidence before committing to build
- You want full documentation across discovery, business, product, UX, architecture, and delivery

**Discovery & business analysis**
- Customer and problem exploration
- Market, alternatives, and differentiation
- Validation plan and evidence
- Business model, pricing, costs, and unit economics
- Positioning, acquisition, retention, and growth
- Quantitative models show formulas and assumptions

**Product definition**
- Detailed PRD, journeys, scope, and requirements
- Edge cases and acceptance criteria
- MVP definition with clear non-goals

**UX/UI**
- UX/UI specification

**Technology & architecture**
- Architecture alternatives comparison
- Data and API design
- Security and privacy
- Delivery plan
- Testing and operations
- Launch plan (as relevant)

**Governance**
- Use approval gates for: problem framing, business direction, MVP, UX, architecture, and release
- Avoid detail that does not inform a decision

**Agent prompt standard**
Every phase brief should state:
- Context: project, current phase, known decisions, constraints, and relevant evidence
- Task: the specific question or work requested
- Expected output: named artifact, format, depth, and decision the output should enable
- Open questions, assumptions, risks, and the approval gate that follows

**Phase execution sequence**
Use the lifecycle sequence in `workflows/PRODUCT_LIFECYCLE.md`: setup, discovery, business analysis, product definition, UX/UI, technology/architecture, delivery planning, implementation, release readiness, and launch/learning. For each phase, complete its outputs, record assumptions and risks, run the relevant quality checks, and pause for the stated founder approval gate.

**Decision examples**
- Good: compare architecture options against explicit product, security, cost, and operations criteria; record the trade-off and obtain approval.
- Bad: silently choose a technology, add unapproved scope, or claim validation, testing, or research that was not performed.

**Completion checklist**
- [ ] Phase objective, actor, scope, and expected output are explicit
- [ ] Requirements include priorities, dependencies, edge cases, security/privacy implications, and testable acceptance criteria
- [ ] Assumptions, risks, evidence, and unresolved questions are recorded
- [ ] Relevant tests and quality checks are run, with actual outcomes documented
- [ ] Founder approval is recorded before crossing the phase gate
- [ ] Documentation and context are updated before handoff

**Documentation and session continuity**
At the end of every session update `docs/AI_CONTEXT.md`, decisions, assumptions/risks, roadmap or task status, files changed, tests, limitations, and next steps. At the next session read those records and inspect the repository before continuing. Treat `workflows/SESSION_HANDOFF.md` as the required handoff procedure; do not rely on chat history alone.
