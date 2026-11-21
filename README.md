# `/ai` — AI Sandbox & Work-in-Progress Initiatives

Welcome to the `/ai` directory! This folder serves as a dedicated landing zone for experimental AI initiatives, proof-of-concepts (PoCs), prompt engineering drafts, and early-stage ideas.

> ** Status: Experimental / Work in Progress**  
> Code, scripts, and documentation in this directory are actively evolving. Items here are not yet production-ready and may undergo breaking changes, refactoring, or deprecation without notice.

---

## Please note that not all folders are public so you may not see everything here - if you are expecting to see something and you don't please contact the admin

##  Purpose

- **Rapid Prototyping:** Test new models, SDKs, and agentic workflows without impacting the main codebase
- **Idea Incubation:** Store architectural notes, evaluation benchmarks, and brainstorming docs before formalizing them into core features
- **Shared Visibility:** Give teammates a clear view into ongoing AI explorations and prevent duplicate efforts

---

## Structure & Conventions

To keep this workspace navigable as ideas grow, please follow these lightweight conventions when adding new work:

- **Group by Initiative:** Place distinct experiments in their own subfolders using kebab-case (e.g., `/ai/rag-search-poc`, `/ai/automated-triage-agent`)
- **Keep governance folders separate from codebase
- **Include a Quick Note:** Add a brief `NOTES.md` or header comment inside your subfolder explaining:
  - What problem the experiment is trying to solve.
  - Current status (`Exploring`, `Testing`, `Paused`, or `Ready for Promotion`).
  - Any required environment variables or API keys.
- **Keep Secrets Out:** Never hardcode API keys or commit `.env` files. Reference keys via environment variables and document required variable names.

---

## Graduation Criteria

When an initiative proves valuable and is ready to move out of `/ai` into the main application:

1. Add unit/integration tests and proper error handling.
2. Complete a standard code and security review.
3. Move the code to its permanent home in the repository and clean up the temporary folder here.
