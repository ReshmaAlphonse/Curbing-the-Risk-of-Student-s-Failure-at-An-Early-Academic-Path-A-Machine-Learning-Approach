# Curbing-the-Risk-of-Student-s-Failure-at-An-Early-Academic-Path-A-Machine-Learning-Approach

Utilizing selected Machine Learning (ML) techniques to identify students at risk of failure
at an early point of their academic career so that support mechanisms can be put in place, this
effort intends to contribute to the reduction of academic failure in higher education. A student
record dataset was retrieved from UC Irvine Machine Learning Repository portal which
contained certain students’ information about courses enrolled at different courses (agronomy,
design, education, nursing, journalism, management, social service, and technologies) at the
end of their first and second semesters at a higher education institution. The issue is presented
as a three-category (Dropout, Enrolled, and Graduate) classification task with a significant
bias in favor of one of the classes. Stratified sampling was performed due to imbalance in
the classification target, and grid search 10-fold cross-validation hyperparameter tuning on
Random Forest (RF), Support Vector Machine (SVM), and K-Nearest Neighbor (KNN) ML
algorithms further boosted the prediction accuracy of the test samples. The results shows
that the RF improved models (from the three parameters configuration) obtained accuracy of
0.76, 0.75, and 0.75, while SVM and KNN resulted to 0.757 and 0.618, respectively. Overall,
RF outperformed other algorithms with or without the parameters been tuned.
