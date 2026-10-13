# World Happiness Analysis (2015–2019)

## Project Overview
This project explores the World Happiness Report dataset from 2015 to 2019 using Python. The goal is to analyze happiness scores across countries, study trends in Morocco, and explore relationships between happiness scores and selected indicators.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Project Objectives
- Explore and clean the dataset.
- Compare the highest and lowest happiness scores by year.
- Analyze Morocco's happiness score from 2015 to 2019.
- Compare Morocco with the average score of countries listed each year.
- Explore correlations between happiness scores and socioeconomic indicators.

## Key Findings
- Morocco's happiness score increased from 5.013 in 2015 to 5.254 in 2018, then decreased to 5.208 in 2019.
- Morocco's score was below the average score of countries listed in each annual dataset from 2015 to 2019.
- Finland recorded the highest score in both 2018 and 2019 in this dataset.
- The gap between the highest and lowest country scores exceeded 4.6 points in every year.
- In the 2019 dataset, GDP per capita had a positive correlation with happiness score across countries.

## Data Quality
- Combined dataset: 782 country-year records.
- One missing value was found in the perceptions of corruption column.
- No duplicate rows or duplicate country-year pairs were found.

## Limitations
- Report methodology and indicator definitions may vary across years.
- Correlation does not imply causation.
- Morocco-only correlations use just five yearly observations and should be interpreted cautiously.
- The annual average is an unweighted average of the countries listed in each dataset, not a population-weighted global average.

## Dataset
World Happiness Report dataset available through Kaggle:  
https://www.kaggle.com/datasets/unsdsn/world-happiness

## How to Use
Open `World_Happiness_Analysis.ipynb` in Google Colab or Jupyter Notebook and run the cells in order.

## Author
Badr Mhanna
