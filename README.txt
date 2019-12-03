# Chornic_kidney_disease_AZ

ABSTRACT

Chronic kidney disease (CKD) is a global public health issue. The early stage of CKD is prevalent, however, the proportion of patients who progress to end-stage renal disease (ESRD) is small. It is meaningful and vital to identify those patients and give a signal to doctors for treatment at early stage.

We used the data source of TriNetX which is an US real-time health database. Data regarding various predictors such as demographic, lab, comorbidities and meditation treatment. In the study, we attempted different types of machine learning algorithms (random forest, gradient Boosting and logistic regression classifier) compared performances by precision, recall, f1-score, AUC and calibration.

The AUC of random forest, gradient boosting and logistic regression algorithms are similar which are 0.74, 0.71 and 0.71 respectively. Gradient boosting is slightly better than other two algorithms. Moreover, we identified and discussed top 15 predictors that lead to CKD fast progression. Lastly, we selected gradient boosting algorithm and set the cut-off value to 0.2, the sensitivity and specificity of the gradient boosting algorithm are 0.74 and 0.61 respectively. Within this algorithm 4594 (6177) fast CKD progressors and 29179 (47680) slow CKD progressors can be identified.
