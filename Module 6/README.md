Module 6: Machine Learning for Addiction Research

This module uses a teaching dataset to explore how an outcome definition, model, threshold, and fairness audit affect a proposed return-to-use prediction workflow. Read Rise Module 6, Sections 6.3–6.4 and complete one pathway in the Module 6 notebook template.

Start here
1. Download the Module 6 .ipynb template from this GitHub folder. Open Google Colab, upload the downloaded notebook, and select File → Save a copy in Drive.
2. Select Foundational or Applied, then run the notebook in order. Read the outputs, complete the learner response fields, and rerun the final export. Running every cell without editing does not finish the assignment.
3. Foundational automatically loads [synthetic HopeBridge ML data](./Data/hopebridge_ml.csv). Applied may use that file for development or an approved public-use dataset; document any change of source and feature definitions.
4. Never upload restricted participant data, PHI, or identifiable clinical records.
What you will investigate
Define a defensible six-month outcome, prevent target leakage, compare models, assess discrimination and calibration, audit subgroup results, and discuss the consequences of a decision threshold. The supplied return_to_use_6mo field is an artificial teaching label, not an adjudicated clinical outcome. In particular, the file cannot resolve prescribed buprenorphine use, ambiguous kratom findings, or missing toxicology. Do not present the prototype as ready for clinical deployment.
Pathway	Additional work	Submit
Foundational (6.31)	Compare logistic regression and a decision tree; inspect AUC, calibration, confusion matrix, and the race/SVI fairness audit; complete the model card and ~200-word fairness reflection.	Completed Colab link with view access, one-page PDF advisory-board brief, and documented outputs.
Applied (6.32)	Implement preprocessing pipelines; compare three models including a tuned random forest; report calibration/Brier scores and at least two subgroup dimensions and three fairness criteria; complete a ~500-word reflection.	Completed Colab link, model card and audit documentation, one-page PDF advisory-board brief, and documented outputs.


The brief should explain the actual outcome, selected model, observed performance and subgroup limits, proposed threshold, safeguards, and governance in plain language. Use your notebook's measured results, not numbers from the fictional Rise scenario. Open the exported PDF and ZIP before submitting.
