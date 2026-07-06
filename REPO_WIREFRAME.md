# Settlement Gate Repository Wireframe

Use this as the extraction map when unpacking `settlement-gate.zip` into the GitHub repository.

The goal is that every file from the zip has an obvious destination, and the repository remains readable to Anthony, a technical reviewer, an IP advisor, or a future product collaborator.

> Important: the repository is currently public. Keep sensitive material out of public folders until IP and disclosure strategy are settled.

---

## Root level

```text
settlement-gate/
├── README.md
├── REPO_WIREFRAME.md
├── LICENSE.md
├── .gitignore
├── 00_packet/
├── 01_presentation/
├── 02_demo_sentences/
├── 03_a_packets/
├── 04_resolver_outputs/
├── 05_validation/
├── 06_product/
└── 07_private/
```

### Root file targets

| Source from zip | Destination | Purpose |
|---|---|---|
| `README.md` | `README.md` | Public-facing repository overview. |
| `LICENSE.md` | `LICENSE.md` | All-rights-reserved placeholder until formal licensing is decided. |
| `.gitignore` | `.gitignore` | Ignore OS, Python, environment, log, and zip files. |

---

## `00_packet/` — Full source packet

```text
00_packet/
├── Settlement_Gate_Collated_Working_Packet_FULL_SCRIPT.md
└── packet_summary.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| Full original Markdown packet | `00_packet/Settlement_Gate_Collated_Working_Packet_FULL_SCRIPT.md` | Canonical source file. Preserve unchanged. |
| `packet_summary.md` | `00_packet/packet_summary.md` | Short readable summary of the full packet. |

Use this folder for the source-of-truth packet and summaries only.

---

## `01_presentation/` — Anthony / PorterShed presentation

```text
01_presentation/
├── slide_plan.md
├── teleprompter_script.md
├── anthony_portershed_ask.md
└── design_notes.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `slide_plan.md` | `01_presentation/slide_plan.md` | 17-slide structure: Slide 0, Slides 1–15, Slide 16. |
| `teleprompter_script.md` | `01_presentation/teleprompter_script.md` | Slide-by-slide spoken script. |
| `anthony_portershed_ask.md` | `01_presentation/anthony_portershed_ask.md` | Standalone ask document for Anthony and PorterShed. |
| `design_notes.md` | `01_presentation/design_notes.md` | Minimal slide design guidance. |

Use this folder for material that supports the 30-minute conversation.

---

## `02_demo_sentences/` — Demo sentence material

```text
02_demo_sentences/
├── galway_portershed_english.md
├── galway_portershed_irish.md
├── bilingual_pairs.csv
└── dog_completion_examples.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `galway_portershed_english.md` | `02_demo_sentences/galway_portershed_english.md` | English Galway / PorterShed demo sentences. |
| `galway_portershed_irish.md` | `02_demo_sentences/galway_portershed_irish.md` | Irish demo sentences. |
| `bilingual_pairs.csv` | `02_demo_sentences/bilingual_pairs.csv` | English–Irish matching pairs and shared landings. |
| `dog_completion_examples.md` | `02_demo_sentences/dog_completion_examples.md` | Two key examples: failure to close and going past closure. |

Use this folder for examples that can be shown without exposing all machinery.

---

## `03_a_packets/` — A1–A6 inspection packets

```text
03_a_packets/
├── sentence_zero_transport_plan.md
├── a_packets_01_20.md
├── a_packets_horizontal_table.csv
└── templates/
    └── a_packet_template.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `sentence_zero_transport_plan.md` | `03_a_packets/sentence_zero_transport_plan.md` | The clean introductory A-packet example. |
| `a_packets_01_20.md` | `03_a_packets/a_packets_01_20.md` | Vertical A-packets for all 20 demo sentences. |
| `a_packets_horizontal_table.csv` | `03_a_packets/a_packets_horizontal_table.csv` | CSV version of the horizontal A1–A6 comparison table. |
| `a_packet_template.md` | `03_a_packets/templates/a_packet_template.md` | Reusable template for future sentence testing. |

Use this folder for the inspection instrument, not for product claims.

---

## `04_resolver_outputs/` — Addresses and validation tables

