# ECOSYSTEM.md

**The rolldabones governance ecosystem · v1.3.0 · 14 July 2026**

**Destination: rolldabones/rolldabones (profile repository). This is the single canonical map. Every other repository links here from a short "Part of the ecosystem" section rather than duplicating this content. One map, many pointers: duplicated maps drift.**

Everything in this account serves one practice: enterprise AI governance, risk management and compliance that is evidence-led and auditable. Three doctrines run through all of it: **Slow AI** (governed, explainable, auditable, evidence over assurances), **Informed Intent** (no deployment without explicit pre-authorization specifying purpose, scope, limits and a named owner) and **Final Liability rests with the Human** (every outcome attaches to a named human with decision rights, oversight and the power to intervene). The **GRC next** framework supplies the operating primitives: Services, Tolerances, Pipes, Switches, Exits.

## Layer 1: Doctrine and method

| Repository | Role in the set |
|---|---|
| [grc](https://github.com/rolldabones/grc) | The foundation: the GRC next framework on the OCEG Capability Model spine, with the Governance Test and the five primitives the tools below implement |
| [grc-workbook](https://github.com/rolldabones/grc-workbook) | The workbook: a module-by-module instrument for building, augmenting and auditing an integrated GRC capability on the OCEG model, with the three doctrines applied in Part II |
| [slow-ai-kitchen](https://github.com/rolldabones/slow-ai-kitchen) | The method: a 12-step governed AI methodology from individual task discipline to institutional program governance |
| [origami-method](https://github.com/rolldabones/origami-method) | The workflow discipline: a stage-gated method for designing repeatable, safe AI workflows through creases, gates and folds, delivered as the Origami Workflow Guide custom GPT |
| [final-liability-rests-with-the-human-book-wip](https://github.com/rolldabones/final-liability-rests-with-the-human-book-wip) | The argument: the book manuscript developing the Final Liability doctrine |

## Layer 2: Assessment and decision tools

| Repository | Role in the set |
|---|---|
| [AI-Impact-Assessment-Tool](https://github.com/rolldabones/AI-Impact-Assessment-Tool) | Pre-deployment and lifecycle impact assessment aligned to the EU AI Act, NIST AI RMF, ISO/IEC 42001 and ISO/IEC 42005; the Informed Intent gate in tool form |
| [risk-informed-decision-making-prompt](https://github.com/rolldabones/risk-informed-decision-making-prompt) | Continuous risk-informed decision making under uncertainty; auditable work product |
| [RedCap-00](https://github.com/rolldabones/RedCap-00) | Operational-optionality self-check: can the organization execute five critical moves within 72 hours under disruption; evidence-capped, conservative scoring |
| [RedCap-01](https://github.com/rolldabones/RedCap-01) | Objective-to-Risk Alignment Check: an evidence-oriented diagnostic testing whether ERM improves the decisions that determine objective achievement (informed by COSO's 2026 *From Guidance to Action*) |
| [master-prompt-for-in-house-legal-and-compliance](https://github.com/rolldabones/master-prompt-for-in-house-legal-and-compliance) | The general-purpose in-house legal and compliance workbench |

## Layer 3: Audience-specific guidance

| Repository | Role in the set |
|---|---|
| [ai-governance-for-boards](https://github.com/rolldabones/ai-governance-for-boards) | Board mandate, best practices and jurisdiction guides (EU, US, Korea, Vietnam, Australia); where the assessment tools send their "verify with counsel" flags |
| [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy) | Prompt template pack for client-facing governance engagements |
| [claude-cowork-legal-onboarding](https://github.com/rolldabones/claude-cowork-legal-onboarding) | Onboarding and guardrails for legal workflows on an agentic platform |
| [the-ai-generalist](https://github.com/rolldabones/the-ai-generalist) | One-day corporate workshop: LLM foundations, a repeatable prompting workflow, a tool selection map and the AI GRC minimum control set, with the three doctrines applied to real corporate use cases |

## Layer 4: Field studies

| Repository | Role in the set |
|---|---|
| [the-ungoverned-channel](https://github.com/rolldabones/the-ungoverned-channel) | A living case study of agentic AI in multiplayer workflows: the risks the assessment tools exist to catch, observed in the wild |

## How the layers connect

Doctrine (Layer 1) defines what governed means. The Origami Method turns that definition into workflow-design discipline: its creases are Tolerances on inputs and outputs, its gates are Switches and its fold log is controlled change under audit. The assessment tools (Layer 2) operationalize it at the decision point: the AI Impact Assessment Tool's kill-switch requirement is a GRC next Switch, its decommission plan an Exit, its data flow narrative a Pipe, its thresholds Tolerances, its system inventory a Service. RedCap-01's decision boundaries are Tolerances made usable and its trigger-to-action links are Switches; RedCap-00 tests whether the Exits and Switches actually fire under stress. The guidance repositories (Layer 3) carry the same doctrines to boards, clients and practitioners; the AI Generalist workshop is the widest on-ramp, teaching the minimum control set to working professionals in a day. The field studies (Layer 4) test the doctrines against live systems and feed corrections back into the tools.

## Maintenance protocol

1. This file is the only canonical map. Repositories link to it; they do not copy it.
2. When a repository is added, renamed or retired, update this file in the same commit series and log the change below.
3. Each repository carries the standard "Part of the ecosystem" section (see the snippet in any current repository README) listing this map plus up to five nearest neighbors.
4. Repositories not yet listed here are pending classification. Add them to a layer on their next substantive revision.

## Change log

- v1.3.0 (2026-07-14): added origami-method (Layer 1); fifteen repositories classified; layer-connection paragraph extended to the workflow-design discipline.
- v1.2.0 (2026-07-14): added the-ai-generalist (Layer 3); fourteen repositories classified; layer-connection paragraph extended to the workshop on-ramp.
- v1.1.0 (2026-07-14): added grc-workbook (Layer 1), RedCap-00 and RedCap-01 (Layer 2); thirteen repositories classified; layer-connection paragraph extended to the RedCap tools.
- v1.0.0 (2026-07-13): initial map, ten repositories classified across four layers.

Final Liability rests with the Human.
