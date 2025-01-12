# SIC_COVID-19_DATA_ANALYSIS


# Covid-19 Data Analysis

This Jupyter Notebook analyzes COVID-19 data, providing insights into global and regional trends, case counts, and correlations.  The notebook leverages various libraries for data manipulation, visualization, and interactive mapping.

**Project Overview:**

This analysis addresses several critical aspects of the COVID-19 pandemic:

* **Data Acquisition and Preparation:** The project downloads COVID-19 datasets from Kaggle.  These datasets are then imported into Pandas DataFrames.  Essential cleaning steps, including handling missing values, are performed.
* **Descriptive Statistics:**  The notebook calculates and displays descriptive statistics (mean, median) for key metrics like confirmed cases, deaths, and recoveries. This provides a high-level understanding of the data distribution.
* **Data Visualization:**  This section utilizes various visualizations to effectively present the insights:
    * **Line Plots:**  Visualizes the trends in confirmed cases, deaths, recoveries, and active cases over time, highlighting pandemic progression.
    * **Stacked Bar Charts:**  Compares confirmed, deaths, recoveries, and active cases across the top 10 countries with the most active cases, enabling a visual comparison of pandemic impact.
    * **Interactive World Map:**  Provides an interactive map displaying COVID-19 statistics by country/region. Users can explore individual country data.
    * **Correlation Heatmap:**  Illustrates the relationships between deaths, confirmed cases, and recovered cases through a heatmap. This assists in understanding the correlation between these key metrics.
* **Relationship Exploration:**
    * **Confirmed vs. Deaths:** A line plot demonstrates the relationship between the number of confirmed cases and deaths over time, aiding in visualizing potential correlations.
    * **Confirmed vs. Recoveries:** A line plot explores the correlation between confirmed cases and the number of recoveries, helping understand the impact of confirmed cases on recovery rates.


**Prerequisites:**

This project requires the following software and libraries:

* **Python 3:** Ensure Python 3 is installed.
* **Necessary Libraries:**
    ```bash
    pip install pandas numpy seaborn matplotlib plotly matplotx geopandas kaggle folium
    ```

**Setup:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/AdityaAjithKumar/SIC_COVID-19_DATA_ANALYSIS
   ```

2. **Install Libraries:**
   Run the following command to install all required libraries.
   ```bash
   pip install pandas numpy seaborn matplotlib plotly matplotx geopandas kaggle folium
   ```

3. **Kaggle API Key:**
   * A `kaggle.json` file, containing your Kaggle API credentials (username and key), is needed for downloading data from Kaggle.
   * If no `kaggle.json` file exists, create one with your API key by following the instructions in the Jupyter Notebook.

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Covid19_Data_Analysis.ipynb
   ```

**Data Source:**

The COVID-19 dataset is sourced from Kaggle.  Appropriate attributions are included in the notebook itself.  Refer to the code cells for specific details on the data origin.
url: https://www.kaggle.com/datasets/imdevskp/corona-virus-report



**Notebook Structure:**

The notebook is structured into logical sections for each stage of the analysis, making it easy to follow the process.  Clear comments within the code cells provide further explanations.

**Further Development:**

Possible expansions include:

* Implementing more advanced visualizations and time series analyses.
* Building predictive models using machine learning algorithms to forecast future trends.
* Expanding the analysis to include additional demographics or regional breakdowns for a more comprehensive understanding.

