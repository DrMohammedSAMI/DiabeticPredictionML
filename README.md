# DiabeticPredictionML
Diabetic Predication based on feature selection methods
This is PYTHON requirements for Machine Learning 
PYTHON VERSION 3.11.1
 (need install pandas, numpy, seaborn, matplotlib, bib and sklearn)

and this is need for feature selection process

(Feature impact ratio on system performances)
from sklearn import tree
features = X.columns.values # The name of each column
classes = ['0', '1', '2'] # The name of each class
for estimator in rfc.estimators_:
    print(estimator)
    plt.figure(figsize=(12,6))
    tree.plot_tree(estimator,
                   feature_names=features,
                   class_names=classes,
                   fontsize=8, 
                   filled=True, 
                   rounded=True)
    plt.show()

To cite this please refer to 
Sahar J. Mohammed, Ali S. Ahmed and Mohammed S. Mohammed, “Feature Minimization for Diabetic Disorders High Performances prediction system based on Random Forest Tree”. 2023
