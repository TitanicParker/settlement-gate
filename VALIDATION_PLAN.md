# Validation Plan

<p><strong>Purpose:</strong> turn Settlement Gate from a working packet into a testable investigation.</p>

<details open>
<summary><strong>Validation posture</strong></summary>

This plan does not assume the system is proven. It defines ways to test whether the A-packet, resolver, and address claims are reproducible, useful, and commercially meaningful.

</details>

---

## Validation questions

1. Can different reviewers produce similar A-packets for the same sentence?
2. Can a resolver recover the same address from an A-packet without seeing the original sentence?
3. Do faithful translations preserve structural landing?
4. Do disagreements reveal useful rival readings rather than mere failure?
5. Can sentence receipts help prevent AI or agentic misreadings?

---

## Test 1 — Source sentence A-packet reproducibility

**Aim:** test whether multiple reviewers can produce comparable A1–A6 packets.

**Method:**

1. Give reviewers the same source sentence.
2. Ask each reviewer to complete A1–A6 independently.
3. Compare the packets for alignment.
4. Record agreement, disagreement, and ambiguous points.

**Success signal:** reviewers may phrase fields differently but identify the same governed object, settlement work, range, shape, and excluded rival.

---

## Test 2 — Blind resolver test

**Aim:** test whether the A-packet contains enough structural information for independent address recovery.

**Method:**

1. Reviewer A receives the sentence and builds A1–A6.
2. Reviewer B receives only the A-packet, not the original sentence.
3. Reviewer B assigns Remainder / Orientation / Operator.
4. Compare with the expected or prior address.
5. Record reasons for mismatch.

**Success signal:** the resolver can recover the intended address from the packet alone often enough to justify deeper testing.

---

## Test 3 — Translation address preservation

**Aim:** test whether faithful translations preserve structural landing.

**Method:**

1. Select source sentence and translation.
2. Build A-packets independently for each language.
3. Resolve both packets into addresses.
4. Compare addresses.
5. Use a native or expert reviewer to assess whether any mismatch is caused by translation shift or analysis error.

**Success signal:** faithful translations tend to preserve address, while unfaithful or shifted translations produce detectable address changes.

---

## Test 4 — AI audit sentence receipts

**Aim:** test whether receipts help identify unsafe or unsupported AI outputs.

**Example sentence:**

> “Your refund has been approved.”

**Audit question:**

Was the sentence entitled to settle approved status?

**Receipt should identify:**

- settled status;
- governed object;
- evidence required;
- rival reading, such as “under review”;
- action permission, such as proceed, request evidence, revise, escalate, or block.

---

## Test 5 — Conditional permission

**Example sentence:**

> “Visitors may board the next ferry after ticket inspection.”

**Audit question:**

Does the system preserve the condition, or does it collapse into unconditional permission?

**Success signal:** the receipt blocks the rival reading that visitors may board immediately without inspection.

---

## Evidence to collect

| Evidence type | Why it matters |
|---|---|
| Reviewer agreement | Tests reproducibility. |
| Reviewer disagreement | Identifies weak points and rival readings. |
| Translation matches | Tests address preservation. |
| Translation mismatches | Shows where meaning or structure shifted. |
| AI audit examples | Tests practical usefulness. |
| Product feedback | Tests commercial value. |

---

## What counts as progress

Progress does not require perfect agreement. Early progress means:

- the method produces inspectable disagreements;
- reviewers understand what is being tested;
- the A-packet prevents obvious surface misreadings;
- translations can be compared structurally;
- at least one product wedge becomes clearer.

---

## What not to claim yet

Do not claim:

- universal proof;
- complete coverage of all sentences;
- final linguistic theory;
- validated commercial product;
- automated reliability without independent testing.

Claim only that Settlement Gate is a structured, testable investigation into sentence landing, recoverable address, translation preservation, and sentence-level auditability.
