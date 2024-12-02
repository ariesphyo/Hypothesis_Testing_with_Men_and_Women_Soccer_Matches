# Hypothesis Testing with Men's and Women's Soccer Matches in Python 

Welcome! This hypothesis-testing project is part of my learning journey as a data analyst at DataCamp.

The datasets used in this analysis contain the results of every official men's and women's international football match since the 19th century, which you scraped from a reliable online source. This data is stored in two CSV files: women_results.csv and men_results.csv.

The questions are:

- Are more goals scored in women's international soccer matches than men's?

- You assume a **10%** significance level, and use the following null and alternative hypotheses:

- H0: The mean number of goals scored in women's international soccer matches is the same as men's.

- HA: The mean number of goals scored in women's international soccer matches is greater than men's.

## Project Instruction 

Perform an appropriate hypothesis test to determine the p-value, and hence the result, of whether to reject or fail to reject the null hypothesis that the mean number of goals scored in women's international soccer matches is the same as men's. Use a 10% significance level.

**Requirements to calculate p-value:**

For this analysis, you'll use Official FIFA World Cup matches since 2002-01-01, and you'll also assume that each match is fully independent, i.e., team form is ignored.

The p-value and the result of the test must be stored in a dictionary called result_dict in the form:
result_dict = {"p_val": p_val, "result": result}
where p_val is the p-value, and the result is either the string "fail to reject" or "reject", depending on the test result.

## Prerequisites

- Python
- Google Colab

## Required Libraries

- Pandas
- NumPy
- Matplotlib
- Pingouin
- SciPy 
