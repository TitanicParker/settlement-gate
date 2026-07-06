# Settlement Gate Roadmap

<p><strong>Status:</strong> early-stage investigation. This roadmap is for controlled development, not public proof.</p>

<details open>
<summary><strong>Current objective</strong></summary>

Prepare Settlement Gate for a safe first external conversation: protect the idea, identify trusted reviewers, and define the smallest credible validation path.

</details>

---

## Phase 0 — Organise the working packet

**Goal:** make the material navigable without changing the underlying claim.

- Preserve the full packet as the canonical source.
- Separate presentation, demo sentences, A-packets, resolver outputs, validation, and product notes.
- Keep the Anthony / PorterShed presentation focused on the ask, not on proving the entire system.

**Repo areas:**

```text
00_packet/
01_presentation/
02_demo_sentences/
03_a_packets/
04_resolver_outputs/
```

**Done when:** the repository can be opened by a reviewer and the core materials are easy to locate.

---

## Phase 1 — Prepare the Anthony / PorterShed meeting

**Goal:** turn the packet into a 30-minute founder-originator conversation.

- Use 17 slides total.
- Slide 0 and Slide 16 carry the ask.
- Slides 1–15 each carry one soundbite.
- Use a few examples only: dog completion, door state/event, A-packet, conditional permission, bilingual English–Irish pairs.
- Avoid deep explanation of the full 54-cell lattice.

**Repo area:**

```text
01_presentation/
```

**Done when:** the speaker can present directly from the slide plan and teleprompter without overexposing the mechanism.

---

## Phase 2 — Define first validation tests

**Goal:** make the claim testable without pretending it is already proven.

- Build a reviewer protocol for source sentences.
- Build a blind A-packet-to-resolver test.
- Test whether independent reviewers recover the same address.
- Test whether translation pairs preserve structural landing.
- Record disagreements instead of smoothing them away.

**Repo area:**

```text
05_validation/
```

**Done when:** there is a repeatable validation protocol that a trusted reviewer can follow.

---

## Phase 3 — Identify first commercial wedge

**Goal:** choose the smallest market-facing version of the idea.

Candidate wedges:

1. **AI output audit** — check whether an AI sentence is entitled to settle what it claims.
2. **Translation validation** — check whether a translation preserves structural address.
3. **Agent instruction safety** — prevent agents from acting on unsupported or misread settlements.
4. **Legal / policy review** — inspect high-stakes sentences for hidden commitments and rival readings.

**Repo area:**

```text
06_product/
```

**Done when:** one narrow product hypothesis is selected for validation.

---

## Phase 4 — Controlled external review

**Goal:** expose the idea to the right people in the right order.

Useful first reviewers:

- IP advisor.
- Trusted AI / NLP reviewer.
- Translation expert.
- Product builder.
- Commercialisation mentor.
- University or research contact.

**Repo area:**

```text
07_private/
```

**Done when:** a small, controlled review group has been identified and the exposure log is maintained.

---

## Phase 5 — Prototype the receipt layer

**Goal:** move from packet to tool concept.

- Define a sentence receipt schema.
- Convert selected examples into receipt objects.
- Test proceed / revise / escalate / block decisions.
- Compare human review with model-generated receipts.

**Repo areas:**

```text
05_validation/
06_product/
```

**Done when:** a basic demo can show a sentence entering a gate and leaving with a receipt.
