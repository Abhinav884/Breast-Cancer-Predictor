# Breast cancer diagnosis predictor

## Overview

The Breast Cancer Diagnosis Predictor is a machine learning-powered web application designed to assist in the early detection of breast cancer. Based on diagnostic measurements, the app predicts whether a breast mass is benign or malignant and displays the results with clear visualizations. It provides a visual representation of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant.

## Features

- Manual input of cell measurement data
- Radar chart visualization
- Real-time prediction with probability score
- Export functionality for analysis

## Dataset

This project uses the publicly available [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) from Kaggle.


Note: This project was developed for educational purposes only and is not approved for clinical or professional medical use.

## Installation

You can run this app in a virtual environment. Here's a quick guide:

```bash
conda create -n breast-cancer-diagnosis python=3.10 
```

Then, activate the environment:

```bash
conda activate breast-cancer-diagnosis
```

To install the required packages, run:

```bash
pip install -r requirements.txt
```

This will install all the necessary dependencies, including Streamlit, OpenCV, and scikit-image.

## Usage
To start the app, simply run the following command:

```bash
streamlit run app/main.py
```

This will launch the app in your default web browser. You can then upload an image of cells to analyze and adjust the various settings to customize the analysis. Once you are satisfied with the results, you can export the measurements to a CSV file for further analysis.
