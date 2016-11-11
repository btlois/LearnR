#Introductory R Exercises

The following is a list of suggested tasks to learn some aspects of the R language.
Feel free to explore on your own and try things that are not listed here.

1. Find the boston housing dataset [here](https://archive.ics.uci.edu/ml/datasets/Housing).  Read the dataset description.

2. Read the dataset directly into R.  Do not download the data locally.
hint: `read.table` accepts urls
- How many rows did you load?
- Print the column names you imported.
- Replace the column names you imported with better ones.
hint: go back and read the dataset description if you skipped this in #1.

3. Explore the data
- Determine the type of all variables. i.e. continuous, discrete, categorical
- Are any variables categorical? If so, make them factors.
- Use corrplot to observe dependencies within the data

4. Pick two variables to plot and perform a two dimensional k-means clustering anaysis.
- Plot the results

5. Perform a principal components analysis on the data.
- First subset to continuous variables
- plot the variances
- examine the rotation matrix

6. Build a model
- Generate at least one new column from the columns provided.
- Using the the original columns, your generated column(s), and the principal components,
  build a model to predict the median value `MEDV` column.
- Plot the residuals of your model


