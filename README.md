Matplotlib Analysis of Anti-Cancer Pharmaceuticals
Compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens

In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. Report findings of drugs' success in reducing tumor size.
Questions

Look across all generated figures and tables and write at least 3 observations or inferences that can be made from the data.
Breakdown of Tasks

    Read in CSV data using pandas.
    Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. (Performed two ways for practice - one manually and the other using pandas.DataFrame.agg)
    Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen.
    Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
    Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
    Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.
    Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.
    Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
    Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Conclusions

    With a correlation of 0.84, there is a positive correlation between average tumor volume and weight within the subject mice.
    Capomulin and Ramicane had the most data points out of all the drugs present in the study.
    Capomulin and Ramicane were also the most successful drugs in reducing the size of the tumors within the mice subjects.

Disclaimer

This project was published for education purposes only. All data came from Trilogy Education Services

Copyright Trilogy Education Services © 2019. All Rights Reserved.
