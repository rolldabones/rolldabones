# ECOSYSTEM.md

**The rolldabones governance ecosystem · v1.7.1 · 16 July 2026**

**Destination: rolldabones/rolldabones (profile repository). This is the single canonical map. Every other repository links here from a short "Part of the ecosystem" section rather than duplicating this content. One map, many pointers: duplicated maps drift.**

Everything in this account serves one practice: enterprise AI governance, risk management and compliance that is evidence-led and auditable. Three doctrines run through all of it: **Slow AI** (governed, explainable, auditable, evidence over assurances), **Informed Intent** (no deployment without explicit pre-authorization specifying purpose, scope, limits and a named owner) and **Final Liability rests with the Human** (every outcome attaches to a named human with decision rights, oversight and the power to intervene). The **GRC next** framework supplies the operating primitives: Services, Tolerances, Pipes, Switches, Exits.

## Layer 1: Doctrine and method

| Repository | Role in the set |
|---|---|
| [grc](https://github.com/rolldabones/grc) | The foundation: the working method on the OCEG GRC Capability Model 3.5 spine (Principled Performance, the operating cycle, the 20 elements), with four build guides, a 21-prompt pack and six operating templates |
| [grc-workbook](https://github.com/rolldabones/grc-workbook) | The workbook: a module-by-module instrument for building, augmenting and auditing an integrated GRC capability on the OCEG model, with the three doctrines applied in Part II |
| [slow-ai-kitchen](https://github.com/rolldabones/slow-ai-kitchen) | The method: a 12-step governed AI methodology from individual task discipline to institutional program governance |
| [definition-of-done](https://github.com/rolldabones/definition-of-done) | The acceptance doctrine: how done is defined before work begins and confirmed before reliance, the depth work inside the Kitchen's Gates 1, 6 and 7 |
| [origami-method](https://github.com/rolldabones/origami-method) | The workflow discipline: a stage-gated method for designing repeatable, safe AI workflows through creases, gates and folds, delivered as the Origami Workflow Guide custom GPT |
| [final-liability-rests-with-the-human-book-wip](https://github.com/rolldabones/final-liability-rests-with-the-human-book-wip) | The argument: the book manuscript developing the Final Liability doctrine |
| [computational-drafting](https://github.com/rolldabones/computational-drafting) | The drafting layer: the design of specifications that translate human and institutional intent into behavior across legal, organizational and technical interpreters, with the eight-element anatomy, the interpreter map, the hostile-case checklist, three templates and a worked example |

## Layer 2: Assessment and decision tools

| Repository | Role in the set |
|---|---|
| [AI-Impact-Assessment-Tool](https://github.com/rolldabones/AI-Impact-Assessment-Tool) | Pre-deployment and lifecycle impact assessment aligned to the EU AI Act, NIST AI RMF, ISO/IEC 42001 and ISO/IEC 42005; the Informed Intent gate in tool form |
| [risk-informed-decision-making-prompt](https://github.com/rolldabones/risk-informed-decision-making-prompt) | Continuous risk-informed decision making under uncertainty; auditable work product |
| [RedCap-00](https://github.com/rolldabones/RedCap-00) | Operational-optionality self-check: can the organization execute five critical moves within 72 hours under disruption; evidence-capped, conservative scoring |
| [RedCap-01](https://github.com/rolldabones/RedCap-01) | Objective-to-Risk Alignment Check: an evidence-oriented diagnostic testing whether ERM improves the decisions that determine objective achievement (informed by COSO's 2026 *From Guidance to Action*) |
| [master-prompt-for-in-house-legal-and-compliance](https://github.com/rolldabones/master-prompt-for-in-house-legal-and-compliance) | The general-purpose in-house legal and compliance workbench |
| [AI-GRC-Copilot](https://github.com/rolldabones/AI-GRC-Copilot) | The artifact factory: production mirror of the AI GRC Spellbook Copilot custom GPT, which drafts the 30 canonical AI GRC artifacts with owners, evidence and systems of record |
| [AI-GRC-Master-List-of-Questions](https://github.com/rolldabones/AI-GRC-Master-List-of-Questions) | The minimum input set (17 sections, mostly yes/no) that, once answered, lets the Spellbook Copilot draft all 30 artifacts; pairs with AI-GRC-Copilot |
| [GRCnext-Copilot](https://github.com/rolldabones/GRCnext-Copilot) | The optionality assessor: evidence-led scoring of Global Optionality across critical services (Pipes, Switches, Exits), with the v2 methodology, advisory tools suite, schemas and tests |
| [Contract-Mechanism-Review-Assistant](https://github.com/rolldabones/Contract-Mechanism-Review-Assistant) | The contract specialist: a mode-gated review assistant treating contracts as risk-transfer mechanisms and executable business plans, with evidence anchors and an uncertainty register |

## Layer 3: Audience-specific guidance

| Repository | Role in the set |
|---|---|
| [ai-governance-for-boards](https://github.com/rolldabones/ai-governance-for-boards) | Board mandate, best practices and jurisdiction guides (EU, US, Korea, Vietnam, Australia); where the assessment tools send their "verify with counsel" flags |
| [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy) | Prompt template pack for client-facing governance engagements, with client-facing publications |
| [the-ai-generalist](https://github.com/rolldabones/the-ai-generalist) | One-day corporate workshop: LLM foundations, a repeatable prompting workflow, a tool selection map and the AI GRC minimum control set, with the three doctrines applied to real corporate use cases |

## Layer 4: Field studies

| Repository | Role in the set |
|---|---|
| [the-ungoverned-channel](https://github.com/rolldabones/the-ungoverned-channel) | A living case study of agentic AI in multiplayer workflows: the risks the assessment tools exist to catch, observed in the wild |

## How the layers connect

Doctrine (Layer 1) defines what governed means. The Origami Method turns that definition into workflow-design discipline: its creases are Tolerances on inputs and outputs, its gates are Switches and its fold log is controlled change under audit. The assessment tools (Layer 2) operationalize it at the decision point: the AI Impact Assessment Tool's kill-switch requirement is a GRC next Switch, its decommission plan an Exit, its data flow narrative a Pipe, its thresholds Tolerances, its system inventory a Service. RedCap-01's decision boundaries are Tolerances made usable and its trigger-to-action links are Switches; RedCap-00 tests whether the Exits and Switches actually fire under stress. The AI GRC Copilot pair turns the doctrine into paperwork that proves itself: the Master List of Questions captures the organization's facts once and the Spellbook Copilot converts them into the 30 artifacts whose owners, evidence and systems of record the Governance Test demands. GRCnext-Copilot is the primitives run as an engine, scoring whether Pipes, Switches and Exits would actually execute within tolerance, and the Contract Mechanism Review Assistant reads the agreements those Exits depend on. The Definition of Done doctrine closes the loop from Layer 1: no tool's output is accepted until a named Human confirms it against tests defined before the work began. Computational drafting supplies the specification layer beneath the whole chain: the eight-element artifact that Informed Intent authorizes, the Origami Method folds into workflow, the Kitchen operates, the assessment tools interrogate and the Definition of Done accepts. The guidance repositories (Layer 3) carry the same doctrines to boards, clients and practitioners; the AI Generalist workshop is the widest on-ramp, teaching the minimum control set to working professionals in a day. The field studies (Layer 4) test the doctrines against live systems and feed corrections back into the tools.

## Maintenance protocol

1. This file is the only canonical map. Repositories link to it; they do not copy it.
2. When a repository is added, renamed or retired, update this file in the same commit series and log the change below.
3. Each repository carries the standard "Part of the ecosystem" section (see the snippet in any current repository README) listing this map plus up to five nearest neighbors.
4. Repositories not yet listed here are pending classification. Add them to a layer on their next substantive revision.

## Change log

- v1.7.1 (2026-07-16): description correction: the computational-drafting line reflects the third template (the operator card) added in that repository's v1.1.0. No layer changes; twenty repositories classified.
- v1.7.0 (2026-07-15): added computational-drafting (Layer 1); twenty repositories classified; layer-connection paragraph extended to the specification layer.
- v1.6.0 (2026-07-15): removed claude-cowork-legal-onboarding from Layer 3 (repository retired and deleted by the maintainer, per maintenance protocol item 2); nineteen repositories classified.
- v1.5.1 (2026-07-15): description corrections against live content. The grc line no longer attributes the Governance Test (which lives in grc-workbook) or the five primitives (which live in GRCnext-Copilot) to the grc repository; the AI-Governance-Academy line now covers its client-facing publications alongside the prompt pack. No layer changes; twenty repositories classified.
- v1.5.0 (2026-07-15): added definition-of-done (Layer 1), GRCnext-Copilot and Contract-Mechanism-Review-Assistant (Layer 2); twenty repositories classified; layer-connection paragraph extended to the optionality engine, the contract specialist and the acceptance loop.
- v1.4.0 (2026-07-15): added AI-GRC-Copilot and AI-GRC-Master-List-of-Questions as a pair (Layer 2); seventeen repositories classified; layer-connection paragraph extended to the artifact factory.
- v1.3.0 (2026-07-14): added origami-method (Layer 1); fifteen repositories classified; layer-connection paragraph extended to the workflow-design discipline.
- v1.2.0 (2026-07-14): added the-ai-generalist (Layer 3); fourteen repositories classified; layer-connection paragraph extended to the workshop on-ramp.
- v1.1.0 (2026-07-14): added grc-workbook (Layer 1), RedCap-00 and RedCap-01 (Layer 2); thirteen repositories classified; layer-connection paragraph extended to the RedCap tools.
- v1.0.0 (2026-07-13): initial map, ten repositories classified across four layers.

Final Liability rests with the Human.
