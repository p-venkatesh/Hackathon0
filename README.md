# Problem Statement

Have you ever wondered how lenders use various factors such as credit score, annual income, the loan amount approved, tenure, debt-to-income ratio etc. and select your interest rates? 

The process, defined as ‘risk-based pricing’, uses a sophisticated algorithm that leverages different determining factors of a loan applicant. Selection of significant factors will help develop a prediction algorithm which can estimate loan interest rates based on clients’ information. On one hand, knowing the factors will help consumers and borrowers to increase their credit worthiness and place themselves in a better position to negotiate for getting a lower interest rate. On the other hand, this will help lending companies to get an immediate fixed interest rate estimation based on clients information. Here, your goal is to use a training dataset to predict the loan rate category (1 / 2 / 3) that will be assigned to each loan in our test set.

You can use any combination of the features in the dataset to make your loan rate category predictions. Some features will be easier to use than others.



# Data ScreenShot

<img src="Screenshot 2020-06-01 at 7.39.59 AM.png">


# A Description of my Methodology


   ### Feature Engineering & Approach


1. Loan_Amount_Requested was converted to numeric by removing commas.
2. PreProcessed all of the data.
3. Filled all of the Nan Values.
4. Understanding the Data using descriptive statistics.
5. All the categorical features were Encoded to the numeric.
6. Handling the outliers in the data.
7. Created two new features.
8. I have used XGBoost which it has gave me 0.53663849301643, and Light GBM also given the same level of accuracy to me.


### Tools used


1. Python for programming.
2. sklearn and numpy libraries for methodology.
3. LightGBM and XGBoost for the final model.
4. matplotlib and seaborn was used for plotting and analyzing the data.


## Evaluation Metric
The evaluation metric for this competition is Weighted F1 Score.


# Competition Result


1. Rank: 39th on public LB.

<img src = "Screenshot 2020-06-01 at 12.00.16 AM.png">


2. Rank: 82th on private LB.

<img src = "Screenshot 2020-06-01 at 8.53.39 AM.png">

3. Top 1 percentile.

4. [Link to LeaderBoard](https://datahack.analyticsvidhya.com/contest/janatahack-machine-learning-for-banking/#LeaderBoard "LCO")
