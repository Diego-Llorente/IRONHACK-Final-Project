# Portuguese Housing Market Analysis

This project analyzes the Portuguese housing market using a dataset downloaded from Kaggle. The analysis involves data cleaning, wrangling, and visualization to extract valuable insights about housing trends in Portugal.

## Dataset

The dataset used in this project is available on Kaggle and can be accessed here:  
[Portugal House Panorama - Kaggle Dataset](https://www.kaggle.com/datasets/paulexx/portugal-house-panorama)

It contains various housing-related features such as property prices, location data, property characteristics, and more. This dataset is used to perform an exploratory data analysis and generate visualizations to uncover key insights about the Portuguese housing market.

## Project Overview

1. **Data Cleaning & Wrangling**:
    - The raw dataset was cleaned and preprocessed using Python.
    - Tasks performed include:
        - Handling missing values
        - Converting data types where necessary
        - Removing outliers and irrelevant columns
        - Standardizing column names

2. **Data Export**:
    - After the cleaning and wrangling process, the dataset was exported as a CSV file to ensure that the clean data could be easily accessed for further analysis.

3. **Data Visualization**:
    - The cleaned data was imported into **Tableau** to create a series of visualizations, including:
        - Distribution of property prices across different regions of Portugal
        - Analysis of property characteristics (e.g., area, number of rooms, etc.) versus price
    - These visualizations provide insights into the Portuguese housing market.

## Requirements

To run the data cleaning and wrangling portion of the project, you'll need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn

For the Tableau visualizations, you will need Tableau Desktop or Tableau Public to open the `.twbx` file containing the visualizations.


## How to Run the Project

1. **Data Cleaning and Wrangling**:
    - Open and run the `final_project_vs.ipynb` notebook to clean and preprocess the data.
    - Once the data is cleaned, export it as a CSV file (`final_project_complete.csv`).

2. **Data Visualization**:
    - Import the cleaned data into Tableau.
    - Open the `Final Project Ironhack.twbx` file in Tableau to explore the visualizations.

## Insights

Through the visualizations created in Tableau, the following insights can be drawn:
- Patterns in property prices across different regions.
- Relationships between property features (e.g., area, number of rooms, etc.) and price.
- Regional differences in property pricing and supply.

## Conclusion

This project provides an overview of the current state and trends in the Portuguese housing market. By using data cleaning, wrangling, and visualization techniques, this analysis offers valuable insights for both housing market professionals and individuals interested in the Portuguese real estate landscape.