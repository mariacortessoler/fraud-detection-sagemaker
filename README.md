<h1>Fraud detection on SageMaker and exploratory analysis examples</h1>

| Owners | Maria Cortes |
| ------ | ------ |
| Date| July, 2020 |

<h2>Objective</h2>

This repository includes notebooks on exploratory analysis and anomaly detection

```
fraud-detection-sagemaker/
├── README.md          <- This document
├── requirements.txt <- Text file with Python libraries to install
├── notebooks
│   ├── 1. Análisis exploratorio.ipynb     <- Exploratory analysis for various frequent types of data
│   ├── 2. PCA análisis exploratorio.ipynb   <- Exploratory analysis of continuous variables using PCA
│   ├── 2. Random Cut Forest SageMaker.ipynb   <- Guidance on training a Random Cut forest anomaly detection model, and creating a SageMaker endpoint
├── data
│   ├── creditcards.csv <- Mock data on credit card transactions for the notebooks
``` 