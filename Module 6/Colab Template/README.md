# Module 6: Machine Learning for Addiction Research

This module uses a teaching dataset to explore how an outcome definition, model, threshold, and fairness audit affect a proposed return-to-use prediction workflow. Read **Rise Module 6, Sections 6.3–6.4** and complete one pathway in the Module 6 notebook template.

Please integrate the use of any AI tools you have to complete this colab.

## Start here: set up your copy

1. Download the Module 6 notebook template (`.ipynb`) from this GitHub folder.
2. Open Google Colab, sign in, and select **File → Upload notebook**. Choose the downloaded file. If you already have it open, continue to step 3.
3. Select **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M6_YourName`, and work in that saved copy.
4. In the first code cell, set `PATHWAY` to `"Foundational"` or `"Applied"` to match Rise. Enter your name or learner ID wherever requested.
5. Work from the top down. Read the instruction before each code cell, make the requested edits, and click **▶** or press **Shift+Enter**. Review the result below the cell before continuing.

A browser and Google account are sufficient; no local Python installation is needed. Use only data permitted for your pathway. Do not enter PHI, restricted participant data, identifiable clinical records or images, or other sensitive information.

## Know what to edit

- **Run:** Use the supplied cell as directed; no edit is needed for that example.
- **Edit, then run:** Change only the named response fields or settings.
- **Bracketed prompts:** Replace `[the prompt]` with your answer, keeping quotation marks, field names and punctuation. Write in the editable code cell, not the output below it.
- **TODO lines:** Before running each section, complete any `#TODO` or `# TODO` instructions in its code. Replace the **entire instruction line** with completed code so the finished line no longer starts with the marker. Keep unrelated explanatory `#` comments.

For example, inside the dictionary where instructed, replace:

```python
# TODO: add "oud": "opioid use disorder"
```

with:

```python
"oud": "opioid use disorder",
```

This example shows the format; do not add it to other cells. Running all cells without completing the learner prompts leaves an incomplete assignment. Applied learners must implement their required extensions as well as document them.

## Understand the colors

Colab automatically colors quoted text, comments, Python words and other syntax. Green and red text **inside code** do not tell you what to edit; colors vary by theme. Follow the written action labels. A red **error message below a cell** is different: read it, correct the named issue, and rerun that cell and any later cells that depend on it.

## Returning after a pause

If you pause for any length of time, save your work. When you return, **rerun all code cells starting from the top** before continuing. Keep your completed answers in place. Colab may disconnect or clear the working session while you are away, so earlier data and variables may need to be loaded again.

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

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. 

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.

