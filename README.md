# iso_forest_real_time
Matlab files for paper on unsupervised anomaly detection. Please consider citing the article if you find this useful: Khan, S., Liew, C. F., Yairi, T., & McWilliam, R. (2019). Unsupervised anomaly detection in unmanned aerial vehicles. Applied Soft Computing, 83, 105650.

# Data files:

Data.mat % aero engine data set

UAV_data.mat % UAV data for 9 variables

# iforest files:

IsolationEstimation.m

IsolationForest.m

IsolationTree.m

IsoMass.m

Measure_AUC.m

Result_iForest.m

run_iForest.m % main file. run this for computing scores

TreeNode_iForest.m

# Real-time iForest in simulink:

iso_forest_real_time.xls % requires functions from iforest files

# SVM/GMM/Mahal files:

Compare_3_methods.m % run before Plot_results.m

Plot_results.m
