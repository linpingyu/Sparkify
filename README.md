# Sparkify
Capstone Project, Udacity Data Science Nanodegree

Github Repo:https://github.com/linpingyu/Sparkify

# Files Contained in this Repo
Notebook Sparkify.ipynb

Readme   Readme.md

### Overview:
Sparkify is a music streaming service just as Spotify and Pandora. The data provided is the user log of the service, having demographic info, user activities, timestamps and etc. We try to analyze the log and build a model to identify customers who are highly likely to quit using our service, and thus, send marketing offers to them to prevent them from churning. We use F1 score to measure of model performance because we need precision and recall at the same time as we don't want to miss too many customers who are likely to churn whilst we don't want to waste too much on those who are not likely to churn. The model we built has a F1 score of 0.800, which is 16% higher than sending everybody offers. There is also a short article about this project posted [here](https://medium.com/@Linpingyu/another-churn-analysis-using-pyspark-be6a6624f313).


### Data
User log extracted from our service.

### Packages:
PySpark, Pandas, Seaborn, Matplotlot.pylpot

### Models:
Logistic Regression, Gradient Boosted Trees, Support Vector Machines, Random Forest

### Methodology:
1. ETL
2. Define customer churn and EDA
3. Feature engineering
4. Modeling 
5. Evaluation
6. Feature import analysis

### Others:
This is mostly a practice of using spark environment to analyze large volume of data, the main part can be replicated locally by just using packages like panads and numpy. 
