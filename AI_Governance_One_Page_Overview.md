# AI Governance — One-Page Overview

*Prepared by Rick Aiere · November 2026 · Draws on NIST AI RMF, IBM AI governance, and EDM Association guidance*

## Purpose: say yes to AI, quickly and safely

AI governance exists so the company can approve good AI uses fast and stop bad ones early.  The objective is to make adoption smoother. 

It answers five questions, one template each:

1. **Who decides what AI we use, and how do we say yes quickly?** Governance template
2. **What AI are we running, and what is it doing for us?** AI inventory - as a pre-requisite


**Why now.** Most companies have no complete list of the AI they run. AI has rapidly been deployed and democratization has left a challenging landscape with many unknowns. 


## Three frameworks, one approach

We borrow from three frameworks instead of writing a fourth. NIST gives the structure, IBM the operating model, and the EDM Association the data foundation.

| Framework | What it contributes | How we use it |
| --- | --- | --- |
| [NIST AI RMF 1.0](https://www.nist.gov/itl/ai-risk-management-framework) (AI 100-1) and its Generative AI Profile (AI 600-1) | Four functions: **Govern, Map, Measure, Manage**. Voluntary, sector-neutral, and widely cited by regulators. NIST is revising it. | The spine. Every template maps to a function: governance → Govern, inventory and tiers → Map, report → Measure, register and incident response → Manage. |
| [IBM AI governance](https://www.ibm.com/think/insights/a-look-into-ibms-ai-ethics-governance-framework) | Principles of trust and transparency. Five pillars: explainability, fairness, robustness, transparency, privacy. A layered structure: an advisory committee, a central AI Ethics Board, and focal points in each business unit. | The operating model, scaled down: one AI council, plus a named focal point in each department as the first stop for requests and concerns. |
| [EDM Association](https://edmconnect.edmcouncil.org/aigovernanceforum/home) (formerly EDM Council) | Holds that AI governance rests on data management. DCAM and CDMC capability models, with CDMC being [extended to AI](https://www.waterstechnology.com/data-management/7953184/hld-thu-730edma-begins-rollout-of-ai-certification-framework). Working-group guidance on an operating model, RACI, KPIs and maturity. | The data readiness check (location, access, fitness, provenance) and the maturity scoring. |


## Operating model: who decides, who can stop it

The **AI Governance Council** is chaired by the CIO, with the CISO, General Counsel, CFO, HR and a rotating business sponsor. It owns the policy, approves high-tier uses, and can stop any AI use. A **focal point** in each department takes requests and approves low-risk uses. IT keeps the **inventory**. Every system has a named **business owner**.

**Approval path:** (1) **Request:** a half-page intake covering the problem, the pillar it serves (revenue, cost, asset use or risk), the data, buy or build, and the owner → (2) **Data check:** location, access, fitness, provenance → (3) **Tier:** low, medium or high, by autonomy, the data it touches, and its effect on people and money → (4) **Approve at the tier's level:** focal point, council member, or full council → (5) **Record** in the inventory and register: vendor, model version, value measure → (6) **Watch:** human-check sampling at the tier's rate, and re-review on any model change.


## Top risks, condensed

The working group's 28 risks fall into seven categories, each with one owner and one lead control.

| Risk category | Risk-map rows | Owner | Lead control |
| --- | --- | --- | --- |
| Not knowing what AI is running | 6, 9, 10, 18 | CIO | Inventory covering embedded AI, staff sign-ups and vendors' AI |
| Company data leaving or overexposed | 15, 23 | CISO | Approved-tools list; permissions fixed before Copilot or search agents go live |
| Agents acting without control | 4, 5, 19, 24 | CIO | Tiering, a named watcher, its own credentials, a tested shutdown |
| Wrong, biased or unaccountable output | 1, 12, 13, 16, 17 | Business owner | Human check sized to tier, logs of prompt and version, approval for public claims |
| Vendor, contract and legal change | 2, 3, 7, 8, 21, 22 | General Counsel | Model-change notice, exit terms, re-review on change |
| Spend without proven value | 11, 14, 25 | CFO | One value measure per system; cost on the quarterly report |
| Workforce and sustainability | 20, 26, 27, 28 | HR | Backup owner per system, skills retained, energy and compute reported |


## Next 90 days

The first week sets up three things: an accountable executive, an inventory, and a published list of approved tools.

| By | Deliverable |
| --- | --- |
| Day 7 | Council chair named; approved-tools list published; inventory started |
| Day 30 | Intake form and data readiness check live; inventory covers embedded AI and staff sign-ups |
| Day 60 | Every system tiered, with an owner; risk register and exception register running |
| Day 90 | First quarterly leadership report: AI in use, value, cost, top risks, open exceptions, decisions needed |

**Asks of leadership:** name the accountable executive, endorse the approved-tools list, and fund AI discovery jointly with Security.
