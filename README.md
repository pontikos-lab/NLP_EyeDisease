# Natural Language Processing for Extraction of Phenotypes for Inherited Retinal Disease from Electronic Health Records
## Structure Diagram of this study:
<!-- ![map](https://user-images.githubusercontent.com/88321656/131142342-d007fabe-ff6f-4503-bbde-d5b68a8d37b7.jpeg) -->
![Concept map](https://user-images.githubusercontent.com/88321656/131233618-3777b9d9-c80a-404f-9fec-bcb0aea37f1f.jpeg)

## Dataset:
Moorfields Eye Hospital (MEH) unstructured free-text EHR data<br/>
MIMIC-III unstructured free-text EHR data<br/>
## Natural Language Processing (NLP) pipeline:
Using CogStack SemEHR to identify eye disease phenotype.<br/>
https://github.com/CogStack/CogStack-SemEHR
## Object:
Use binary classification for internal and external validation to determine whether the mentions identified by CogStack-SemEHR is true or not using BERT model.
## Process:
1. Preprocess of the dataset<br/>
    MIMIC-III: https://github.com/pontikos-lab/NLP_EyeDisease/blob/main/MIMIC-III_preprocessing.ipynb<br/>
    MEH: https://github.com/pontikos-lab/NLP_EyeDisease/blob/main/MEH_preprocessing.ipynb
2. Internal validation of BERT<br/>
    MIMIC-III: https://github.com/pontikos-lab/NLP_EyeDisease/blob/main/MIMIC-III_BERT.ipynb<br/>
    MEH: https://github.com/pontikos-lab/NLP_EyeDisease/blob/main/MEH_BERT.ipynb
3. External validation of BERT<br/>
    MIMIC-III use MEH for validation: https://github.com/pontikos-lab/NLP_EyeDisease/blob/main/MIMIC-III_bert_MEH_validation.ipynb
