# Laser powder bed fusion dataset for relative density prediction of commercial metallic alloys
This repository contains the dataset and code for predicting relative density of metallic alloys produced by L-PBF.

# Dataset
The dataset comprises 1,579 observations, and it is organized in such a way that the first ten columns are the inputs (i.e., printing conditions, material, shielding gas, printed geometry, etc.), and the last column is the relative density expressed in percent. The dataset is provided in Excel format in the Harvard Dataverse repository:

La Fé-Perdomo, I., Barrionuevo, G. O. & Ramos-Grez, J. A. A dataset for modeling and optimizing the relative density of metallic alloys in laser-based powder bed fusion. Harv. Dataverse https://doi.org/10.7910/DVN/VPBQK8 (2024)

# Models
The following models are implemented and included in this repository:

XGBRegressor: hyperparameters for XGBRegressor: {'learning_rate': 0.01, 'max_depth': 5, 'n_estimators': 400}

RandomForestRegressor: hyperparameters for RandomForestRegressor: {'bootstrap': False, 'max_depth': 30, 'min_samples_leaf': 2, 'min_samples_split': 2, 'n_estimators': 200}

# Usage: 
All files can be opened and edited using Jupyter or similar editing software. After downloading from Harv. Dataverse, replace the file paths in the code with the correct locations. The code can then be run directly. Note that you will need to manually install any packages not already installed during the import step.


