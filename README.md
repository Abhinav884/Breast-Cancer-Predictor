# Breast Cancer Predictor

## Overview

The Breast Cancer Predictor is a machine learning-powered web application designed to assist in the early detection of breast cancer. Based on diagnostic measurements, the app predicts whether a breast mass is benign or malignant and displays the results with clear visualizations of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant.

## Features

- Manual input of cell measurement data
- Radar chart visualization
- Real-time prediction with probability score
- Export functionality for analysis

## Dataset

This project uses the publicly available [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) from Kaggle.


Note: This project was developed for educational purposes only and is not approved for clinical or professional medical use.

## Installation & SetUp

You can run this app in a virtual environment. Here's a quick guide:

```bash
conda create -n breast-cancer-diagnosis python=3.10 
```

Then, activate the environment:

```bash
conda activate breast-cancer-diagnosis
```

To install the required packages:

```bash
pip install -r requirements.txt
```

## Usage
To launch the app, simply run the following command:

```bash
streamlit run app/main.py
```

Once launched, the app will open automatically in your default web browser.