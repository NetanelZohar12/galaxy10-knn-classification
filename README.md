# Galaxy10 DECaLS Binary Classification with KNN

Machine Learning assignment for binary galaxy morphology classification.

## Task

Classify galaxy images into:

- Round Smooth Galaxy
- Barred Spiral Galaxy

## Model

K-Nearest Neighbors (KNN)

Final configuration:

- Feature Engineering: HOG + color histograms + morphology statistics
- Scaler: RobustScaler
- k: 10
- Voting: distance weighted
- Distance: Cosine

## Final Results

- 5-Fold CV Macro-F1: 0.9049
- Validation Macro-F1: 0.8966
- Test Macro-F1: 0.8903

## Main Notebook

`galaxy10_decals_knn_assignment_FINAL_EN_READY.ipynb`

The notebook is saved with all execution outputs and visualizations.

## Dataset

Galaxy10 DECaLS Binary Classification Dataset  
Kaggle: [insert dataset link]

The dataset itself is not stored in this repository because of its size.

## Environment

See:

`requirements_galaxy10.txt`
