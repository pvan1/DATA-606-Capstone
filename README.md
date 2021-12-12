# DATA-606-Capstone
Repository for DataScience MPS Capstone project

The project site can be found at:  
https://sites.google.com/umbc.edu/data606/home/previous-semesters/spring-21-section-1/phillip-vandenberghe  
archive:  
https://web.archive.org/web/20211212161809/https://sites.google.com/umbc.edu/data606/home/previous-semesters/spring-21-section-1/phillip-vandenberghe

This notebook is updated periodically as work progresses, please make sure you have the newest version.

capstone-phase1.ipynb loads the data set and performs exploratory analysis and feature selection in preparation for machine learning.

capstone-phase2.ipynb begins the exploration of ML modeling, after loading the data and apply transformations identified in phase 1. Predictions and classification reports on the test set for GNB and KNN models are found at the end of the notebook.  Plots showing metrics of all models are found in capstone_phase2_ann_plot_results.ipynb

-- The decision was made to split the exploration of different models into separate notebooks to avoid the notebook becoming too long.

capstone-phase2-svm.ipynb continues from capstone-phase2.ipynb with the exploration of SVM models. Predictions and classification reports on the test set for the Linear SVC models are found at the end of the notebook.  Plots showing metrics of all models are found in capstone_phase2_ann_plot_results.ipynb

capstone-phase2-randforest.ipynb contains exploration of Random Forest classifiers. Predictions and classification reports on the test set for Random Forest models are found at the end of the notebook.  Plots showing metrics of all models are found in capstone_phase2_ann_plot_results.ipynb

-- My local system is running on an AMD Phenom II X6 1090T processor, which does not support AVX instructions.
For that reason the exploration of Artificial Neural Networks using Tensorflow will be carried out in Google Colab Notebooks.
Those notebooks are uploaded here.

capstone_phase2_ann.ipynb contains the exploration of ANN classifiers, focusing mainly on hyper-parameter tuning and evaluation of a network using the optimal feature subset identified by the Random Forest classifier. Predictions and classification reports on the test set for ANN models using the Random Forest optimum features are found at the end of the notebook.  Plots showing metrics of all models are found in capstone_phase2_ann_plot_results.ipynb

capstone_phase2_ann_2.ipynb contains hyper-parameter tuning and evaluation of a network using the five (5) previously identified feature subsets, for direct comparison to the traditional ML models used. Predictions and classification reports on the test set for the ANN models using the 5 feature subsets are found at the end of the notebook.  Plots showing metrics of all models are found in capstone_phase2_ann_plot_results.ipynb

capstone_phase2_ann_plot_results.ipynb loads classification reports from the tests conducted in capstone_phase2_ann.ipynb and capstone_phase2_ann_2.ipynb and plots them on the same axes for comparison. Also loads classification reports for final test predictions of all trained models and plots them on the same axis for comparison.  Standard scaled confusion matrices for final test predictions on all ANN models are also generated.
