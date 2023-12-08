# CMMC-Model  
This is the code for 'Using Active Learning for the Computational Design of Polymer Molecular Weight Distributions'  
## package
* python==3.7.11  
* numpy==1.21.6  
* pandas==1.3.4  
* scikit-learn==1.0.2  
* modal==0.4.1
* We suggest that you can install these packages by pip.

## CMMC Model
We provide two different versions CMMC model. CMMC only used Mn and PDI as the output, and the training data are mode0_data.csv and mode1_data.csv. In order to describe MWD more accurately, we added Skewness and Kurtosis to describe MWD in CMMC_v1, and the traning data for CMMC_V1 is data_final.xlsx.

## SHAP
We also provide the code for SHAP Analysis, you can find it in SHAP_xgb.ipynb.

## Note
1. Xgboost model performs better than random forest model when the Skewness and Kurtosis are added to describe the MWD. So we choose Xgboost model in CMMC_v1 and random forest model in CMMC.
