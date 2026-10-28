# WISER Module 8: Translational Portfolio Capstone

Bring the methods from Modules 4–7 together in one research-planning portfolio. You now choose and justify a coherent measurement plan, trace changes from feedback, and communicate the decision needed. This exercise does not generate trial results or establish a clinical decision tool.

## Open your notebook

1. Read **WISER Module 8, Sections 8.3–8.4**, and choose Foundational or Applied.
2. In GitHub, open the Module 8 `.ipynb` notebook file and click **Download raw file** to save it to your computer.
3. Open [Google Colab](https://colab.research.google.com/), choose **File → Upload notebook**, and select the downloaded `.ipynb` file. You will work in your own Colab instance.
4. Choose **File → Save a copy in Drive**. Work in your saved copy.
5. Set `PATHWAY` to `"Foundational"` or `"Applied"`, matching your WISER choice. Enter your learner name or ID where requested.
6. Follow the notebook from top to bottom. Click **▶** or press **Shift+Enter** to run a code cell, then read its output.

Edit answers in the **code cell**, not in the table or message below it. Replace the whole `[bracketed prompt]` with your answer while keeping quotation marks, field names, and punctuation. **Run** means no edit is required; **Edit, then run** names what to change; **Run, then answer** asks you to inspect output before writing in the response cell that follows.

Please integrate the use of any AI tools you have to complete this Colab. Check their suggestions against the source materials and your actual results. Use only permitted data; do not enter protected health information, identifiable clinical records or images, or restricted participant data.

## Materials

- Foundational uses the WISER Phase 2 non-opioid analgesic **measurement-planning** question and may remain template-only: no participant dataset or fitted model is required.
- Applied uses a mentor-approved addiction-science question and a permitted source, with source-specific evidence and implemented mapping/review work.
- The WISER HopeBridge implementation-risk feedback is **instructor-simulated** unless actual approved feedback is available. Identify its source honestly.
- Earlier module outputs can inform your choices. The earlier datasets differ; do not automatically join them or treat their results as clinical evidence for this project.

## How the earlier modules connect

| Earlier module | Apply here |
| --- | --- |
| 4 — NLP semantics | Compare definitions, document label drift, and preserve uncertainty in mappings. |
| 5 — Visualization | Choose an audience, make an evidence-supported statement, and communicate caveats and a next step. |
| 6 — Machine learning | Specify intended use, error/fairness review, model limits, and governance. |
| 7 — Images | Distinguish within-source evaluation from external validation; address image consent, privacy, and continuity of care. |

In `learning_connections`, explain how one method from each module informs your plan. Reuse reasoning and documentation where relevant rather than copying unrelated results.

## Build the portfolio

1. **Scope and workplan:** State the population, question, intended decision, audience, and evidence stage. Assign owner roles, deliverables, review gates, and risks.
2. **Modality comparison:** Compare wearable summaries, consented task-based video summaries, clinical text/NLP, and tabular/reported data with no-code ML. Address measures, cost/burden, latency, privacy, and interpretability, with sources. Recommend an initial combination and explain the tradeoffs; a no-code tool is not itself a measurement source.
3. **Legacy-label mapping:** Complete both legacy-label rows. Compare definitions before proposing current constructs, leave unsupported IDs empty, and route ambiguity to qualified review. Applied also adapts the routing logic and checks synthetic test cases.
4. **Cards and CDE crosswalk:** Document source/status, access, reuse conditions, intended use, evidence, and limitations. State clearly when no model was fitted. Enter HEAL CDE identifiers only after verifying both definitions.
5. **Human review:** Specify reviewer roles, triggers, allowed actions, log fields, and audit frequency. A blank log schema is not evidence of completed review. Applied implements a handoff and logs a synthetic test decision.
6. **Feedback and revision:** Address wearable adherence, perceived video surveillance, and unclear vendor residency. Record before/after changes, owners, and follow-up evidence. Revise earlier portfolio sections wherever a change affects them, then rerun from the earliest edit.
7. **Brief and reflection:** Write a one-page planning brief that agrees with the tables, feedback changes, and review plan. Complete your pathway reflection or memo without repeating every table.

## Choose one pathway

| Pathway | Required work | Submission |
| --- | --- | --- |
| **Foundational — WISER 8.31** | Provided measurement-planning question, completed planning artifacts and both legacy-label rows, simulated-feedback revisions, and approximately **300 words** on one consequential change. | Completed notebook and portfolio ZIP with brief, documentation, feedback memo, and reflection. |
| **Applied — WISER 8.32** | Mentor-approved question, permitted source, cited modality evidence, implemented source-specific mapping/review/logging workflow, and approximately **800 words** on the claim, evidence limits, governance, and feedback changes. | Completed notebook and full portfolio ZIP, including the revised brief, documentation, feedback memo, and pathway memo. |

## Exported files

The final cell creates `WISER_Module_8_portfolio.zip`, containing `module8_portfolio/`.

| Files | Contents |
| --- | --- |
| `Module_8_one_page_brief.pdf`, `brief_text.md` | Planning decision, recommendation, safeguards, limitations, and next step. |
| `project_workplan.csv`, `modality_comparison.csv` | Workplan and evidence-based comparison. |
| `dsm5_mapping.csv`, `heal_cde_crosswalk.csv` | Legacy-label decisions and CDE documentation. |
| `dataset_card.md`, `model_card.md` | Source, status, use, and limitations. |
| `human_review_specification.csv`, `review_log_schema.csv` | Review plan and log structure. |
| `feedback_revision_log.csv`, `hopebridge_feedback_memo.md` | Traceable feedback changes and unresolved issues. |
| `learning_connections.md`, `pathway_reflection_or_memo.md` | Earlier-module connections and pathway response. |
| `metadata.json`, `README.md` | Portfolio provenance and FAIR documentation. |

FAIR means findable, accessible, interoperable, and reusable. Document permissions and reuse conditions rather than assuming that a portfolio is ready to share. The PDF limits its headline to 170 characters and each section to 230; shorten the named field if needed.

## Save, check, and submit

- After a pause, rerun code cells from the top, keeping your completed answers. Colab may have cleared earlier data or variables.
- If you change an earlier answer or setting, rerun from that cell downward, including export.
- Resolve the required `TO COMPLETE` notices. A successful run alone does not complete the assignment.
- Open the exported files and check that they match your answers and results. In Colab's **Files** panel, use the file menu to download a PDF or other output if needed.
- Save the completed notebook separately with **File → Download → Download .ipynb**. Follow WISER's submission location and access instructions for your pathway.

If a cell fails, read the first error message, correct the named issue, and rerun. If you need help, share the error text and section name with your instructor. Code colors are syntax highlighting, not instructions about what to edit.
