# Phase III — Fatigue Crack Growth Demonstration

Publication-held-out XGBoost demonstration using 196 experimental observations from DOI 10.1016/j.marstruc.2020.102881. This is grouped cross-validation, not independent external validation.

Open `phase3_github_one_run_demo_colab.ipynb` in Google Colab. The notebook downloads its input CSV and fold-specific trained model from the `data/` directory, verifies their SHA-256 hashes, and shows R², MAE, RMSE (natural-log target) and a measured-versus-predicted figure.

Model artifacts are provided for research demonstration purposes only. The dataset is already harmonized; the notebook does not perform arbitrary raw-publication ingestion.