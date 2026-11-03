# Week 6 — Integrative Capstone Project

## Objective
Integrate the previous five weeks into a complete data science workflow, from data acquisition to exploratory analysis, segmentation, predictive modelling, deep learning and strategic recommendations.

## Files
- `YuvaIntern3_week6.ipynb` — executed integrated capstone notebook.
- `Week6_Integrated_Capstone_Report.docx` — final integrated report.

## Integrated Components
1. UCI dataset acquisition and data-quality audit.
2. Cleaning and preprocessing, including unknown categories and the `pdays = -1` sentinel.
3. EDA of customer profiles and campaign outcomes.
4. K-Means segmentation and cluster profiling.
5. Logistic Regression and Random Forest subscription prediction.
6. TensorFlow/Keras neural network.
7. Evaluation, limitations and responsible business recommendations.

## Key Design Principles
- Clustering is descriptive; it excludes target `y`.
- Prediction uses pre-call features and excludes `duration`.
- Model evaluation considers precision, recall, F1, ROC-AUC and PR-AUC because the target is imbalanced.
- Recommendations are cautious and do not treat historical associations as causal evidence.

## Important Note
The capstone includes its own integrated clustering run. Its clustering configuration should be distinguished from the dedicated Week 3 five-cluster experiment.

## Re-running
Open the notebook in Google Colab and select **Runtime → Run all**. Review the generated tables and figures before final submission.
