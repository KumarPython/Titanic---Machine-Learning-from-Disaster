# Titanic---Machine-Learning-from-Disaster

## Titanic - Machine Learning from Disaster


This is the legendary Titanic ML competition – the best, first challenge for you to dive into ML competitions and familiarize yourself with how the Kaggle platform works.

The competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

Read on or watch the video below to explore more details. Once you’re ready to start competing, click on the "Join Competition button to create an account and gain access to the competition data. Then check out Alexis Cook’s Titanic Tutorial that walks you through step by step how to make your first submission!


### Kaggle - https://www.kaggle.com/pythonkumar
### Twitter - https://twitter.com/KumarPython
### LinkedIn - https://www.linkedin.com/in/kumarpython/


### I used following techniques in this notebook
1. Loading Data using Pandas
2. Checking varible type for each column
3. Checking number of nulls in each column
4. Finding column in Dataset
5. Drop useless columns
6. Handling Missing value with Median and Mode
7. Checking occurance of each category
8. Data Visualiztion using Matplotlib
9. Checking Ouliers
10. Handling Categorical Data using Get_Dummies()
11. Concatenating the Original Dataset & the One after creating Dummies
12. Seggregating X & y.
13. Preprocessing Numeric Data using StandardScaler
14. Dropping useless columns after we get_dummies()
15. Splitting using train_test_split
16. Using Random Forest as ML model
17. Predicting & Scoring the Trained Model


**The Challenge**

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

**Goal**
It is your job to predict if a passenger survived the sinking of the Titanic or not.
For each in the test set, you must predict a 0 or 1 value for the variable.

**Metric**
Your score is the percentage of passengers you correctly predict. This is known as accuracy.

**Submission File Format**
You should submit a csv file with exactly 418 entries plus a header row. Your submission will show an error if you have extra columns (beyond PassengerId and Survived) or rows.

The file should have exactly 2 columns:

PassengerId (sorted in any order)
Survived (contains your binary predictions: 1 for survived, 0 for deceased)
