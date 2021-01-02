# Matplotlib : The Power of Plots

## Background
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

### Objective
Your tasks are to do the following:
- Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
- Use the cleaned data for the remaining steps.
- Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![image](https://user-images.githubusercontent.com/69765842/103465984-a6e77680-4d0e-11eb-9f71-785457e56688.png)

- Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.

![image](https://user-images.githubusercontent.com/69765842/103465943-61c34480-4d0e-11eb-8b7f-25aac14da499.png)

- Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

![image](https://user-images.githubusercontent.com/69765842/103465949-6d167000-4d0e-11eb-849a-761599f25049.png)

- Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![image](https://user-images.githubusercontent.com/69765842/103465960-7f90a980-4d0e-11eb-9fa0-b7bb5bcc91d0.png)

- Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
- Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

![image](https://user-images.githubusercontent.com/69765842/103465964-891a1180-4d0e-11eb-9cd8-98659aa4e1fa.png)

### Observation of the data:

1. In the output of cell 19, you can see that there is a positive correlation between mouse weight and average tumor volume when using the drug treatment Capomulin. The scatterplot shows the data moving in the same direction and with a correlation coefficient at 0.84, it is close to an almost perfect postive correlation.

2. In the output of cell 17, you can see a line plot showing how mouse s185 did on the drug treatment Capomulin over time(days). It was tracked by looking at the total tumor volume (mm3) over time. You can see that over the course of the days plotted, the treatment of Capomulin decreases the amount of total tumor volume in the s185 mouse, which shows that the drug treatment is working well.

3. In cell 13 and 14, we look at the distribution of male and female mice within the study. You can see from both pie charts that it is a pretty equal distribution of male and female mice being studied, with their being just a bit more male mice than female mice (51% to 49%).











