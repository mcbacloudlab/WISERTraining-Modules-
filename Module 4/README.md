# WISER Module 4: Making Meaning with NLP Semantics

Inspect synthetic notes, normalize wording, recognize mentions, and document terminology-mapping decisions. This is the most guided activity in the Module 4–8 sequence. Its definition and language checks prepare you to make accurate chart claims in Module 5.

## Open your notebook

1. Read **WISER Module 4, Sections 4.3–4.4**, and choose Foundational or Applied.
2. In GitHub, open the Module 4 `.ipynb` notebook file and click **Download raw file** to save it to your computer.
3. Open [Google Colab](https://colab.research.google.com/), choose **File → Upload notebook**, and select the downloaded `.ipynb` file. You will work in your own Colab instance.
4. Choose **File → Save a copy in Drive**. Work in your saved copy.
5. Set `PATHWAY` to `"Foundational"` or `"Applied"`, matching your WISER choice. Enter your learner name or ID where requested.
6. Follow the notebook from top to bottom. Click **▶** or press **Shift+Enter** to run a code cell, then read its output.

Edit answers in the **code cell**, not in the table or message below it. Replace the whole `[bracketed prompt]` with your answer while keeping quotation marks, field names, and punctuation. **Run** means no edit is required; **Edit, then run** names what to change; **Run, then answer** asks you to inspect output before writing in the response cell that follows.

Please integrate the use of any AI tools you have to complete this Colab. Check their suggestions against the source materials and your actual results. Use only permitted data; do not enter protected health information, identifiable clinical records or images, or restricted participant data.

## Materials

- [Synthetic notes](./Data/notes.csv), loaded automatically by the notebook.
- The three-wave NSDUH teaching subset and matching-year codebooks supplied in WISER. Open these before completing the crosswalk.
- Source definitions for any HEAL common data element (CDE) or RxNorm target you consider. The notebook does not supply verified target identifiers.

## What you will do

1. Load the notes and inspect the identifier-pattern results. Explain why a simple pattern check cannot certify de-identification.
2. Add one abbreviation rule and one drug-name variation. Section 3 contains two marked edit locations; the notebook's **Start here** section provides the single worked TODO example. Follow that example there rather than adding it to other cells.
3. Run the supplied recognition rules and describe one match and one limitation. Finding a mention is different from verifying a concept link.
4. Complete the three independently editable crosswalk rows, `CW-001`–`CW-003`. Find the exact source variable in the teaching subset, locate it in the matching-year codebook, and cite the wording, definition/timeframe, and page or item. Compare source and target evidence before selecting `supported`, `uncertain`, or `no suitable mapping`. Leave an unverified target ID blank.
5. Review flagged language, write a respectful replacement sentence and rationale, and explain one bias-review step.

Repeated identical note text is not independent evidence. The notebook displays the row and distinct-text counts and uses representative distinct texts for practice.

## Choose one pathway

| Pathway | Required work | Submission |
| --- | --- | --- |
| **Foundational — WISER 4.31** | Complete the guided activities and three crosswalk rows. Write approximately **200 words** on one terminology-drift case, the evidence you checked, and what you would not combine. | Completed notebook and reflection, as directed in WISER. The reflection is also included in the exported responses. |
| **Applied — WISER 4.32** | Implement source-specific ingestion, transformer-based named entity recognition, concept-linking decisions, and an embedding-neighbor audit for stigma terms. Document methods/model versions and write an approximately **500-word** validity memo. | Notebook, crosswalk bundle with completed schema/README and verified reuse/license information, and validity memo. The guided examples alone do not fulfill Applied. |

## Exported files

The final cell creates `WISER_Module_4_submission.zip`, containing `module4_outputs/`.

| File | Contents |
| --- | --- |
| `terminology_crosswalk.csv` | Your mapping decisions and source references. |
| `normalized_analysis_layer.csv` | Derived analysis text and rule-based mentions; this is not a raw-note export. |
| `responses.md` | Review answers and your reflection or memo. |
| `metadata.json` | Source and processing details. |
| `crosswalk_schema.json`, `README.md`, `LICENSE.txt` | Draft bundle documentation. Applied learners must complete and verify the schema, README, and reuse/license information. |

## Save, check, and submit

- After a pause, rerun code cells from the top, keeping your completed answers. Colab may have cleared earlier data or variables.
- If you change an earlier answer or setting, rerun from that cell downward, including export.
- Resolve the required `TO COMPLETE` notices. A successful run alone does not complete the assignment.
- Open the exported files and check that they match your answers and results. In Colab's **Files** panel, use the file menu to download a PDF or other output if needed.
- Save the completed notebook separately with **File → Download → Download .ipynb**. Follow WISER's submission location and access instructions for your pathway.

If a cell fails, read the first error message, correct the named issue, and rerun. If you need help, share the error text and section name with your instructor. Code colors are syntax highlighting, not instructions about what to edit.

