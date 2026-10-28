# WISER Module 5: Data Visualization and Communication

Create an accessible chart and a one-page decision brief for a chosen audience. Build on Module 4's definition checks: decide what the data actually measure before describing a pattern. The plotting code is supplied; you take more responsibility for the question, interpretation, and recommended action.

## Open your notebook

1. Read **WISER Module 5, Sections 5.3–5.4**, and choose Foundational or Applied.
2. In GitHub, open the Module 5 `.ipynb` notebook file and click **Download raw file** to save it to your computer.
3. Open [Google Colab](https://colab.research.google.com/), choose **File → Upload notebook**, and select the downloaded `.ipynb` file. You will work in your own Colab instance.
4. Choose **File → Save a copy in Drive**. Work in your saved copy.
5. Set `PATHWAY` to `"Foundational"` or `"Applied"`, matching your WISER choice. Enter your learner name or ID where requested.
6. Follow the notebook from top to bottom. Click **▶** or press **Shift+Enter** to run a code cell, then read its output.

Edit answers in the **code cell**, not in the table or message below it. Replace the whole `[bracketed prompt]` with your answer while keeping quotation marks, field names, and punctuation. **Run** means no edit is required; **Edit, then run** names what to change; **Run, then answer** asks you to inspect output before writing in the response cell that follows.

Please integrate the use of any AI tools you have to complete this Colab. Check their suggestions against the source materials and your actual results. Use only permitted data; do not enter protected health information, identifiable clinical records or images, or restricted participant data.

## Materials

- [Synthetic event records](./Data/post_overdose_data.csv), loaded automatically for Foundational.
- For Applied, a permitted public aggregate CSV and its documentation. Upload it through Colab's **Files** panel, copy its path into `APPLIED_SOURCE`, and adapt the cleaning and analysis to its fields. Setting `APPLIED_SOURCE = "synthetic"` supports practice, not the final public-data extension.
- Source and target definitions for the Applied HEAL CDE crosswalk.

The supplied file contains synthetic event records, **not verified deaths or a population denominator**. Its monthly chart shows counts of recorded opioid-involved events. These counts cannot establish mortality or population rates. Provisional flags indicate possible revision, not its size or direction.

## What you will do

1. Inspect fields, duplicate IDs, missing dates, and the reporting period. Review the source-definition/CDE table; Foundational may retain explicitly unverified candidate mappings.
2. Build monthly recorded-event counts and examine the actual provisional flags. Explain one equity limitation of comparing counts without denominators or coverage information.
3. Choose an audience, question, and action goal. Write the title, caption, and alt text; draw the chart and check its dates, units, and provisional shading.
4. Review wording and accessibility. Complete the accessibility response in the audit cell, revising earlier chart fields if necessary.
5. Draft a chart-supported finding, two or three caveats, and an action with an owner and timeframe. Export and inspect the one-page PDF.
6. Write approximately **200 words** on one evidence or communication tradeoff. This reflection is required for **both pathways**.

## Choose one pathway

| Pathway | Required work | Submission |
| --- | --- | --- |
| **Foundational — WISER 5.31** | Guided synthetic-event analysis, accessible chart, one-page brief, equity/accessibility responses, and approximately 200-word tradeoff reflection. | Viewable Colab notebook link, one-page PDF brief, and documented outputs folder or ZIP. |
| **Applied — WISER 5.32** | Implement public-data ingestion, cleaning, aggregation, and appropriate suppression/denominator decisions. Complete a documented HEAL CDE crosswalk, adapting labels and source notes to your source. Include the chart, brief, and approximately 200-word reflection. | Reproducible notebook link, chart and PDF brief, crosswalk, and documented outputs folder or ZIP. |

Applied transformations belong **before** the analysis cells that depend on them. The supplied plotting branch expects one row per month with `month`, numeric `recorded_events`, and Boolean `provisional` fields; adapt the workflow consistently if your source needs another structure. Optional SUDORS/SVI joins require compatible definitions, geography, periods, and access terms. Record unverified or unsuitable mappings honestly; never invent identifiers or denominators.

## Exported files

The final cell creates `WISER_Module_5_outputs.zip`, containing `module5_outputs/`.

| File | Contents |
| --- | --- |
| `Module_5_one_page_decision_brief.pdf` | Audience, question, finding, chart, caveats, and action. |
| `module5_primary_chart.png`, `chart_alt_text.txt` | Figure and its text description. |
| `monthly_recorded_events.csv`, `cde_alignment_table.csv` | Plot-ready counts and variable-mapping documentation. |
| `reflection.txt`, `brief_text.md` | Tradeoff reflection and brief text. |
| `metadata.json`, `README.md` | Source and methods documentation. |

## Save, check, and submit

- After a pause, rerun code cells from the top, keeping your completed answers. Colab may have cleared earlier data or variables.
- If you change an earlier answer or setting, rerun from that cell downward, including export.
- Resolve the required `TO COMPLETE` notices. A successful run alone does not complete the assignment.
- Open the exported files and check that they match your answers and results. In Colab's **Files** panel, use the file menu to download a PDF or other output if needed.
- Save the completed notebook separately with **File → Download → Download .ipynb**. Follow WISER's submission location and access instructions for your pathway.

If a cell fails, read the first error message, correct the named issue, and rerun. If you need help, share the error text and section name with your instructor. Code colors are syntax highlighting, not instructions about what to edit.
