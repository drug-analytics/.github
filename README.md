# Drug Analytics

**Pharmaceutical lifecycle intelligence built on public FDA data.**

We turn the FDA's public drug records into a connected view of market protection — so the
teams deciding where to invest can see when protection ends, who else is in the field, and
what changed since their last review.

---

## The problem

The data that determines when a generic can enter a market is public. It is also,
practically speaking, unusable.

Patents, exclusivities, approvals, and applications arrive as separate flat files on
separate schedules, keyed inconsistently, with no stable link between a product, the
molecule inside it, the application that approved it, and the company that owns it.
So teams rebuild the same map by hand, every cycle:

- **Nothing is connected.** A drug, its active ingredient, its FDA application, its patents, its exclusivities, and the company behind it live in different records with no reliable join. Building a portfolio-level view is manual reconciliation work before it is analysis.
- **Timelines are buried.** Whether a protection actually blocks entry — and when it lifts — is a reading exercise across dense patent and regulatory text, not a date you can look up.
- **Change is invisible.** Meaningful events (a patent added or removed, a term changed, a first-filer signal, a discontinuation) land inside routine monthly data maintenance and are easy to miss entirely.
- **Prioritization has no common basis.** Going from a long list of molecules to a defensible shortlist means combining timing, competitive field, company exposure, and regulatory milestones — usually in a spreadsheet that only its author trusts.

The cost isn't that the answers are unknowable. It's that every team pays to derive them
again, slowly, and can't easily show their work.

---

## What we're building

| # | Focus | What it means |
|---|---|---|
| 01 | **A connected pharmaceutical data model** | Drugs, active ingredients, FDA applications, companies, patents, and exclusivities as one navigable, entity-linked system — consistent product identities, portfolio-level context. |
| 02 | **Understandable protection timelines** | Patent and regulatory records rendered as timelines: which protections matter, when they expire, where uncertainty still exists, and what the realistic next-entry date looks like. |
| 03 | **Early detection of meaningful change** | Successive data releases compared automatically, elevating additions, removals, term changes, first-filer signals, and discontinuations instead of letting them pass as noise. |
| 04 | **Better portfolio prioritization** | Reusable screeners, curated opportunity lists, and comparable decision criteria — so a shortlist can be defended, not just asserted. |
| 05 | **A broader lifecycle layer** | Extending past Orange Book events toward approvals, clinical development, IP, and commercial signals evaluated as a single lifecycle. |

---

## Who it's for

**Generic portfolio & business development teams**
Prioritize opportunities and decide where deeper technical, regulatory, and commercial
diligence is justified. *Which products are approaching an entry window? Where is the
competitive field still manageable? What changed since the last review?*

**IP, regulatory & market-access teams**
Track expiries, exclusivity windows, and next-entry dates against sources that can be
chased back to the original record.

**Pharma investors & strategy teams**
Monitor patent cliffs and market entry windows across a coverage universe without
maintaining the plumbing.

---

## How we think about it

**Traceable over mysterious.** Every date and every number should be chaseable back to the
FDA record it came from. An answer you can't audit isn't an answer you can act on.

**Actionable over exhaustive.** A decision-shaped result beats a complete data dump. We'd
rather surface the five things that changed and matter than all four thousand that changed.

**The pipeline is the product.** Public data is only as good as the discipline behind
ingesting it — reconciled on every run, versioned per release, so history stays comparable.

---

## Get in touch

<!-- Replace with your public contact route before publishing. -->
Interested in the platform, or in the data model behind it? Reach us at https://druganalytics.vercel.app/contact.

---
