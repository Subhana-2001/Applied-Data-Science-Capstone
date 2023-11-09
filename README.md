# SpaceX Launch Data Analysis

This repository contains data analysis and machine learning models for SpaceX rocket launches.

## Table of Contents
- [Introduction](#introduction)
- [Data Collection](#data-collection)
- [Data Wrangling](#data-wrangling)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Interactive Visual Analytics with Folium](#interactive-visual-analytics-with-folium)
- [Machine Learning Predictive Analysis](#machine-learning-predictive-analysis)
- [Dashboard](#dashboard)
- [Presentation](#presentation)
- [Files](#files)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The aim of this project is to predict the success or failure of Falcon 9 rocket landings and analyze factors that contribute to successful landings. This analysis can be valuable for understanding the cost-effectiveness of SpaceX rocket launches.

## Data Collection

- Data was collected from SpaceX's API to gather information about rocket launches.
- Web scraping was performed using Beautiful Soup to collect additional data from Wikipedia.

## Data Wrangling

Data collected from multiple sources was cleaned, combined, and prepared for analysis.

## Exploratory Data Analysis (EDA)

- The main characteristics of successful or failed landings were identified.
- Relationships between rocket variables and landing outcomes were explored.
- Orbits and other factors affecting landing success rates were analyzed.

## Interactive Visual Analytics with Folium

An interactive map was created using Folium to display the SpaceX launch sites.

## Machine Learning Predictive Analysis

Machine learning models were trained to predict the success of rocket landings.

## Dashboard

A dashboard was built using Dash to provide interactive visualization of the data.

## Presentation

A detailed presentation summarizing the entire project and findings was created.

## Files

- `EDA diagrams`: Diagrams generated during the EDA process.
- `Prediction diagrams`: Diagrams related to predictive analysis.
- `Data Collection with Webscraping.ipynb`: Jupyter Notebook for web scraping.
- `Data Collection.ipynb`: Jupyter Notebook for data collection from SpaceX API.
- `Data Wrangling.ipynb`: Jupyter Notebook for data cleaning and preprocessing.
- `EDA with Data Visualization.ipynb`: Jupyter Notebook for EDA and data visualization.
- `EDA.ipynb`: Jupyter Notebook for general EDA.
- `Interactive Visual Analytics with Folium lab.ipynb`: Jupyter Notebook for creating the Folium map.
- `Machine Learning Prediction.ipynb`: Jupyter Notebook for machine learning models.
- `spacex_dash_app.py`: Code for the Dash dashboard.

## Installation

To run the code and notebooks, you will need Python and the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- folium
- dash
- scikit-learn

Install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn folium dash scikit-learn
```
## Usage
- Clone this repository.
- Explore the Jupyter notebooks to understand the analysis and results.
- Run the Dash dashboard with python spacex_dash_app.py.
- Review the presentation for a detailed overview of the project.

## Contributing
Contributions are welcome! If you'd like to make improvements, please open an issue or submit a pull request.
