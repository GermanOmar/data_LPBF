# Laser powder bed fusion dataset for relative density prediction of commercial metallic alloys
Laser-based powder bed fusion (L-PBF) technology stands out for its ability to create complex, high-performance parts, optimizing design freedom and material efficiency. Despite technical and financial challenges, it is attractive to industries where performance, weight reduction, and customization are critical. In L-PBF, relative density (RD) is a key factor that directly impacts the mechanical properties and overall quality of printed parts. However, predicting RD is a complex and costly task due to the numerous factors involved. This study addresses this need by creating a large-scale dataset for RD prediction in L-PBF, consisting of 1579 samples of commercial alloys from the literature. It includes printing conditions and other crucial inputs like protective atmosphere, powder size distribution, and part geometry. This dataset offers a valuable resource for researchers to benchmark their results, better understand key factors influencing RD, and validate models or explore new machine-learning approaches tailored to L-PBF.

Barrionuevo, G.O., La Fé-Perdomo, I. & Ramos-Grez, J.A. Laser powder bed fusion dataset for relative density prediction of commercial metallic alloys. Sci Data 12, 375 (2025). https://doi.org/10.1038/s41597-025-04576-x

# Dataset
The dataset comprises 1579 observations, and it is organized in such a way that the first eleven columns are the inputs (i.e., printing conditions, material, shielding gas, printed geometry, etc.), and the last column is the relative density expressed in percent. The dataset is provided in Excel format in the Harvard Dataverse repository:

La Fé-Perdomo, I., Barrionuevo, G. O. & Ramos-Grez, J. A. A dataset for modeling and optimizing the relative density of metallic alloys in laser-based powder bed fusion. Harv. Dataverse https://doi.org/10.7910/DVN/VPBQK8 (2024)

# Models
The following models are implemented and included in this repository:

XGBRegressor: hyperparameters for XGBRegressor: {'learning_rate': 0.01, 'max_depth': 5, 'n_estimators': 400}

RandomForestRegressor: hyperparameters for RandomForestRegressor: {'bootstrap': False, 'max_depth': 30, 'min_samples_leaf': 2, 'min_samples_split': 2, 'n_estimators': 200}

# Usage: 
All files can be opened and edited using Jupyter or similar editing software. After downloading from Harv. Dataverse, replace the file paths in the code with the correct locations. The code can then be run directly. Note that you will need to manually install any packages not already installed during the import step.


