# Module 5: Data Visualization and Communication

Use data and a one-page brief to make a clear, responsible message for a decision-making audience. Read **Rise Module 5, Sections 5.3–5.4**, select one pathway, and complete the Module 5 notebook template.

Please integrate the use of any AI tools you have to complete this colab.

## Start here: set up your copy

1. Download the Module 5 notebook template (`.ipynb`) from this GitHub folder.
2. Open Google Colab, sign in, and select **File → Upload notebook**. Choose the downloaded file. If you already have it open, continue to step 3.
3. Select **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M5_YourName`, and work in that saved copy.
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

Foundational automatically loads [post_overdose_data.csv](./Data/post_overdose_data.csv) from GitHub. Applied learners set `APPLIED_SOURCE` to a permitted public aggregate CSV and implement the appropriate ingestion and analysis; the synthetic option supports offline practice. Document any changed source in your chart, brief and metadata.

## Interpret the supplied data carefully

`post_overdose_data.csv` contains **synthetic event records**, not verified deaths or a population denominator. The Foundational chart shows monthly counts of recorded opioid-involved events. Do not describe them as overdose mortality rates or calculate a rate per 100,000 without a matching numerator and population denominator. Check the actual provisional flags before describing uncertainty.

## Pathway and deliverables

| Pathway | What to complete | Submit |
| --- | --- | --- |
| **Foundational (5.31)** | One accessible, accurately labeled chart; one-page decision brief; ~200-word reflection on a charting tradeoff. | Colab notebook link with view access, one-page PDF brief, and documented outputs folder or ZIP. |
| **Applied (5.32)** | Your own public-data ingestion, cleaning, chart, suppression/denominator decisions, and verified HEAL CDE crosswalk. Optional SUDORS or SVI joins require compatible source definitions and access terms. | Reproducible notebook link, chart and one-page PDF brief, crosswalk, and documented outputs folder or ZIP. |

Before submitting, open the PDF, confirm chart title, units, source, provisional-data explanation and limitations, and make sure the notebook link is viewable by your instructor. The notebook exports its reflection with the outputs. Follow the submission location specified in your course.

## Before you submit

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. 

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.

