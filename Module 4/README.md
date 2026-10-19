# Module 4: Making Meaning with NLP Semantics

This module explores how wording in clinical notes and survey questions affects the meaning of data. The hands-on activity builds a documented terminology crosswalk. Read **Rise Module 4, Sections 4.3–4.4**, choose one pathway, and use the matching prompts in the Module 4 notebook template.

Please integrate the use of any AI tools you have to complete this colab.

## Start here: set up your copy

1. Download the Module 4 notebook template (`.ipynb`) from this GitHub folder.
2. Open Google Colab, sign in, and select **File → Upload notebook**. Choose the downloaded file. If you already have it open, continue to step 3.
3. Select **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M4_YourName`, and work in that saved copy.
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

## Materials

- [Synthetic clinical notes](./Data/notes.csv) are loaded automatically by the notebook from this repository.
- [Visit-level context](./Data/encounters.csv) is optional.
- The curated three-wave NSDUH items and the crosswalk worksheet are provided in Rise. Consult the relevant codebooks before claiming a survey-item match.

## What you will do

Check the supplied text for obvious identifiers, add an abbreviation rule and a medication-name variation, use the supplied recognition rules for drug/dose/route mentions, and document supported or uncertain links to HEAL CDEs and RxNorm. Review potentially stigmatizing language. A pattern check does not certify de-identification, and recognizing a term does not verify a vocabulary match.

| Pathway | Additional work | Submit |
| --- | --- | --- |
| **Foundational (4.31)** | Complete three crosswalk rows and a ~200-word reflection on a terminology drift case. | Completed notebook and reflection. |
| **Applied (4.32)** | Build source-specific ingestion and transformer-based NER, audit embedding neighbors for stigma terms, and document validity threats. | Notebook, crosswalk bundle (CSV, completed JSON schema, README, verified reuse/license information), and ~500-word memo. |

The notebook can export a ZIP for review. Verify the crosswalk, source references, and permissions before sharing it; its draft schema and blank license field are prompts to complete, not verified claims. Follow your course's submission location and access instructions.

## Before you submit

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. 

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.
