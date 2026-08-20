WISER Module 4: Making Meaning with NLP Semantics

Overview
Module 4 introduces natural language processing (NLP) approaches for identifying and harmonizing changes in opioid-related terminology across survey and clinical text. Learners use Python-based NLP techniques to explore terminology drift, normalize language, identify opioid-related concepts, and audit outputs for stigmatizing language.

The hands-on activity is completed using a Google Colab notebook with provided synthetic, deidentified datasets.

Repository Contents
Module-4/
├── WISER_M4_NLP_Semantics_Harmonization.ipynb
├── notes.csv
├── notes_data_dictionary.csv
├── encounters.csv
└── encounters_data_dictionary.csv

Google Colab Notebook

WISER_M4_NLP_Semantics_Harmonization.ipynb

The notebook provides a guided NLP workflow that includes:
Loading and reviewing the provided datasets
Deidentification checks
Text normalization
Named entity recognition (NER)
Concept linking
Terminology crosswalk development
Stigma auditing
FAIR-aligned export and documentation

The notebook is designed for Python 3.11. A CPU runtime is sufficient for the Foundational pathway; a GPU is optional for transformer-based activities in the Applied pathway.

Synthetic Datasets
notes.csv - Synthetic, deidentified clinical-text data used to practice normalization, NER, concept linking, and stigma auditing.
encounters.csv Optional synthetic encounter-level data that provides additional context for the clinical notes.

Data dictionaries are provided for both datasets to describe the included variables and their definitions.

Using the Module 4 Materials
Open the Google Colab notebook.
Run the setup and data-loading cells.
Load notes.csv and, when needed, encounters.csv.
Use the corresponding data dictionaries to review variable definitions.
Complete the activities for your assigned Foundational or Applied pathway.
Follow the notebook instructions to create and export the required learning artifacts.

Important Data Note
The datasets provided in this repository are synthetic and deidentified and contain no protected health information (PHI). Do not upload identifiable clinical data or PHI to this repository or substitute real clinical notes without appropriate institutional approvals and data protections.

Module Information
Estimated time: 90–110 minutes
Design Thinking phase: Prototype
Bloom level: Apply / Create
Prerequisites: Modules 1–3
