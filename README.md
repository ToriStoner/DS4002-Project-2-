# README

## Contents of the Repository
This repository contains a comprehensive analysis aimed at predicting crime rates in Los Angeles from 2020 to 2024, using both time series models (ARIMA, SARIMA) and machine learning models (Random Forest). The goal of this analysis is to explore how seasonal fluctuations, areas of high crime, and significant cultural events impact crime rates and to provide policymakers, activists, tourists, and residents with valuable insights.

- **Data Preprocessing**: Cleaning and structuring the dataset for analysis.
- **Time Series Analysis**: ARIMA and SARIMA models to explore trends and seasonality in crime data.
- **Predictive Modeling**: Random Forest regression to predict future crime rates based on multiple variables.
- **Visualizations**: Graphs for comparing predicted and actual crime rates, as well as feature importance in the predictive model.
  
## Section 1: Software and Platform

- **Software Used**: 
  - Software: Google CoPython 3.x
- **Add-on Packages**: 
  - `pandas` (for data manipulation)
  - `numpy` (for numerical operations)
  - `matplotlib` (for plotting)
  - `folium` (for geographic maps)
  - `seaborn` (for advanced visualizations)
  - `scikit-learn` (for Random Forest and metrics)
  - `statsmodels` (for ARIMA and SARIMA models)
- **Platform**: This project was developed and tested on both **Windows** and **Mac** platforms.

---

## Section 2: Project Structure

Below is the tree structure of the project repository:

```
├── DATA/
│   ├── Data Appendix            # Appendix for all text, tables, figures, and statistics we created
│   ├── Full Dataset            # Raw crime dataset for Los Angeles
├── OUTPUTS/
│   ├── List of .png            # List of .png files of our EDA & Analysis
├── SCRIPTS/
│   ├── Project_2.ipynb         # Our main group Colab Notebook for all code
├── References/
│   ├── DS4002 Project 2 References   # Folder containing all References in IEEE Citation
├── LICENSE                     # MIT License
├── README.md                     # Overview of the repository and instructions
```

---

## Section 3: Instructions for Reproducing Results

To reproduce the results of the analysis, follow the step-by-step instructions below:

### Step 1: Set up the environment
- Install Python 3.12.6.
   - Install necessary packages using pip:
     ```
     pip install pandas numpy matplotlib seaborn scikit-learn folium statsmodels
     ```
     
### Step 2: Download dataset
   - Place the `Crime Data.csv` file in the `data/` folder.

### Step 3: Data Preprocessing, Time Series Analysis (ARIMA and SARIMA), and Predictive Modeling (Random Forest)
- Run the Jupyter notebook `SCRIPTS/Project_2.ipynb` to clean and preprocess the raw crime dataset (`Crime Data.csv`).
  - This first step will include data filtering, handling missing values, and extracting relevant features.
  - Below, you will continue to run the code working toward running the ARIMA and SARIMA models that will analyze the seasonality and general trends of crime rates.
  - Lastly, there is our Random Forest code that we used to predict crime rates based on location, date, and other relevant features.

### Step 4: Interpreting Results
Use the visualizations and feature importance plots after each section to gain insights into:
- How seasonal fluctuations impact crime rates (via SARIMA)
- Which factors (e.g., location, time of year) are most predictive of crime rates (via Random Forest)

---


