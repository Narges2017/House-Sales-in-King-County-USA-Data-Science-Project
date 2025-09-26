# House Sales in King County, USA — Data Science Project

## Project Overview
This project focuses on analyzing housing sales data from King County, including the city of Seattle. The goal is to gain insights into key factors influencing house prices and to develop predictive models for estimating sale prices. The dataset includes transactions from May 2014 through May 2015.

## Dataset Description
The dataset provides detailed information about each home sold, such as number of bedrooms and bathrooms, living area size, lot size, year built, waterfront views, and more. These features collectively help in understanding market dynamics and predicting house prices.

### Key Features
- **id**: Unique identifier for each house
- **date**: Date of sale
- **price**: Sale price (target variable)
- **bedrooms**: Total bedrooms
- **bathrooms**: Total bathrooms
- **sqft_living**: Living area in square feet
- **floors**: Number of floors
- **waterfront**: Indicates if the house has a waterfront view
- **yr_built**: Year when the house was constructed

## Tools and Libraries
This analysis was performed using the following libraries and tools:
- Python 3
- pandas for data manipulation
- numpy for numerical operations
- matplotlib and seaborn for data visualization
- scikit-learn for building predictive models

## Data Preprocessing
Major preprocessing steps included:
- Removing irrelevant or redundant columns
- Handling missing values through imputation of means where appropriate
- Converting date fields into datetime format for easier manipulation
- Conducting initial data exploration and summary statistics

## Exploratory Data Analysis (EDA)
Exploratory analysis involved:
- Examining the distribution of key variables
- Visualizing relationships between features and house prices
- Detecting and addressing outliers within the dataset

## Model Development
- Built various regression models to predict house prices
- Employed polynomial feature transformation to capture nonlinear relationships
- Assessed model performance using metrics such as R-squared and cross-validation scores

## Results and Interpretation
- Summarized model accuracy and predictive capabilities
- Highlighted significant insights from the analysis
- Provided visual summaries of model performance

## How to Use
To reproduce or extend this analysis:
1. Clone this repository.
2. Ensure the required packages are installed.
3. Open the `01_project-scenario_House_Sales_in_King_Count_USA.ipynb` Jupyter notebook.
4. Run the cells in sequence to follow the complete analysis.

## Future Directions
Potential improvements and next steps:
- Incorporate additional external datasets to enhance model accuracy
- Explore alternative machine learning algorithms
- Refine feature engineering and data cleaning processes

## Contact Information
For questions, feedback, or collaboration opportunities, please communicate via GitHub or email.
