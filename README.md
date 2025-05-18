<!-- Write a README for the project  -->

# Benin EDA Project

This project provides an exploratory data analysis (EDA) of solar and meteorological data for Benin (Malanville). The analysis focuses on data cleaning, outlier detection, missing value imputation, and visualization of key variables such as solar irradiance, temperature, wind, and humidity.

## Project Structure

- **notebooks/benin_eda.ipynb**: Main Jupyter notebook containing all analysis steps and visualizations.
- **data/**: Folder containing the raw and cleaned CSV data files.

## Main Steps

1. **Data Loading & Overview**
   - Loads the dataset and inspects its structure and missing values.

2. **Missing Value Handling**
   - Identifies columns with significant missing data.
   - Imputes missing values in key columns using the median.

3. **Outlier Detection & Removal**
   - Uses Z-score to flag and remove outliers from key columns.

4. **Data Export**
   - Saves the cleaned dataset for further analysis.

5. **Time Series Analysis**
   - Plots time series for solar and temperature variables.
   - Computes and visualizes monthly and hourly means.

6. **Wind & Distribution Analysis**
   - Creates a wind rose (radial bar plot) for wind speed and direction.
   - Plots histograms for GHI and wind speed.

7. **Temperature & Humidity Analysis**
   - Examines the relationship between relative humidity (RH), temperature (Tamb), and solar radiation (GHI) using scatter plots and correlation coefficients.

8. **Bubble Chart Visualization**
   - Visualizes GHI vs. Tamb with bubble size and color representing RH.

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scipy

Install dependencies with:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Usage

1. Place your raw data CSV in the `data/` folder.
2. Open and run the notebook `notebooks/benin_eda.ipynb` step by step.
3. The cleaned data will be saved as `data/benin-malanville_clean.csv`.

## Results

The notebook provides:
- Cleaned and preprocessed data ready for modeling or further analysis.
- Visual insights into the distribution and temporal patterns of solar and meteorological variables in Benin.
- Exploratory relationships between temperature, humidity, and solar radiation.

---

**Author:**  
Kifiya Week 0 Project Team

**License:**  
MIT License