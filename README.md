# natural-disaster-classification-lime-shap
K Akshitha (2024) published research explores natural disaster classification using machine learning.(plese do not copy)As the paper is copyrighted under IEEE


This study explores machine learning for classifying natural disasters. It compares Random Forest and XGBoost algorithms, optimizing their hyperparameters for better performance. Explainable AI (XAI) techniques, Lime and Shap, offer insights into XGBoost's decision-making process (72% accuracy). These techniques reveal key features like 'No Injuries' and 'Total Damages' that significantly impact XGBoost's predictions. Contribution graphs visually represent the importance of these features. XGBoost outperforms other algorithms, demonstrating its effectiveness in disaster classification. Importantly, the study highlights the value of XAI in boosting accuracy and fostering a deeper understanding of the model's choices. This not only improves model interpretability but also advances the field of disaster classification and opens doors for broader XAI applications.
This study explored using machine learning algorithms, specifically Random Forest and XGBoost, to classify natural disasters. The dataset contained 8,946 entries with 15 attributes (13 numerical, 2 categorical). Label encoding was used to convert categorical data to numerical values.

Machine Learning Performance:
Various algorithms were tested, with XGBoost achieving the highest accuracy (72%). Here's a breakdown:

Algorithm:Accuracy
Logistic Regression:	0.40
KNN:	0.47
Decision Tree (DT):	0.54
Random Forest (RF):	0.68
Support Vector Machine (SVM):	0.39
Gradient Boosting:	0.68
AdaBoost:	0.44
XGB Classifier:	0.72
CatBoost:	0.61
Random Search CV:	0.68

Hyperparameter Tuning:
Hyperparameter tuning for Random Forest identified optimal values for parameters like 'n_estimators', 'min_samples_split', 'max_features', and 'max_depth'. Both grid and random search were employed.
Explainable AI (XAI) for XGBoost:
To understand XGBoost's decision-making process, two Explainable AI (XAI) techniques, LIME and SHAP, were applied.
LIME: This method revealed key features impacting XGBoost predictions, such as "No Injured" and "Total Damages".
SHAP: This method calculated feature importance, with "No Injured" being the most significant factor. The importance of all features is shown in a table.
Contribution Graphs and Feature Importance:
These techniques utilize contribution graphs and feature importance plots to visualize the impact of different attributes on the model's predictions.
Conclusion:
This study demonstrates the effectiveness of XGBoost (72% accuracy) for natural disaster classification. XAI methods (LIME and SHAP) provide valuable insights into model behavior, highlighting crucial features like "No Injured" and "Total Damages". The importance of XAI for improving model interpretability and accuracy is emphasized.
Future Directions:
Further research can explore deeper integration of XAI techniques and expand the scope of disaster classification studies. Additionally, the study highlights the benefits of XGBoost, including handling missing values, parallel processing, and second-order optimization. This work paves the way for developing more trustworthy and transparent disaster classification models, fostering greater confidence in machine learning for disaster prediction.
Key Takeaways:
XGBoost outperforms other algorithms for natural disaster classification.
XAI techniques (LIME and SHAP) improve model interpretability.
"No Injured" and "Total Damages" are critical features for XGBoost.
XAI and machine learning offer valuable insights for disaster management.
Future research should explore deeper XAI integration and broader disaster studies.



