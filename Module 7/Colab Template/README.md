# WISER Module 7: Deep Learning and Images

Train or adapt a convolutional neural network (CNN), inspect image-classification errors, and draft a proposed HopeBridge study. Build on Module 6's separation of training and evaluation: now distinguish training, validation, and test images and assess the limits of transferring an image model to another setting.

## Open your notebook

1. Read **WISER Module 7, Sections 7.3–7.4**, and choose Foundational or Applied.
2. In GitHub, open the Module 7 `.ipynb` notebook file and click **Download raw file** to save it to your computer.
3. Open [Google Colab](https://colab.research.google.com/), choose **File → Upload notebook**, and select the downloaded `.ipynb` file. You will work in your own Colab instance.
4. Choose **File → Save a copy in Drive**. Work in your saved copy.
5. Set `PATHWAY` to `"Foundational"` or `"Applied"`, matching your WISER choice. Enter your learner name or ID where requested.
6. Follow the notebook from top to bottom. Click **▶** or press **Shift+Enter** to run a code cell, then read its output.

Edit answers in the **code cell**, not in the table or message below it. Replace the whole `[bracketed prompt]` with your answer while keeping quotation marks, field names, and punctuation. **Run** means no edit is required; **Edit, then run** names what to change; **Run, then answer** asks you to inspect output before writing in the response cell that follows.

Please integrate the use of any AI tools you have to complete this Colab. Check their suggestions against the source materials and your actual results. Use only permitted data; do not enter protected health information, identifiable clinical records or images, or restricted participant data.

## Materials and setup

- Foundational loads **Fashion-MNIST clothing images** through the notebook. The exercise does not require you to upload clinical images.
- Applied requires an openly licensed replacement dataset, documented source/license terms, an adapted loader/model, and an implemented extension.
- Applied also requires the smartphone eye-scanning paper supplied in WISER; read it before writing the appraisal.
- TensorFlow is required. If the import cell reports it is missing, run `%pip install tensorflow` in a separate Colab code cell, restart the runtime/session, and rerun from the top. The small guided subset can run on a CPU; a GPU is optional.

The clothing classifier and the HopeBridge clinical research proposal are **separate tasks**. Clothing accuracy does not validate facial/ocular or adolescent return-to-use prediction.

## What you will do

1. Enter your learner ID and document dataset provenance and reuse conditions. Load independent training, validation, and test splits.
2. Inspect the training-image gallery. In the following answer cell, identify visually similar classes and write gallery alt text.
3. Run the CNN training cell and let it finish. Do not retrain simply to enter a written answer.
4. Compare training/validation accuracy and loss, then complete the separate curve-response cell. State whether the displayed evidence suggests overfitting; three epochs may not establish it.
5. Evaluate the held-out test data. Read the class report and confusion matrix, then cite an error or low-recall class in the separate error-response cell. Describe what overall accuracy hides.
6. Connect validation, consent/privacy, and continuity of care to the WISER HopeBridge scenario. Complete every field of the proposed protocol sketch.
7. Complete your pathway reflection/appraisal and, for Applied, the implemented extension and model card. Choose model changes using training/validation evidence rather than repeatedly tuning to test results.

## Choose one pathway

| Pathway | Required work | Submission |
| --- | --- | --- |
| **Foundational — WISER 7.31** | Guided Fashion-MNIST CNN, gallery/curve/error interpretations, scenario connection, protocol sketch, and approximately **250-word** reflection. | Completed `.ipynb`, reflection, and protocol-sketch PDF; retain the supporting outputs ZIP as directed in WISER. |
| **Applied — WISER 7.32** | Adapt an openly licensed replacement dataset, implement and justify an appropriate extension, complete the protocol and a **1–2 page** model card, and critically appraise the assigned paper in approximately **500 words**. | Adapted `.ipynb`, model-card PDF, appraisal memo, protocol-sketch PDF, and supporting outputs as directed in WISER. |

Applied must change the actual loading/preprocessing/model workflow, not just the dataset name. Document the implemented changes in `APPLIED_ADAPTATION_NOTES` and the model card. If WISER requests its DOCX protocol template, transfer your completed protocol answers into it too.

## Exported files

The final cell creates `WISER_Module_7_outputs.zip`, containing `module7_outputs/`.

| File | Contents |
| --- | --- |
| `Module_7_protocol_sketch.pdf`, `protocol_sketch.md` | Proposed research protocol for either pathway. |
| `training_validation_curves.png`, `confusion_matrix.png` | Learning curves and test-error summary. |
| `responses.md` | Observations, scenario connection, and pathway response. |
| `foundational_reflection.md` | Foundational reflection only. |
| `Module_7_model_card.pdf`, `model_card.md`, `appraisal_memo.md` | Applied documentation only; the supplied PDF summary fits within the 1–2 page requirement. |
| `metadata.json`, `README.md` | Dataset and methods documentation. |

The notebook does not export source images or individual predictions. The protocol PDF limits each field to 230 characters; the model-card summary limits each field to 310. Shorten the named field if a layout error appears.

## Save, check, and submit

- After a pause, rerun code cells from the top, keeping your completed answers. Colab may have cleared earlier data or variables.
- If you change an earlier answer or setting, rerun from that cell downward, including export.
- Resolve the required `TO COMPLETE` notices. A successful run alone does not complete the assignment.
- Open the exported files and check that they match your answers and results. In Colab's **Files** panel, use the file menu to download a PDF or other output if needed.
- Save the completed notebook separately with **File → Download → Download .ipynb**. Follow WISER's submission location and access instructions for your pathway.

If a cell fails, read the first error message, correct the named issue, and rerun. If you need help, share the error text and section name with your instructor. Code colors are syntax highlighting, not instructions about what to edit.

