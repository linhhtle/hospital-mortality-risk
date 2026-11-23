# Hospital Mortality Risk Prediction

Healthcare analytics | Python | Supervised machine learning

## Objective
Evaluate whether clinical admission information can help identify patients at elevated risk of in-hospital mortality.

## Data and approach
The academic analysis covers 14,845 admissions and compares logistic regression and random forest models through exploratory analysis, preprocessing and predictive modeling.

## Results
| Model | Reported AUROC |
| --- | ---: |
| Logistic regression | 0.825 |
| Random forest | 0.961 |

Random forest achieved higher discrimination in the reported analysis. AUROC does not establish clinical utility or performance at a specific decision threshold.

## Explore the analysis
- [Project notebook](BA889_Project.ipynb)

## Reproduction and limitations
Review the notebook for dependencies, input requirements and evaluation details. Obtain any required clinical data through authorized channels. This retrospective academic project is not a validated clinical decision tool; external validation, leakage checks, calibration and fairness assessment would be needed before deployment.
