# WBA ANALYSIS: PREDICTING CONDUCTIVE HEARING LOSS


## Overview

Conductive hearing loss is a prevalent health concern in young children. In my Master's degree capstone project, I applied the Support Vector Machine (SVM) to predict conductive hearing loss using wideband absorbance (WBA) data and narrow down key frequencies for the prediction.


## Methodology

The research was conducted using Python and Jupyter Notebook, using the following libraries:
- NumPy and Pandas, for data cleaning and transformation
- Seaborn and Matplotlib, for data visualisations
- imblearn, for oversampling techniques (SMOTE, SMOTEENN, and SMOTETomek)
- Scikit-learn, for embedded feature selection and model training


## Results

The final SVM model effectively distinguished between normal and hearing-impaired ears by focusing on absorbance levels within the frequency range of 1000 to 2000 Hz. This frequency range provides a smaller, more focused area for audiologists to examine on the WBA chart and serves as a starting point for future studies.
