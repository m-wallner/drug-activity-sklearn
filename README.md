# Drug Activity

The aim of this project was to predict the biological activity or toxicity of a drug or a molecule purely based on its chemical structure. A dataset of molecules in SMILES format was given (provided by the JKU Institute of Machine Learning, not available in this repository), together with activities of these molecules related to 11 different applications, and the goal was to train a machine learning model to predict the activities of new molecules based on the selected model.

First, the molecules in SMILES format are transferred into sparse Morgan fingerprints of length 2048, then various classic machine learning models (Support Vector Regression, AdaBoost and Random Forest) are trained and tested on the validation set. SVR showed the best results in terms of mean ROC AUC scores on the 11 different tasks.
