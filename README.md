# Shipment Delay Insight

## Project Overview
Shipment Delay Insight is a data analysis and machine learning project based on a logistics scenario involving TransGlobe Logistics Services. The project analyzes shipment delivery patterns, identifies factors associated with delays, and aims to predict whether a shipment may be delayed.

## Objectives
- Analyze historical shipment delivery data.
- Clean and preprocess multiple datasets.
- Explore delay patterns across routes, carriers, weather conditions, shipment types, and dispatch periods.
- Build a machine learning model to classify shipments as delayed or not delayed.
- Provide insights to support better shipment planning and delivery management.

## Project Structure

```text
shipment-delay-insight/
├── code/
│   └── Shipment_Delay_Insight.ipynb
├── dataset/
│   ├── shipments.csv
│   ├── routes.csv
│   ├── carriers.csv
│   ├── events.csv
│   └── weather.csv
├── README.md
└── requirements.txt
```

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Workflow
1. Load and inspect the datasets.
2. Check for missing values, duplicates, and invalid records.
3. Clean and preprocess the data.
4. Combine shipment, route, carrier, event, and weather information.
5. Calculate delivery delay days and create the target variable.
6. Perform Exploratory Data Analysis (EDA) and visualize delay patterns.
7. Train and evaluate a classification model.
8. Interpret the results and suggest improvements to shipment planning.

## Machine Learning Approach
The intended algorithm is the Random Forest Classifier.

The target variable is `delayed`:
- `1` — Shipment delivered late.
- `0` — Shipment delivered on time or early.

Model performance can be evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

## Expected Outcomes
- Understand historical shipment delay patterns.
- Compare observed delay rates across different shipment factors.
- Identify potential areas for operational improvement.
- Estimate delay risk for new shipments after model training and evaluation.

## Dataset Information
The repository contains five CSV datasets covering shipments, routes, carriers, shipment events, and weather conditions. These are synthetic practice datasets created for project development and are not verified real company records.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Update the CSV file paths to match the `dataset/` folder.
5. Run the notebook cells in order.

## Author
Nanditaa P.S.

## Note
This project is developed for educational and skill-based assessment purposes.