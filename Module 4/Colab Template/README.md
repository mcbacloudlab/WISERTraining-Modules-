Module 4: Making Meaning with NLP Semantics


This module explores how wording in clinical notes and survey questions affects the meaning of data. The hands-on activity builds a documented terminology crosswalk. Read Rise Module 4, Sections 4.3–4.4, choose one pathway, and use the matching prompts in the [Module 4 Colab notebook](./WISER_M4_NLP_Semantics_Template_Revised.ipynb).
Start here
1. Open the notebook in Google Colab and select File → Save a copy in Drive. A browser and Google account are sufficient; you do not need a local Python installation.
2. Select Foundational or Applied as directed in Rise. Complete only that pathway.
3. Run the cells in order, read the results, and replace the marked learner responses. Then rerun the affected cells and final export. Run all by itself leaves the assignment incomplete.
4. Use only synthetic or appropriately licensed public-use material. Never enter real clinical notes, PHI, or sensitive data into the notebook.
Materials
- [Synthetic clinical notes](./Data/notes.csv) are loaded automatically by the notebook from this repository.
- [Visit-level context](./Data/encounters.csv) is optional.
- The curated three-wave NSDUH items and the crosswalk worksheet are provided in Rise. Consult the relevant codebooks before claiming a survey-item match.
What you will do
Check the supplied text for obvious identifiers, add an abbreviation rule and a medication-name variation, use the supplied recognition rules for drug/dose/route mentions, and document supported or uncertain links to HEAL CDEs and RxNorm. Review potentially stigmatizing language. A pattern check does not certify de-identification, and recognizing a term does not verify a vocabulary match.
Pathway	Additional work	Submit
Foundational (4.31)	Complete three crosswalk rows and a ~200-word reflection on a terminology drift case.	Completed notebook and reflection.
Applied (4.32)	Build source-specific ingestion and transformer-based NER, audit embedding neighbors for stigma terms, and document validity threats.	Notebook, crosswalk bundle (CSV, completed JSON schema, README, verified reuse/license information), and ~500-word memo.


The notebook can export a ZIP for review. Verify the crosswalk, source references, and permissions before sharing it; its draft schema and blank license field are prompts to complete, not verified claims. Follow your course's submission location and access instructions.
