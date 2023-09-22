# Seattle Real Estate Evaluation

## Introduction

This project aims to perform Exploratory Data Analysis (EDA) on real estate data from King County, Washington, USA. The goal is to derive insights and recommendations for potential buyers, specifically focusing on William and Angelo Rodriguez, a young professional couple looking for two new homes: one in the city center and another as a fixer-upper in the countryside of King County.

## Project Goals

1. Analyze real estate data to provide recommendations on suitable zip codes for the buyers.
2. Investigate urbanity based on population density.
3. Determine the optimal time of year to buy a country house in King County.

## Data Description

The dataset used is a comprehensive database containing information about the King County real estate market. Additionally, population density data from the US Census is integrated for analysis.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine.

2. Ensure you have the necessary dependencies installed:
   - [Pandas](https://pandas.pydata.org/)
   - [Matplotlib](https://matplotlib.org/)
   - [Seaborn](https://seaborn.pydata.org/)
   - [Geopandas](https://geopandas.org/)
   - [Plotly](https://plotly.com/)

3. Install the required libraries by running the command:
```bash
brew update
brew install postgresql
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

4. Acquire the data and configure the database connection. Ensure that the necessary environment variables are set (e.g., `DB_STRING`).

5. Execute the Jupyter notebook to perform the data analysis.

## Data Preprocessing

- Data types were adjusted, missing values were handled, and unreasonable data was corrected.

- Feature engineering was performed to calculate client scores based on specified criteria.

## Data Analysis

- The project involved visualizing real estate data on maps to provide meaningful insights.

- Maps were created to display average sales price, client scores, and population density by zip code.

## Conclusion

The project successfully provided valuable recommendations for potential buyers in King County. Insights on urbanity, timing of purchase, and pricing factors were derived.

## Further Steps

Potential next steps for this project include in-depth analysis of optimal purchasing times and further refinement of client recommendations.

## Acknowledgements

- Shapefile for King County: [Link to Dataset](https://gis-kingcounty.opendata.arcgis.com/datasets/kingcounty::zipcodes-for-king-county-and-surrounding-area-zipcode-area/explore)

## Versioning

- Notebook and insights by Simon Klemm.
- Version: 1.0
- Date: 2023-09-22

