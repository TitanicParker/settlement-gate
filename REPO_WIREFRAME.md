# Settlement Gate Repository Wireframe

Use this as the extraction map for the `settlement-gate.zip` package.

The aim is simple: every file from the zip should have an obvious destination, and the repository should remain easy to navigate for Anthony, a technical reviewer, an IP advisor, or a future product collaborator.

---

## Target structure

```text
settlement-gate/
├── README.md
├── REPO_WIREFRAME.md
├── LICENSE.md
├── .gitignore
├── 00_packet/
│   ├── Settlement_Gate_Collated_Working_Packet_FULL_SCRIPT.md
│   └── packet_summary.md
├── 01_presentation/
│   ├── slide_plan.md
│   ├── teleprompter_script.md
│   ├── anthony_portershed_ask.md
│   └── design_notes.md
├── 02_demo_sentences/
│   ├── galway_portershed_english.md
│   ├── galway_portershed_irish.md
│   ├── bilingual_pairs.csv
│   └── dog_completion_examples.md
├── 03_a_packets/
│   ├── sentence_zero_transport_plan.md
│   ├── a_packets_01_20.md
│   ├── a_packets_horizontal_table.csv
│   └── templates/
│       └── a_packet_template.md
├── 04_resolver_outputs/
│   ├── resolver_results_01_20.md
│   ├── compact_cell_ledger.csv
│   ├── threefold_address_validation.md
│   └── validation_summary_table.csv
├── 05_validation/
│   ├── README.md
│   ├── reviewer_protocol.md
│   ├── translation_tests/
│   │   ├── english_irish_round_01.md
│   │   └── future_language_pairs.md
│   ├── ai_audit_tests/
│   │   ├── refund_approval_examples.md
│   │   ├── conditional_permission_examples.md
│   │   └── agent_instruction_examples.md
│   └── results/
│       └── placeholder.md
├── 06_product/
│   ├── product_hypotheses.md
│   ├── use_cases.md
│   ├── sentence_receipt_schema.md
│   └── commercial_questions.md
└── 07_private/
    ├── ip_notes_DO_NOT_SHARE.md
    ├── advisor_questions.md
    └── exposure_log.md
```

---

## Folder purpose

| Folder | Purpose |
|---|---|
| `00_packet/` | Canonical working packet and short summary. |
| `01_presentation/` | Anthony / PorterShed slide plan, script, ask, and design notes. |
| `02_demo_sentences/` | Demo sentences, dog completion examples, and bilingual pairs. |
| `03_a_packets/` | The A1–A6 inspection instrument and sentence packets. |
| `04_resolver_outputs/` | Current resolver outputs, address validations, and cell ledgers. |
| `05_validation/` | Future independent testing protocols and validation rounds. |
| `06_product/` | Product hypotheses, use cases, receipt schema, and commercial questions. |
| `07_private/` | Sensitive planning templates: IP notes, advisor questions, exposure log. |

`07_private/` can be renamed later if desired. Possible alternatives:

```text
07_sensitive_planning/
07_disclosure_control/
07_advisor_material/
07_originator_notes/
```

For now, keeping the folder name stable avoids breaking the zip structure.

---

## Extraction checklist

After extracting the zip and uploading the contents, confirm that these files exist:

```text
README.md
LICENSE.md
.gitignore
00_packet/packet_summary.md
01_presentation/slide_plan.md
01_presentation/teleprompter_script.md
02_demo_sentences/bilingual_pairs.csv
03_a_packets/a_packets_01_20.md
04_resolver_outputs/compact_cell_ledger.csv
05_validation/reviewer_protocol.md
06_product/sentence_receipt_schema.md
07_private/exposure_log.md
```

If those are present, the repository has the intended working shape.

---

## Recommended working order

1. Use `01_presentation/` to prepare the Anthony / PorterShed meeting.
2. Use `00_packet/`, `03_a_packets/`, and `04_resolver_outputs/` as the source evidence behind the talk.
3. Use `05_validation/` to design the first independent tests.
4. Use `06_product/` to clarify possible commercial wedges.
5. Use `07_private/` to track disclosure, advisor questions, and IP strategy.

---

## Next build layer

Once the repository contents are confirmed, the next useful files to add are:

```text
ROADMAP.md
DEMO_FLOW.md
VALIDATION_PLAN.md
PITCH_NOTES.md
```

These should translate the packet into action: what to show, who to show it to, what to test first, and what not to disclose casually.
