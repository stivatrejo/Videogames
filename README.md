## Overview
This project analyzes global video game sales to identify trends across platforms, genres, regions, and critic/user scores.
It includes data cleaning, preprocessing, and exploratory data analysis (EDA).

## Project Structure
```
videogames-analysis/
│── games_eng.ipynb        # Main notebook (cleaning + EDA)
│── games.csv              # Original dataset
│── games_eng_vis.pdf      # Notebook exported as PDF
│── README.md              # Project documentation
```

## Data Cleaning
- Handling missing values
- Type conversion (years, scores)
- Category normalization (platforms, ESRB)
- Removal of duplicates and inconsistencies
- Preparation of numerical variables

## Exploratory Data Analysis
- Global top-selling video games
- Platform performance over time
- Genre distribution by region
- Relationship between critic/user scores and sales
- Annual release trends

## Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run
```
pip install -r requirements.txt
jupyter notebook
```

## Author
Stivaliz Trejo Sánchez
