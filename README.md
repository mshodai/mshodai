# mshodai

Architecture and tooling for systems that have to answer to a supervisor.

---

Most software in regulated domains fails the same way: compliance is treated as
a review gate at the end instead of a constraint at the start. Everything here
assumes the opposite — traceability, evidence and explainability as structural
decisions, made on day one, testable.

### Working ground

Client onboarding and due diligence · document lifecycle and lineage ·
counterparty matching · automated financial reporting · AI governance

`EU AI Act` · `ISO/IEC 42001` · `DORA` · `AMLD` · `MiFID II` · `PSD2/PSD3` · `GDPR`

### Tools

`Python` · `FastAPI` · `PostgreSQL` · `Odoo` · `React` · `Typst`
LLM orchestration · structured extraction · deterministic rule engines ·
evaluation and audit logging

### Method

- **Verify before asserting.** A claim about a system comes with the file and the
  line it came from, or it is labelled a hypothesis. A comment is text about the
  code, not the code.
- **Adversarial validation.** Decisions go through multi-model review — thesis,
  antitheses, synthesis — before they are locked in. Fluent agreement is a risk
  signal, not a result.
- **ADRs by default.** Context, decision, consequences. Written when the decision
  is made, not reconstructed afterwards.
- **One change, one check.** If an approach fails three times, the approach is
  the problem.

### The interesting part

The probabilistic component of a system is the part you have to justify. Most of
the design work is deciding what a model is allowed to decide, what stays
deterministic, and how every output is logged so someone can reconstruct it two
years later without asking anyone.

### Before this

Two decades founding and running companies before building systems for
them. Hardware and software R&D, cross-border manufacturing, and several
years on the buy side: investment analysis, due diligence, deal work.

I have raised institutional capital, which means I have been the one
audited rather than the one building for auditors. Most of what I design
now, I once had to do by hand.

---

Reference implementations on synthetic data. Notes. Tools I needed and had to
build. Nothing here comes from anyone's production.
