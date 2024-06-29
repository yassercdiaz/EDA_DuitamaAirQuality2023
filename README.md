# Exploratory Data Analysis of Air Quality in Duitama

## Project Description

This project performs an exploratory data analysis (EDA) of air quality levels in the municipality of Duitama. Using data collected from various monitoring stations, which are published on the ["Datos Abiertos Colombia"](https://www.datos.gov.co/Ciencia-Tecnolog-a-e-Innovaci-n/Calidad-del-Aire-Municipio-de-Duitama/aghd-ge2f/about_data), the analysis provides insights into the trends of various pollutants and the correlations between them.

### The analysis includes:

1. **Data Cleaning and Preprocessing**: Identification and treatment of missing and erroneous values.
2. **Analysis of Pollutant Distributions**: Histogram and other visualizations of pollutant levels.
3. **Visualization of Temporal Trends**: Analysis of pollutant trends over time.
4. **Correlation Analysis Between Variables**: Heatmap and other methods to analyze the relationship between different variables.

## Project Contents

- **eda.ipynb**: The Jupyter notebook containing the complete code and analysis.
- **data/**: Folder containing the CSV file with the air quality data.
- **README.md**: This file, describing the project.
- **requirements.txt**: File with the dependencies required to run the analysis.

## System Requirements

To run the analysis, you need to have Python 3 installed and the following packages:

- **pandas**
- **numpy**
- **matplotlib**
- **seaborn**

You can install them using the provided **`requirements.txt`** file with the following command:

```sh
pip install -r requirements.txt
