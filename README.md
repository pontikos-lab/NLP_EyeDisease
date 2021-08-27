# NLP BERT
## Structure Diagram of this study:
![map](https://user-images.githubusercontent.com/88321656/131142342-d007fabe-ff6f-4503-bbde-d5b68a8d37b7.jpeg)

## Dataset:
Moorfields Eye Hospital (MEH) unstructured free-text EHR data<br/>
MIMIC-III unstructured free-text EHR data<br/>
## Natural Language Processing (NLP) pipeline:
CogStack SemEHR: https://github.com/CogStack/CogStack-SemEHR
## Object:
Use binary classification for internal and external validation to determine whether the mentions identified by CogStack-SemEHR is true or not using BERT model.
## Process:
1. Preprocess of the dataset
    MIMIC-III: https://github.com/pontikos-lab/NLP_BERT/blob/main/MIMIC-III_preprocessing.ipynb
    MEH: https://github.com/pontikos-lab/NLP_BERT/blob/main/MEH_preprocessing.ipynb
2. Internal validation of BERT
    MIMIC-III: https://github.com/pontikos-lab/NLP_BERT/blob/main/MIMIC-III_BERT.ipynb
    MEH: https://github.com/pontikos-lab/NLP_BERT/blob/main/MEH_BERT.ipynb
3. External validation of BERT
    MIMIC-III use MEH for validation: https://github.com/pontikos-lab/NLP_BERT/blob/main/MIMIC-III_BERT_MEH_validation.ipynb
