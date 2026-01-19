# Task 2 - Movie Rating Prediction 🎬

## Objective
Build a machine learning model to predict the IMDB rating of movies using numeric features from the dataset.

---

## Dataset
- Dataset: IMDB Top 1000 Movies dataset (CSV file)
- File used: `imdb_top_1000.csv`

---

## Features Used
- Released_Year
- Runtime
- Meta_score
- No_of_Votes
- Gross

Target:
- IMDB_Rating

---

## Steps Performed
1. Imported required libraries (pandas, numpy, matplotlib, seaborn, sklearn)
2. Loaded the dataset
3. Checked dataset info and missing values
4. Cleaned data:
   - Converted Released_Year to numeric
   - Converted Runtime from text to numeric
   - Converted Gross from comma-separated to numeric
5. Filled missing values using median
6. Removed duplicates
7. Performed EDA with charts:
   - IMDB rating distribution
   - Votes vs rating plot
   - Correlation heatmap
8. Train-test split
9. Trained Linear Regression Model
10. Evaluated performance using:
   - MAE
   - MSE
   - RMSE
   - R2 Score

---

## Result
The model successfully predicts IMDB ratings with acceptable accuracy.
Performance is evaluated using regression metrics and visualization of actual vs predicted ratings.

