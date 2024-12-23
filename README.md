# Forage: BCG X - Data-Science Job Simulation

![download](https://github.com/user-attachments/assets/bf707a31-482a-437d-a024-6712349bd694)


Four tasks make up this virtual experience programme.

1: Business Understanding & Hypothesis Framing

2: Exploratory Data Analysis

3: Feature Engineering & Modelling

4: Findings & Recommendations

# ♦ Task 1 - Business Understanding & Hypothesis Framing

**Here is the background information on your task:**

PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers. A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After discussion with your team, you have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities. Your AD wants an email with your thoughts on how the team should go about testing this hypothesis. The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.

**Here is your task:**

Your first task today is to understand what is going on with the client and to think about how you would approach this problem and test the specific hypothesis.

You must formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis. Communicate your thoughts and findings in an email to your AD, focusing on the data that you would need from the client and the analytical models you would use to test such a hypothesis.

# ♦ Task 2 - Exploratory Data Analysis

Exploratory data analysis (EDA) is a technique used by a Data Scientist to gain a holistic understanding of the data that they are working with. It is mainly based around using statistical techniques (such as descriptive statistics) and visualizations to gain a deeper understanding of the statistical properties that the data holds.

**The client has sent over 3 data sets (shown below):**

- Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
- Historical pricing data: variable and fixed pricing data etc
- Churn indicator: whether each customer has churned or not

**You need to analyze the following using Python:**

- The data types of each column
- Descriptive statistics of the dataset
- Distributions of columns

**Here are some tips to help you:**

Let’s take a look at the 3 data sets PowerCo. has sent over:

A first good step is to review the data to make sense of the columns…
Hint: Look at data types of column to gain a better understanding of what the columns mean. This is why data description documents are important - they describe exactly what the columns represent.
 
Once you understand the columns in the dataset. Now you want to look at how the values in the data vary…
Hint: this is why reporting descriptive statistics is useful because it’ll tell you some basic statistical properties of the columns in the data. It will also tell you how many values feature within a column, e.g. does a column only have 1 unique value or 100? This is useful to know because you can then start to build a picture of what this data represents.
 
You now understand how the values vary and what the data represents - next up, it can be useful to visualize some of this…
Hint: Not all visualizations are useful. Keep the visualizations simple and always keep in mind what you’re trying to show. E.g. if you want to see how the distribution of a column looks and that column has 1000 unique values, using a pie chart would not be good because it would become too crowded! If the values are numeric, a distribution plot would be more appropriate.
Hint: make sure to use the starter Jupyter notebook provided, as this will show you some example visualizations and sample code to use!
 
At this stage, you should now have a clearer understanding of what the data is and how it looks. This framework is not exhaustive, but it shows how you could start to build your own framework for analysing data.

# ♦ Task 3 - Feature Engineering & Modelling

**Feature engineering refers to:**

- Addition
- Deletion
- Combination
- Mutation
of your data set to improve machine learning model training, leading to better performance and greater accuracy.

In context of this task, feature engineering refers to the engineering of the price and client data to create new columns that will help us to predict churn more accurately. Effective feature engineering is based on sound knowledge of the business problem and the available data sources.

Your task is to create new features for your analysis and upload your completed python file. We'll show you an example answer on the next step, but we encourage you to give it a go first! Below are some tips on how to get started. 

As before, a good way to quickly learn how to effectively feature engineer is to build a framework to follow. Below is an example of how you could attempt this task:

First - can we remove any of the columns in the datasets?

There will almost always be columns in a dataset that can be removed, perhaps because they are not relevant to the analysis, or they only have 1 unique value.

Second - can we expand the datasets and use existing columns to create new features?

For example, if you have “date” columns, in their raw form they are not so useful. But if you were to extract month, day of month, day of year and year into individual columns, these could be more useful.

Third - can we combine some columns together to create “better” columns?

How do we define a “better” column and how do we know which columns to combine?
We’re trying to accurately predict churn - so a “better” column could be a column that improves the accuracy of the model.
And which columns to combine? This can sometimes be a matter of experimenting until you find something useful, or you may notice that 2 columns share very similar information so you want to combine them.

# ♦ Task 4 - Findings & Recommendations

It is your task to:

- Train a random forest classifier to predict churn.

- Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed.

- Finally - can we combine these datasets and if so, how?

To combine datasets, you need a column that features in both datasets that share the same values to join them on.
At this stage, your data could look vastly different, or may have just some subtle differences to how it was before.

The outputs of your work will be shared with the AD and Estelle has given you a few points to include within the notebook:

- Why did you choose the evaluation metrics that you used? Please elaborate on your choices.

- Do you think that the model performance is satisfactory? Give justification for your answer.

- Make sure that your work is presented clearly with comments and explanations

# 
📣 Feel free to have a look at all the files in this repository !🤗

❎ In case you find issues in any of my Repositories, you can Hit Me Up [here](https://github.com/issues)! 👈
