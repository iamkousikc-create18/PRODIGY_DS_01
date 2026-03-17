PRODIGY_DS_01
Task 01: Data Visualization

📌 Objective
The primary objective of this task is to create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population, using the World Bank Population Dataset.

📂 Dataset Information
This dataset contains total population statistics for countries and regions worldwide, spanning over six decades.
- Source: World Bank Population Dataset
- Data Shape: 266 rows × 70 columns (as verified in the analysis).
- Time Period: 1960 to 2024.
- Key Columns:
    - Country Name: Name of the country or geographic region.
    - Country Code: Unique 3-letter identifier for each entity.
    - Indicator Name: Population, total.
    - Years (1960 - 2024): Annual population counts for each year.
  
🛠️ Tech Stack
- Language: Python 3.x
- Libraries:
    - Pandas: For data loading, checking shapes, and handling missing values.
    - Matplotlib & Seaborn: For generating histograms and bar charts.
    - NumPy: Used for performing Log Transformations to handle skewed data.
- IDE: Jupyter Notebook

📈 Key Insights from Analysis
Based on the data processing and visualizations:

- Data Distribution: The population data for the year 2024 is highly right-skewed on a normal scale.
- Extreme Outliers: A few specific countries/regions possess significantly larger populations compared to the global average.
- Scaling for Clarity: Due to the extreme variance, a Log Transformation was applied. This allowed the distribution to appear more balanced and interpretable.
- Data Integrity: A null check was performed on the population columns (e.g., 2022, 2024) to ensure the accuracy of the visualizations.
  
🚀 How to Run
Ensure the dataset file (API_SP.POP.TOTL_DS2...) is in the project directory.
Install the required libraries: pip install pandas matplotlib seaborn numpy.
Open the Jupyter Notebook and run the cells to generate the distribution plots.
