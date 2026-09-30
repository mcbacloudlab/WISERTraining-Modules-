# Module 6: Machine Learning for Addiction Research

This module uses a teaching dataset to explore how an outcome definition, model, threshold, and fairness audit affect a proposed return-to-use prediction workflow. Read **Rise Module 6, Sections 6.3–6.4** and complete one pathway in the Module 6 notebook template.

## Start here

1. Download the Module 6 notebook template (`.ipynb`) from this GitHub folder. Keep it as an `.ipynb` file; do not convert it to a Word document or PDF.
2. Open Google Colab, sign in to your Google account, and choose **File → Upload notebook**. Select the downloaded template.
3. Choose **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M6_YourName`. Work in your own saved copy.
4. Read the notebook’s **Start here** guide. In the first code cell, set `PATHWAY` to `"Foundational"` or `"Applied"` to match Rise. Enter your name or learner ID wherever requested.
5. Work from top to bottom. Read the instruction above each code cell, then click its **▶** button or press **Shift+Enter**. The result appears below the cell.
6. Follow the written action label: **Run** means use the supplied cell as directed; **Edit, then run** means change only the named fields. Replace bracketed prompts with your answer, keeping the surrounding quotation marks and table punctuation. Do not type into the output below the cell.
7. Complete your pathway’s written responses and additional work. Running all cells without completing the prompts produces an incomplete assignment. Applied learners must implement the required extensions, not only describe them.
8. Rerun affected cells and the final export after making changes. Review every required file, save the completed notebook separately, and submit the materials listed below through your course’s submission location.

A browser and Google account are sufficient; no local Python installation is needed. Use only the supplied teaching data or a source permitted for your pathway. Do not enter PHI, restricted participant data, or sensitive information.

## What do green and red text mean?

Colab automatically colors code to distinguish quoted text, comments, Python words, and other syntax. The colors depend on your theme and do **not** tell you which parts to edit.

- Follow **Run** and **Edit, then run** labels, rather than colors.
- Replace `[bracketed response prompts]` only where instructed. Keep quotation marks, field names, commas and braces intact.
- A red **error message below a cell** is different from colored code. Read the message, fix the named issue, and rerun that cell and the later cells that depend on it.
- Tables, charts and messages beneath a code cell are outputs to review; write your answers in the specified editable fields.


## Materials and data

Foundational automatically loads [hopebridge_ml.csv](./Data/hopebridge_ml.csv) from GitHub. Applied learners may use it for development or adapt the workflow to an approved public-use source, documenting provenance and outcome definitions. Optional insurance or encounter joins require compatible keys and features available at the prediction time.

## What you will investigate

Define a defensible six-month outcome, prevent target leakage, compare models, assess discrimination and calibration, audit subgroup results, and discuss the consequences of a decision threshold. The supplied `return_to_use_6mo` field is an **artificial teaching label**, not an adjudicated clinical outcome. In particular, the file cannot resolve prescribed buprenorphine use, ambiguous kratom findings, or missing toxicology. Do not present the prototype as ready for clinical deployment.

| Pathway | Additional work | Submit |
| --- | --- | --- |
| **Foundational (6.31)** | Compare logistic regression and a decision tree; inspect AUC, calibration, confusion matrix, and the race/SVI fairness audit; complete the model card and ~200-word fairness reflection. | Completed Colab link with view access, one-page PDF advisory-board brief, and documented outputs. |
| **Applied (6.32)** | Implement preprocessing pipelines; compare three models including a tuned random forest; report calibration/Brier scores and at least two subgroup dimensions and three fairness criteria; complete a ~500-word reflection. | Completed Colab link, model card and audit documentation, one-page PDF advisory-board brief, and documented outputs. |

The brief should explain the actual outcome, selected model, observed performance and subgroup limits, proposed threshold, safeguards, and governance in plain language. Use your notebook's measured results, not numbers from the fictional Rise scenario. Open the exported PDF and ZIP before submitting.
## Before you submit

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. If your session disconnected, run the notebook from the first code cell again.

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.
