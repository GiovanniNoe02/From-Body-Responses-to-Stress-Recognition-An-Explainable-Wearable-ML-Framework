# Stress Detection from Physiological Signals using WESAD

## Authors

* Francesco Volpi Ghirardini
* Giovanni Noè

## Project Overview

This repository contains the material developed for the *Big Data in Behavioural Psychology* course project.

The objective of the project is to investigate whether psychological stress can be reliably identified from physiological signals collected through wearable devices. Using the WESAD dataset, we combine physiological signal processing, machine learning, and explainable AI techniques to classify affective states and identify the most relevant physiological responses associated with stress.

## Repository Contents

* **Project.ipynb** – Jupyter Notebook containing the complete analysis pipeline, including data preprocessing, feature extraction, exploratory data analysis, machine learning classification, and explainability analysis.
* **Report.pdf** – Final project report.
* **Questionnaires_and_Scores.xlsx** (or equivalent file) – Processed questionnaire responses and computed psychological scores used for the validation of the experimental conditions.

## Dataset

The original physiological recordings are **not included** in this repository due to their size.

The WESAD dataset can be downloaded from Kaggle:

https://www.kaggle.com/datasets/orvile/wesad-wearable-stress-affect-detection-dataset

WESAD (Wearable Stress and Affect Detection) is a publicly available multimodal dataset containing physiological and motion signals collected from 15 participants during baseline, stress, and amusement conditions. It includes data from both chest-worn and wrist-worn sensors, as well as several psychological questionnaires used for experimental validation.

## Project Pipeline

1. Validation of the experimental protocol through questionnaire analysis.
2. Feature extraction from multimodal physiological signals.
3. Exploratory Data Analysis (EDA).
4. Random Forest classification of affective states.
5. Hyperparameter optimization using GridSearch Cross-Validation.
6. Model evaluation through Accuracy, Precision, Recall, F1-score, and Confusion Matrices.
7. Explainable Machine Learning using:

   * Mean Decrease in Impurity (MDI)
   * Permutation Feature Importance (PFI)

## References

* Schmidt, P., Reiss, A., Dürichen, R., Marberger, C., & Van Laerhoven, K. (2018). *Introducing WESAD: A Multimodal Dataset for Wearable Stress and Affect Detection*. ACM International Conference on Multimodal Interaction (ICMI).
* WESAD Dataset Documentation and README.
* Stress and stress responses: A narrative literature review from physiological mechanisms to intervention approaches.

## License

This repository is intended for academic and educational purposes. Please refer to the original WESAD dataset license and citation requirements when using the data.
