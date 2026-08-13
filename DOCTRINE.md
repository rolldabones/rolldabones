# DOCTRINE.md

**The rolldabones doctrine canon · v1.0.0 · 13 August 2026 (KST)**

**Destination: rolldabones/rolldabones (profile repository), beside [ECOSYSTEM.md](ECOSYSTEM.md). This file is the single normative statement of the three doctrines. [ECOSYSTEM.md](ECOSYSTEM.md) keeps its one-paragraph summary and points here. Every other repository uses these definitions exactly as stated and adds instruments, not doctrine.**

Three doctrines run through this account. They are stated here once, in normative form, so that twenty-one repositories do not each drift their own version. Where a repository needs a formulation at a different altitude, board, enterprise or task, it may restate the doctrine in its own register. It may not restate it into a different rule.

---

## 1. Slow AI

**AI that cannot be governed, explained and audited should not be deployed, however fast it would make the business.**

Slow AI is not a speed limit. It is a precondition. The three tests are conjunctive: a system that is explainable but unauditable fails, and so does one that is auditable but ungoverned. "Governed" means a named owner, defined boundaries and a working intervention path. "Explained" means the organization can state why an output was produced in terms the affected person can use. "Audited" means the evidence exists before it is asked for, not after.

The doctrine's operative consequence is that the right to operate follows from being governable. Where a jurisdiction expresses the same idea, it tends to express it as a documentation, retention and explanation duty.

## 2. Informed Intent

**No AI system, and above all no AI agent, acts on the organization's behalf without prior authorization that specifies what it may do, on whose authority, within what boundaries and with what exit.**

Four elements, all required: purpose, authority, boundaries, exit. An authorization missing its exit is not an authorization; it is a hope. Authorization precedes action, and it is specific to the action, not to the technology in general. A general permission to "use AI" authorizes nothing in particular and therefore authorizes nothing.

The agentic case is the hard case and the reason the doctrine is stated at this strength. A system that plans across steps and calls tools will encounter states its authorizer never contemplated. The boundary and the exit are what make that survivable.

## 3. Final Liability rests with the Human

**Every material outcome produced by an AI system attaches to a named human owner with decision rights, oversight and the power to intervene. There is no such thing as an outcome the model is responsible for.**

Note the three attributes. A name alone is not accountability; a person who is named but holds no decision rights, no oversight and no power to intervene is a nominee, and nominating one is worse than naming nobody because it manufactures the appearance of accountability. The doctrine refuses to allow the question of liability to be left open. It does not transfer liability to the system, and it cannot: systems are not liability-bearing entities.

### 3.1 The allocation lifecycle

Accountability has three moments, and confusing them is the most common failure in AI governance drafting.

| Moment | What happens |
|---|---|
| **Named at specification** | The owner is identified before the work begins, as part of the authorization. Naming after the fact is selection of a scapegoat, not allocation of accountability |
| **Attaches at confirmation** | Accountability binds when the named human confirms the output against criteria defined in advance. Confirmation has three lawful outcomes: confirm, refuse, or amend and confirm, each with a record. There is no fourth |
| **Holds through reliance** | It does not end at confirmation. It persists for as long as the organization or a third party relies on the output, which is usually far longer than the project that produced it |

The lifecycle is why "who approved this" is the wrong first question after a failure. The right sequence is: who was named, on what specification, what did they confirm, against what criteria, and who has been relying on it since.

### 3.2 The drafting rule

**Reserve liability language for where legal liability genuinely lands.**

Governance documents routinely say that a control "discharges", "satisfies" or "transfers" an obligation. Almost always this is false, and the falsity is load-bearing: it lets an organization believe a duty has moved when it has not. A control advances compliance. It reduces what remains to be done. It does not transfer the duty and it does not end it, because obligations are discharged only by the person on whom they fall, on the terms the instrument sets.

Applied to drafting, the rule produces three habits:

1. Use "advances", "supports" or "evidences" where that is what a control does. Reserve "discharges" for the case where the instrument itself says the obligation is thereby met.
2. Never write that responsibility is "shared" without saying how it is divided and what happens when the division is contested.
3. Never write that a vendor "assumes" a duty owed by the organization to a regulator. Vendors can assume contractual risk between the parties. They cannot assume a public-law duty.

### 3.3 Statutory analogues

The doctrine is the author's, but it is not idiosyncratic. Two instruments now express parts of it in operative regulatory language.

**Colorado.** *[Binding law. Pinpoint: C.R.S. 6-1-1707. As at 13 August 2026 (KST).]* Liability between developer and deployer is allocated on **relative fault**. The statute creates **no joint and several liability**. And at **6-1-1707(7)(a)**, an indemnification provision between developer and deployer purporting to cover that party's **own** acts or omissions under Colorado anti-discrimination law is **void as contrary to public policy**.

That third limb is the drafting rule in statute. Colorado has decided that a contract cannot move a party's own discrimination exposure onto its counterparty, whatever the parties write. An organization that believed its vendor indemnity covered the thing it most feared would discover, at the worst moment, that the clause was void. Reserving liability language for where liability genuinely lands is not stylistic fastidiousness; it is the difference between an enforceable allocation and an unenforceable one.

**Vietnam.** *[Binding law. Pinpoint: Decision No. 33/2026/QD-TTg. As at 13 August 2026 (KST).]* The Decision provides that the use of an AI system **does not change, transfer or exclude the authority and responsibility of the competent body, organization or individual**.

That is Final Liability stated as a rule of administrative law. Deploying the system moves no liability off the person who already held it. Note what the drafter did: rather than create a new accountability regime for AI, the provision denies that AI disturbs the existing one. That is the more durable construction, and it is worth borrowing.

---

## 4. Relations between the three

The doctrines are sequential, not parallel.

**Informed Intent** governs entry: nothing acts without authorization. **Slow AI** governs the condition of the thing authorized: it must be governable, explainable and auditable, or the authorization should not issue. **Final Liability** governs the whole span: a named human with decision rights holds accountability from specification, through confirmation, for as long as anyone relies on the output.

A failure in any one collapses the others. An unauthorized system has no named owner because there was no specification to name one in. An unauditable system cannot support confirmation, because there is nothing to confirm against. And where no human holds decision rights, the authorization was to nobody.

---

## 5. Use of this file

1. This file is the only normative statement of the three doctrines in this account. Repositories link here rather than redefining.
2. Repositories add **instruments**, not doctrine. A repository may introduce a template, a checklist, a scoring method or a worked example that operationalizes a doctrine. It may not introduce a variant definition.
3. Altitude restatement is permitted; rule variation is not. Board, enterprise and task registers of the same doctrine must reduce to the same rule.
4. Changes to a doctrine statement are versioned here and logged below, and the change is announced in [ECOSYSTEM.md](ECOSYSTEM.md)'s change log in the same commit series.
5. Where a jurisdiction's law states something close to a doctrine, cite it as an analogue with a pinpoint, an as-at date and a status tag. Do not present the doctrine as law.

## Change log

- v1.0.0 (2026-08-13, KST): first issue. Consolidates the three doctrine statements previously restated across repositories; adds the allocation lifecycle, the drafting rule and the Colorado and Vietnam statutory analogues.

---

**Final Liability rests with the Human.**
