# Project roi-prediction
This is the README for ROI Prediction Project


## Folders
- datasets: raw datasets from the external sources.
- datasets_filtered: datasets that has been formatted to fit with the project

## Programs
- **filter_datasets**: filter the raw datasets to the one used by the other programs and format the naming convention
- **preprocessing**: preprocess the dataset by droping features and rows that are not needed, imputation and interpolation of missing data, and calculate the ROI based on ZHVI data.
- **model**: set up of the model and standardize the dataset and train the model.
- **test_model**: test the model by giving test input and other features.

## How to run
Starting from the raw datasets.

1. Run the filter_datasets
2. Run the preprocessing
3. Run the model. You can choose to turn on the attention layer here. The default is off.
4. Run test_model if applicable.