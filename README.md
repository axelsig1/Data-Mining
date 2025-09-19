# Data Mining Project: Analysis of EU Countries

This repository contains data analysis, preprocessing scripts, and visualizations for a data mining project focused on various socio-economic indicators across EU countries.

## Project Structure

```
.
├── assignment2.ipynb
├── education.ipynb
├── EU_countries.csv
├── output.png
├── README.md
├── survival_rate_in_primary_education.csv
├── test.ipynb
├── www.csv
└── Project-Data-Mining-I-main/
    ├── .gitignore
    ├── countries_clusters.csv
    ├── data_clustering.py
    ├── data_processing.ipynb
    ├── elbow_method.png
    ├── LICENSE.md
    ├── README.md
    ├── Suicide_cluster.png
    ├── data/
    │   ├── EU_countries.csv
    │   ├── EU2019_Alcohol_consumption.csv
    │   ├── EU2019_Annual_Sunshine.csv
    │   ├── EU2019_avg_age_of_leaving_parental_home.csv
    │   ├── EU2019_Gini_Index.csv
    │   ├── EU2019_internet_usage.csv
    │   └── ...
    └── data/
        └── raw_data/
            └── [preprocessing scripts and raw data]
```

## Contents

- **education.ipynb**: Analysis and normalization of education data for EU countries.
- **test.ipynb**: Exploratory data analysis and frequent pattern mining.
- **Project-Data-Mining-I-main/data_clustering.py**: Clustering of EU countries based on selected features using KMeans, and visualization of cluster characteristics.
- **Project-Data-Mining-I-main/data/**: Contains cleaned and processed datasets for various indicators (unemployment, alcohol consumption, Gini index, etc.).
- **Project-Data-Mining-I-main/data/raw_data/**: Scripts for preprocessing raw data files.
- **Visualizations**: Includes plots such as elbow_method.png and Suicide_cluster.png.

## How to Run

1. **Install dependencies**  
   Make sure you have Python 3.x and the required libraries:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn pyfpgrowth
   ```

2. **Data Preprocessing**  
   Run the scripts in `Project-Data-Mining-I-main/data/raw_data/` to clean and prepare the raw data.

3. **Analysis and Visualization**  
   - Use the Jupyter notebooks (`education.ipynb`, `test.ipynb`, `data_processing.ipynb`) for step-by-step analysis.
   - Run `data_clustering.py` to perform clustering and generate cluster visualizations.

## Data Sources

- Country codes and EU country lists from [iban.com](https://www.iban.com/country-codes)
- Socio-economic indicators from various public datasets (see `data/raw_data/` for details).
