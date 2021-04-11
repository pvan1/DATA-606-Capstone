# DATA-606-Capstone
Repository for DataScience MPS Capstone project

This notebook is updated periodically as work progresses, please make sure you have the newest version.

capstone-phase1.ipynb loads the data set and performs exploratory analysis and feature selection in preparation for machine learning.

capstone-phase2.ipynb begins the exploration of ML modeling, after loading the data and apply transformations identified in phase 1.

-- The decision was made to split the exploration of different models into separate notebooks to avoid the notebook becoming too long.

capstone-phase2-svm.ipynb continues from capstone-phase2.ipynb with the exploration of SVM models.

capstone-phase2-randforest.ipynb contains exploration of Random Forest classifiers.

-- My local system is running on an AMD Phenom II X6 1090T processor, which does not support AVX instructions.
For that reason the exploration of Artificial Neural Networks using Tensorflow will be carried out in Google Colab Notebooks.
Those notebooks are uploaded here.

capstone_phase2_ann.ipynb contains the exploration of ANN classifiers, focusing mainly on hyper-parameter tuning and evaluation of a network using the optimal feature subset identified by the Random Forest classifier.

capstone_phase2_ann2.ipynb contains hyper-parameter tuning and evaluation of a network using the five (5) previously identified feature subsets, for direct comparison to the traditional ML models used.
