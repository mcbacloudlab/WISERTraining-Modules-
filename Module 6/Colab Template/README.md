# WISER Module 6: Machine Learning for Addiction Research

Compare prediction models, inspect errors and subgroup results, and explain your findings in a model card and advisory-board brief. Build on Module 5's evidence and communication checks: move from describing a pattern to judging a prediction and its consequences.

## Open your notebook

1. Read **WISER Module 6, Sections 6.3–6.4**, and choose Foundational or Applied.
2. In GitHub, open the Module 6 `.ipynb` notebook file and click **Download raw file** to save it to your computer.
3. Open [Google Colab](https://colab.research.google.com/), choose **File → Upload notebook**, and select the downloaded `.ipynb` file. You will work in your own Colab instance.
4. Choose **File → Save a copy in Drive**. Work in your saved copy.
5. Set `PATHWAY` to `"Foundational"` or `"Applied"`, matching your WISER choice. Enter your learner name or ID where requested.
6. Follow the notebook from top to bottom. Click **▶** or press **Shift+Enter** to run a code cell, then read its output.

Edit answers in the **code cell**, not in the table or message below it. Replace the whole `[bracketed prompt]` with your answer while keeping quotation marks, field names, and punctuation. **Run** means no edit is required; **Edit, then run** names what to change; **Run, then answer** asks you to inspect output before writing in the response cell that follows.

Please integrate the use of any AI tools you have to complete this Colab. Check their suggestions against the source materials and your actual results. Use only permitted data; do not enter protected health information, identifiable clinical records or images, or restricted participant data.

## Materials

- [Synthetic teaching data](./Data/hopebridge_ml.csv), loaded automatically for Foundational.
- Applied may use the disclosed synthetic development workflow or adapt an approved public-use source. If using another CSV, document its provenance and eligibility and adapt the required labels, predictors, audit fields, and output descriptions. A different file path alone does not complete that adaptation.

`return_to_use_6mo` is an **artificial teaching label**. The file cannot resolve prescribed buprenorphine use, ambiguous kratom findings, or missing toxicology. Writing a better proposed clinical definition does not relabel these records; the supplied models still predict the teaching label.

## What you will do

1. Inspect source fields and label balance. Draft a proposed six-month outcome protocol and an intended use involving optional additional peer support.
2. Run the held-out split and preprocessing pipeline. Check that identifiers, outcomes, and later follow-up information are excluded from predictors. Training data determine preprocessing.
3. Compare model results. AUC describes ranking; Brier score describes probability error. Choose a model for discussion using performance, interpretability, and limitations.
4. Inspect calibration and the confusion matrix. Write your model-choice response in its separate answer cell.
5. Review at least race/ethnicity and SVI quartile results. Cite actual metric values and sample sizes, explain false-positive/false-negative consequences, and identify an advisory-board question. Small gaps on one measure do not establish fairness overall.
6. Compare illustrative thresholds. Recommend one for discussion and document reviewers, review frequency, stakeholder feedback, and a specific stop condition. Repeated test-set choices are exploratory, not an independent final validation.
7. Complete the model card and one-page advisory brief with your run's measured results, then write your pathway reflection.

## Choose one pathway

| Pathway | Required work | Submission |
| --- | --- | --- |
| **Foundational — WISER 6.31** | Compare logistic regression and a decision tree; interpret calibration, errors, and subgroup results; complete the model card/brief; write approximately **200 words** on one fairness tradeoff. | Viewable completed Colab link, one-page advisory-board PDF, and documented outputs. |
| **Applied — WISER 6.32** | Complete the expanded preprocessing/modeling, cross-validated random-forest tuning, calibration, and audit workflow. Examine at least two subgroup dimensions and positive-selection share, TPR/FPR, and calibration. Write approximately **500 words** on outcome-definition and fairness tradeoffs. | Completed Colab link, model card and audit documentation, advisory-board PDF, and documented outputs. Disclose any synthetic development fallback. |

The Applied comparison displays both tuned and calibrated forest results alongside the two baseline models. Synthetic-data performance does not establish clinical readiness, and a low research score must not remove existing services.

## Exported files

The final cell creates `WISER_Module_6_outputs.zip`, containing `module6_outputs/`.

| File | Contents |
| --- | --- |
| `Module_6_advisory_board_brief.pdf` | One-page findings, limitations, and next-step summary. |
| `model_comparison.csv`, `calibration_plot.png` | Overall comparison and calibration results. |
| `aggregate_fairness_audit.csv`, `threshold_comparison.csv` | Aggregate subgroup results and exploratory threshold tradeoffs. |
| `model_card.md`, `responses_and_reflection.md` | Model documentation, answers, and reflection. |
| `metadata.json`, `README.md` | Source, features, split, and methods documentation. |

Only aggregate audit results are exported; the supplied export does not include person-level predictions. The ZIP does not replace the required Colab link or PDF.

## Save, check, and submit

- After a pause, rerun code cells from the top, keeping your completed answers. Colab may have cleared earlier data or variables.
- If you change an earlier answer or setting, rerun from that cell downward, including export.
- Resolve the required `TO COMPLETE` notices. A successful run alone does not complete the assignment.
- Open the exported files and check that they match your answers and results. In Colab's **Files** panel, use the file menu to download a PDF or other output if needed.
- Save the completed notebook separately with **File → Download → Download .ipynb**. Follow WISER's submission location and access instructions for your pathway.

If a cell fails, read the first error message, correct the named issue, and rerun. If you need help, share the error text and section name with your instructor. Code colors are syntax highlighting, not instructions about what to edit.
