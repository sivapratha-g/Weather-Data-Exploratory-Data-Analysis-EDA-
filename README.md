# Weather Data Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Australia Weather Dataset using Python.

The main objective is to understand weather data, identify missing values, clean the dataset, and explore temperature and rainfall patterns through data visualization.

## Objectives

- Understand the structure of the weather dataset.
- Identify missing values and duplicate records.
- Clean the dataset using suitable techniques.
- Analyze numerical and categorical columns.
- Visualize weather patterns using histograms.
- Understand the distribution of temperature and rainfall.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

**Dataset name:** Australia Weather Dataset (`weatherAUS.csv`)

The dataset contains weather-related information, including:

- Location
- Minimum Temperature
- Maximum Temperature
- Rainfall
- Sunshine
- Humidity
- Wind Speed
- Atmospheric Pressure
- Rain Today
- Rain Tomorrow

**Note:** The dataset file must be added separately to the repository if you want others to run the notebook. Include its source and check its usage terms before uploading it.

## Project Workflow

### 1. Importing Libraries

Imported Pandas, NumPy, Matplotlib, and Seaborn for data analysis and visualization.

### 2. Loading the Dataset

Loaded the Australia weather dataset using Pandas.

### 3. Data Exploration

- Displayed the first few rows.
- Checked dataset shape and column names.
- Examined data types and statistical summaries.
- Checked missing values and duplicate records.
- Explored unique values and label distributions.

### 4. Data Cleaning

- Removed rows where `RainTomorrow` was missing.
- Filled numerical missing values using the median.
- Filled categorical missing values using the mode.
- Checked missing values after cleaning.

### 5. Data Visualization

Created histograms to understand the distributions of:

- Maximum Temperature
- Minimum Temperature
- Rainfall

## Key Observations

- Maximum temperature has a single peak around 21°C–22°C.
- Minimum temperature has a single peak around 11°C–13°C.
- Most rainfall observations are low, while a smaller number of days have heavy rainfall.
- The median is a useful measure for summarizing rainfall because of its distribution.

## How to Run the Project

1. Clone or download this repository.
2. Install the required libraries.
3. Make sure `weatherAUS.csv` is available in the project folder.
4. Open `weather_EDAminipro1.ipynb` using Jupyter Notebook.
5. Run the notebook cells.

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Future Enhancements

- Perform correlation analysis.
- Create additional weather visualizations.
- Analyze rainfall patterns by location.
- Explore relationships between humidity, temperature, and rainfall.
- Build a machine learning model to predict rainfall.

## Conclusion

This project demonstrates the process of exploratory data analysis, including data exploration, data cleaning, handling missing values, and visualization. It helps develop a better understanding of weather data using Python.

## Author

Sivapratha G

Python | Data Analysis | Exploratory Data Analysis
