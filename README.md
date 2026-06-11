# EDS 232 Machine Learning Kaggle Competition
## Predicting Dissolved Inorganic Carbon (DIC) in California Coastal Waters
Authors: Megan Hessel, Richard Montes-Lemus, Sofia Rodas, and Peter Vitale.

## Background
**This notebook tests several machine learning models to find the one that best 
predicts dissolved inorganic carbon (DIC) concentration (umol/kg) in seawater 
samples collected off the California coast.**

**The data come from the California Cooperative Oceanic Fisheries Investigations 
(CalCOFI), one of the longest-running ocean monitoring programs in the world. Each 
row corresponds to a single water sample, described by total alkalinity (TA) 
(umol/kg), seawater practical salinity (ppt(PSS78)), seawater temperature (°C), 
depth (m), and dissolved inorganic carbon (DIC) (umol/kg).**

## Models Tested
- Ridge Regression
- Lasso Regression
- Principal Component Regression (PCR)
- Random Forest
- XGBoost
- Support Vector Regression (RBF and Polynomial kernels)
- LightGBM

## Best Model
LightGBM achieved the lowest test MSE of 211.01 and was used as our final Kaggle submission.

## Repository Structure
- `all_models.ipynb` — final submission notebook with all models
- `data/` — training and test data from CalCOFI
- `submission.csv` — final Kaggle submission file

## Final Submission
`all_models.ipynb`

# References

GeeksforGeeks. (2025). Lightgbm tree parameters. Retrieved from https://www.geeksforgeeks.org/machine-learning/lightgbm-tree-parameters/ 

GeeksforGeeks. (2025). Regression using lightgbm. Retrieved from https://www.geeksforgeeks.org/machine-learning/regression-using-lightgbm/ 

Shekarreddy. (2024). RandomizedSearchCV. Retrieved from https://medium.com/@shekar3reddy4/randomizedsearchcv-3fac09d6927e 

Zouinina, S. (2024). A deep dive into LIGHTGBM: How to choose and tune parameters. Retrieved from https://medium.com/@sarahzouinina/a-deep-dive-into-lightgbm-how-to-choose-and-tune-parameters-7c584945842e 
