## Machine-learning-based prediction of functional recovery in deep-pain-negative dogs after decompressive thoracolumbar hemilaminectomy for acute intervertebral disc extrusion
Overview
* This repository contains the code and trained XGBoost model for the above study.
* The open-access paper is available at [doi.org/10.1111/vsu.14250](https://doi.org/10.1111/vsu.14250)

Model

* The XGBoost classifier was trained on the dataset with Bayesian hyperparameter optimisation to predict postoperative ambulation recovery.
* Best XGBoost hyperparameters: {'learning_rate': 0.004835563568734652,
'max_depth': 6, 'n_estimators': 2284, 'min_child_weight': 3,
'subsample': 0.7718650742894587, 'colsample_bytree':
0.8734927796575177}

Permissions
* The open access of this model is granted for research purposes only. Any use of the model for clinical decision-making is not recommended. The sole responsibility of patient care remains that of the attending veterinarian, and we assume no responsibility or liability if this model is used outside of its intended scope.
* Contributions are welcome! If you'd like to improve the model or code, please open an issue or submit a pull request.
* Cite us at Low D, Stables S, Kondrotaite L, Garland B, Rutherford S. Machine-learning-based prediction of functional recovery in deep-pain-negative dogs after decompressive thoracolumbar hemilaminectomy for acute intervertebral disc extrusion. Vet Surg. 2025;1-10. doi.org/10.1111/vsu.14250

Files in this Repository

📂 model.joblib – Serialized trained model

📂 target_encoders.joblib – Encoders for categorical variables

📂 training_params.json – Model hyperparameters

📂 MIT LICENSE - CC Attributions 4.0 Open Source License

📂 README.md – This documentation
