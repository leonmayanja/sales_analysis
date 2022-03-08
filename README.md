# Sales-Analysis
## Information
This project uses Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.
I start by cleaning the data. This involves:

* Dropping NaN values from DataFrame
* Removing rows based on a condition
* Changing the dtypes of certain columns

Once I have cleaned up the data, I move to the data exploration section. In this section I explore 4 high level business questions related to the data:

* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
* What product sold the most? Why do you think it sold the most?

To answer these questions I go through many different pandas & matplotlib methods. They include:

* Concatenating/ merging multiple csvs together to create a new DataFrame (pd.concat)
* Adding columns e.g. Months, Hours, Count, etc
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize the results
* Labelling the graphs