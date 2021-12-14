# Applying-Python-in-Analytics

These are the tasks that I have done as Part of my Master's program. This is the level after familiarizing myself with Python.

It was a 05 ECTS worthy course

# Task 01: 
In this task, you have to work with a dataset in the file full group.csv (more details about the
data https://www.kaggle.com/imdevskp/corona-virus-report?select=full_grouped.csv). Note I
added three columns, ’year’, ’month’ and ’day’, extracted from the Date column, that may be useful in
some of the tasks. The dataset contains information about the number of confirmed, recovered and death
cases related to COVID 19 in the initial months. The dataset has one row for each day and country
combination. The columns with name starting ’New’ record the numbers for that specific day, while
other columns provide cumulative values up to that day. In the tasks, you have to select, summarize and
compare information in the dataset.
• Use either the original date column or the new year-month-day columns to determine what is the
earliest and latest date that appears in the dataset.
• Select the data for the month April. What is the total number of deaths in this month?
• Create a new dataframe with the two columns CountryRegion and WHO Region. Remove the
duplicates so that each combination of CountryRegion and WHO Region appears only once. What
is the number of different CountryRegion that appears in the dataset? Which WHO Region has the
most CountryRegion associated to it?
• Select the data for the months March and April, and for the country US. Was the average number
of daily new deaths higher in March or April in US?
