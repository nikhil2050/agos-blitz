# ⚡ AgOS Blitz

> **Ag**entic **OS** for **B**uilding & **L**aunching **I**deas with **T**actical **Z**eal.

A modular, reusable, business-first repository template for building raw products ideas from zero to production at ligtning speed, equipped with pre-configured AI workflows, and clean architectural patterns.

Primary agents: OpenAI Codex and Claude Code. 

The core is portable to other agents.

## Quick start
1. Create a new repository from this template.
2. Read `AGENTS.md` and the matching file in `agents/`.
3. Use the root `PROJECT_BRIEF.md` (copy/replace it from `templates/PROJECT_BRIEF.md` for each new idea).
4. Choose `profiles/COMPREHENSIVE.md` or `profiles/LEAN.md`.
5. Choose relevant modules from `project-types/` and skills from `skills/`.
6. Ask the agent: "Read the framework instructions and PROJECT_BRIEF.md. Start Phase 0. Guide me through discovery one question at a time. Do not code until the relevant approvals."
7. Follow `workflows/PRODUCT_LIFECYCLE.md` and approve each gate.

## Principles
- Business before code. 
- Founder controls direction and technology. 
- Ask before assuming. 
- Separate facts, assumptions and hypotheses. 
- No fabricated research or validation. 
- No premature implementation. 
- Maintain documentation and context between sessions.

## Structure
- `AGENTS.md`: shared agent contract
- `agents/`: Codex, Claude Code and generic adapters
- `profiles/`: comprehensive and lean execution depth
- `workflows/`: lifecycle, research, technology decisions and handoff
- `prompts/`: phase-specific copy/paste prompts
- `skills/`: specialist playbooks
- `project-types/`: optional product-type overlays
- `templates/`: project brief and documentation templates
- `checklists/`: quality and approval checklists
- `knowledge/`: glossary

The agent should load only the resources relevant to the current project and phase. 
Create project-specific documents in `docs/` as needed; do not fabricate content for irrelevant documents.
