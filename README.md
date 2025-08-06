Air Quality and Health Impact – Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis (EDA) to investigate the relationship between air quality indicators and health outcomes. The primary goal is to understand how various air pollutants correlate with respiratory and cardiovascular health issues.

📂 Project Structure • air_quality_health_impact_EDA.ipynb: The main notebook containing all EDA steps, visualizations, and analysis. • air_quality_health_impact_data.csv: The dataset used for analysis (referenced inside the notebook). • correlation_matrix.csv: Output file containing the computed correlation coefficients between air pollutants and health indicators.

📊 Objectives 1. Identify correlations between pollutants and diseases: • Analyze how air pollutants such as PM2.5, PM10, NO2, SO2, and O3 relate to health indicators including Respiratory Cases, Cardiovascular Cases, and Hospital Admissions. • Generate and export a correlation matrix. 2. Analyze skewness and kurtosis: • Determine the distribution characteristics of pollutants and health metrics using skewness and kurtosis. • Understand whether the data exhibits symmetry or contains extreme outliers.

🛠️ Tools & Libraries • Python • Pandas • NumPy • Matplotlib / Seaborn (presumed for visualizations) • Jupyter Notebook

🚀 Getting Started 1. Clone this repository or download the notebook and dataset. 2. Make sure the dataset air_quality_health_impact_data.csv is in the same directory as the notebook. 3. Open air_quality_health_impact_EDA.ipynb in Jupyter Notebook or JupyterLab. 4. Run all cells to reproduce the analysis.

📌 Notes • The notebook handles basic data cleaning, descriptive statistics, and correlation analysis. • No missing values were found in the dataset as per initial inspection. • The correlation matrix can help prioritize which pollutants might be most critical to target for public health improvement.
