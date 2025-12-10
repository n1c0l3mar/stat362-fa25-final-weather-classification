# Weather Image Classification
### Stats 362 - Fall 2025
Team Members: Isabella Toth, Sana Nanlawala, Nicole Marcatoma 

## Introduction
This project focuses on building a deep learning model to classify weather conditions from images. Our goal is to accurately recognize different weather types by training a CNN-based model on a labeled image dataset. Throughout the process, we performed data preprocessing, exploratory analysis, and iterated through multiple model attempts to improve performance and generalization.

## Dataset 
We use the Weather Dataset from Kaggle, which contains a large collection of labeled weather images spanning multiple conditions. This dataset provides enough variation to train, validate, and evaluate our model effectively, making it well-suited for image-based weather classification tasks.

Link to dataset: [Weather Dataset (Kaggle)](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset)

## Directory 
### Baseline Models 
- `preliminary_model.ipynb` - A simple baseline CNN trained on smaller images to establish an initial performance benchmark.
- `baseline_model.ipynb` - Improved baseline model with cleaner training structure, extended training, and slight tuning to better stabilize learning. Used to further enhance intermediate, final models. 
  
### Interim Report
- `final_interim_report.html` - A milestone progress report covering data exploration, modeling attempts, results, and next steps.

### Model Iterations
- `model_attempt2.ipynb` - Second attempt where performance was improved by increasing image size to 128×128, adding data augmentation, BatchNorm, Dropout, learning-rate scheduling, and early stopping. 
- `model_attempt3.ipynb` - Third attempt scaling images to 224×224 (ResNet input size), reducing augmentation, introducing class-weighted loss to address imbalance, and continuing early stopping.

### Final Model 
- `final_model.ipynb` - Final model using ResNet50 with improved training strategy and class balancing.

## Key Results
Summary of key results here "You may reuse plots or metrics from your final presentation slides." 

## Notes on Reproducability
- Dataset can be accessed here, as it is too large over Github [Weather Dataset (Kaggle)](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset)
- Pyproject.toml has dependencies and python requirements listed
- GPU is preferred over CPU to run models more efficiently
