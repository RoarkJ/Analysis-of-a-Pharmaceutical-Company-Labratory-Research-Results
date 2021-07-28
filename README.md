# Pymaceutilcals Inc.
## This analyiss is of a pharmaceutical company's research into an anti-cancer treatments for squamous cell carcinoma (SCC)
## Tools used: Matplotlib, Pandas, Scipy Stats, and Numpy

### The steps taken to analyse the data are as follows:
1.) Checked the data for any duplicate mouse ID time points and remove all mice with duplicate timestamps.

2.) Geneerated a summary staticstics table consting of mean, median, variance, stardard deviation, and SEM of the tumor volume for each drug regimen.

3.) Generated a bar plot using Panda's DataFrame.plot() and pyplot. The Pandas bar plot showing the number of total mice for each treatment regimen throught the course of the study and the pyplot showing the number of datapoints for each treatment regimen.

4.) Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

5.) Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

6.) Selected a mouse that was treated with Capomulin and generate a line plot of time point versus tumor volume for that mouse.

7.) Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

8.) Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