```text
04_resolver_outputs/
├── resolver_results_01_20.md
├── compact_cell_ledger.csv
├── threefold_address_validation.md
└── validation_summary_table.csv
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `resolver_results_01_20.md` | `04_resolver_outputs/resolver_results_01_20.md` | Resolver output table and explanation. |
| `compact_cell_ledger.csv` | `04_resolver_outputs/compact_cell_ledger.csv` | Compact list of chosen cells for all 20 sentences. |
| `threefold_address_validation.md` | `04_resolver_outputs/threefold_address_validation.md` | Full Remainder / Orientation / Operator validation section. |
| `validation_summary_table.csv` | `04_resolver_outputs/validation_summary_table.csv` | CSV summary of address claims. |

Use this folder for produced outputs from the current packet, not for independent validation results.

---

## `05_validation/` — Future independent testing

```text
05_validation/
├── README.md
├── reviewer_protocol.md
├── translation_tests/
│   ├── english_irish_round_01.md
│   └── future_language_pairs.md
├── ai_audit_tests/
│   ├── refund_approval_examples.md
│   ├── conditional_permission_examples.md
│   └── agent_instruction_examples.md
└── results/
    └── placeholder.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `README.md` | `05_validation/README.md` | Explains future validation folder. |
| `reviewer_protocol.md` | `05_validation/reviewer_protocol.md` | Draft procedure for human/model review. |
| `english_irish_round_01.md` | `05_validation/translation_tests/english_irish_round_01.md` | Local bilingual pressure test from packet. |
| `future_language_pairs.md` | `05_validation/translation_tests/future_language_pairs.md` | Placeholder for additional languages. |
| `refund_approval_examples.md` | `05_validation/ai_audit_tests/refund_approval_examples.md` | Future AI-audit example around approved refund status. |
| `conditional_permission_examples.md` | `05_validation/ai_audit_tests/conditional_permission_examples.md` | Ferry / ticket-inspection conditional permission example. |
| `agent_instruction_examples.md` | `05_validation/ai_audit_tests/agent_instruction_examples.md` | Placeholder for future agent instruction tests. |
| `placeholder.md` | `05_validation/results/placeholder.md` | States that no independent validation results are added yet. |

Use this folder to separate future validation from the current working packet.

---

## `06_product/` — Commercial and product framing

```text
06_product/
├── product_hypotheses.md
├── use_cases.md
├── sentence_receipt_schema.md
└── commercial_questions.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `product_hypotheses.md` | `06_product/product_hypotheses.md` | Candidate commercial hypotheses. |
| `use_cases.md` | `06_product/use_cases.md` | Possible application areas. |
| `sentence_receipt_schema.md` | `06_product/sentence_receipt_schema.md` | Early draft schema for a sentence receipt. |
| `commercial_questions.md` | `06_product/commercial_questions.md` | Questions for IP, validation, product, and go-to-market. |

Use this folder for commercial thinking. Keep claims framed as hypotheses.

---

## `07_private/` — Sensitive notes

```text
07_private/
├── ip_notes_DO_NOT_SHARE.md
├── advisor_questions.md
└── exposure_log.md
```

| Source from zip | Destination | Purpose |
|---|---|---|
| `ip_notes_DO_NOT_SHARE.md` | `07_private/ip_notes_DO_NOT_SHARE.md` | Placeholder for IP questions and protection notes. |
| `advisor_questions.md` | `07_private/advisor_questions.md` | Questions for IP, AI/NLP, translation, product, commercialisation, funders, and university contacts. |
| `exposure_log.md` | `07_private/exposure_log.md` | Log of who has seen what, when, and under what protection. |

Strong recommendation: do not upload this folder to a public repository unless it contains only harmless placeholders.

---

## Upload order

Recommended order when extracting the zip:

1. Upload root files: `README.md`, `LICENSE.md`, `.gitignore`.
2. Upload `00_packet/` only if you are comfortable storing the full packet in this repository.
3. Upload `01_presentation/` for the Anthony / PorterShed conversation.
4. Upload `02_demo_sentences/` for public-safe examples.
5. Upload `03_a_packets/` and `04_resolver_outputs/` only after deciding what level of mechanism exposure is acceptable.
6. Upload `05_validation/` to prepare future testing.
7. Upload `06_product/` for commercial framing.
8. Keep `07_private/` local or private unless cleared.

---

## Quick check after upload

After uploading, the repository should show:

```text
README.md
REPO_WIREFRAME.md
LICENSE.md
.gitignore
00_packet/
01_presentation/
02_demo_sentences/
03_a_packets/
04_resolver_outputs/
05_validation/
06_product/
07_private/
```

If those appear, the zip has been extracted into the intended shape.
