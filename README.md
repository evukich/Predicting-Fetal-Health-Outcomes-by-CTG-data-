# A proposal for an automated machine learning model in Maternal-Fetal Healthcare utilizing common Cardiotocographic data (fetal monitor) to predict fetal health outcomes. 

Python Notebooks demonstrate my data cleansing process, strategy and intent to build and test machine learning models, and final comparison of various unsupervised machine learning models ( Logistic Regression, Decision Tree Classifiers, K Nearest Neighbors, Light GBM). 

Models were hypertuned to provide highly accurate results. The highest performing model achieved 95% accuracy in predicting the fetal health outcome as 'Normal', 'Suspect', or 'Pathological'. XG Boost shows a 95% accuracy and would be an ideal model to deploy in an automated model in the healthcare setting. 

Please see comparison of models and accuracy scores below: 

Dummy
0.6370510396975425

Logistic Regression
0.9017013232514177

Logistic Regression3 
0.8960302457466919

KNN
0.9300567107750473

RF
0.9489603024574669

Decision Tree
0.9206049149338374

Decision Tree 2
0.9206049149338374

Decision Tree 3
0.9376181474480151

LGBM
0.9489603024574669

XGB
0.9546313799621928
