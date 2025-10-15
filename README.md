# 🧠 MentalDisorder Classification with Azure AutoML

This project uses Azure Machine Learning Studio's AutoML to classify mental disorder data. The best-performing model was a VotingEnsemble, achieving strong accuracy and AUC scores across macro, micro, and weighted metrics.

## 🔍 Model Highlights
- **Best Model:** VotingEnsemble (LightGBM-based)
- **Accuracy:** 0.8033
- **AUC Macro:** 0.9576
- **AUC Micro:** 0.9421
- **AUC Weighted:** 0.9364
- **Training Time:** 12m 36.73s

## 📊 Performance Metrics
| Metric              | Value(s)                          |
|---------------------|-----------------------------------|
| Accuracy            | 0.8033 (best), 0.7722, 0.6978     |
| AUC Macro           | 0.9576                            |
| AUC Micro           | 0.9421                            |
| AUC Weighted        | 0.9364                            |
| Predicted Cost      | 0, 0.5, 0                         |
| Fit Times (s)       | 0.0287, 0.0152, 2                 |
| Iterations          | 0, 1, 2                           |
| Training Percent    | 100%                              |

## 📦 Inputs & Outputs
- **Input Data Asset:** `mental_disorders_dataset.csv`


## 🧪 Experiment Details
- **Run Name:** `calm_office_f1r43m67bb`
- **Experiment Name:** `MentalDisorder`
- **Job Type:** Automated ML
- **Task Type:** Classification
- **Featurization:** Auto
- **Preprocessing:** MaxAbsScaler
- **Algorithm Used:** VotingEnsemble
- **Created By:** Najum Ul Hassan

## 🚀 Deployment Status
- Model not yet registered or deployed

## 📁 Folder Structure
MentalDisorder-Classification/
├── model/
│   ├── model.pkl
│   ├── MLmodel
│   └── conda.yaml
├── python_env.yaml
└── requirements.txt
└── mental_disorders_dataset.csv
