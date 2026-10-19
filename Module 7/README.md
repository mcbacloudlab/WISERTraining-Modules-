# Module 7: Deep Learning and Images

Learn how convolutional neural networks (CNNs) handle images while assessing whether an image model could be responsibly studied in a different setting. Read **Rise Module 7, Sections 7.3–7.4** and choose one pathway in the Module 7 notebook template.

Please integrate the use of any AI tools you have to complete this colab.

## Start here: set up your copy

1. Download the Module 7 notebook template (`.ipynb`) from this GitHub folder.
2. Open Google Colab, sign in, and select **File → Upload notebook**. Choose the downloaded file. If you already have it open, continue to step 3.
3. Select **File → Save a copy in Drive**. Give your copy a recognizable name, such as `WISER_M7_YourName`, and work in that saved copy.
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

Foundational downloads Fashion-MNIST clothing images through the notebook. A GPU runtime can speed up training but is not required. Applied learners choose and document an openly licensed dataset and adapt the actual loader/model. Read the smartphone eye-scanning paper attached in Rise before writing the Applied appraisal.

## Keep the two tasks distinct

The Foundational CNN classifies **clothing images** in Fashion-MNIST. Its accuracy says nothing about opioid use, adolescent care, eye scans, or HopeBridge. The **Rise 7.3 protocol sketch** is a separate, proposed research plan. Complete it for either pathway; it does not authorize image collection or clinical deployment.

| Pathway | What to complete | Submit |
| --- | --- | --- |
| **Foundational (7.31)** | Build the guided CNN; interpret training/validation curves and a test error; write a ~250-word reflection connecting the exercise to validation and privacy decisions. | Completed `.ipynb`, reflection, and protocol sketch PDF. |
| **Applied (7.32)** | Adapt the CNN to a documented openly licensed dataset, implement an appropriate extension, write a 1–2 page model card, and critically appraise the smartphone eye-scanning paper attached in Rise (~500 words). | Adapted `.ipynb`, model card PDF, appraisal memo, and protocol sketch PDF. |

The notebook packages supporting figures and written answers in an outputs ZIP. If your instructor requests the Rise DOCX protocol template, transfer the completed sketch into that template as well. Rerun the notebook from the beginning and inspect each exported PDF before submitting.
## Before you submit

Check that you completed only your chosen pathway, replaced all required prompts, reviewed the actual results, and opened the exported PDF or tables. If you changed an earlier cell, rerun from that point downward. 

If a code error continues, share the error text and the section name with your instructor. Avoid changing unrelated code to make the message disappear.

