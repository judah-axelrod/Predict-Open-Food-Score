# Predict-Open-Food-Score
In this supervised learning task, I utilize the Open Food Facts dataset found here: https://www.kaggle.com/openfoodfacts/world-food-facts. Open Food Facts is an open-source, ever-growing database of information about worldwide food products found on product labels. In my analysis, I look to answer two questions:
1. Can I build a model to accurately predict the nutrition score (assigned by the country of France) of each food?
2. What are the most important underlying drivers of a food's nutrition score?

I make use of a variety of machine learning techniques to answer these questions, including:
- Linear Regression (using LASSO to perform feature selection and mitigate bias)
- KNN Regression
- Generalized Additive Model
- Decision Tree (just as a baseline model)
- Random Forest
- Boosting

Here is a quick overview of the files in this repository:
- **Open-Food-Facts-Report.pdf** is the full write-up of the analysis, with all code and charts coming in the Appendix starting on page 5
- **Open-Food-Facts-Report.Rmd** is the code that generates the pdf
- **brands_lookup.csv** is a lookup file I made to consolidate and clean many of the brand names associated with foods in the database
- The raw data is not included here, but it can be downloaded from Kaggle at the link up top

Thanks to Professor Xinghao Qiao and my peers in LSE's ST443 course for their teaching and collaboration.

