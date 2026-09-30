# Module 4: Making Meaning with NLP Semantics

This module explores how wording in clinical notes and survey questions affects the meaning of data. The hands-on activity builds a documented terminology crosswalk. Read **Rise Module 4, Sections 4.3–4.4**, choose one pathway, and use the matching prompts in the Module 4 notebook template.

## Start here

1. Download the Module 4 notebook template (`.ipynb`) from this GitHub folder. Keep it as an `.ipynb` file; do not convert it to a Word document or PDF.
2. Open Google Colab, sign in to your Google account, and choose **File → Upload notebook**. Select the downloaded template.
3. Choose **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M4_YourName`. Work in your own saved copy.
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

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. If your session disconnected, run the notebook from the first code cell again.

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.
